Once after the cluster is ready we need to deploy WordPress and MySQL and attach PVC with storage class from EBS.

The EFS Provisioner is deployed as a Pod that has a container with access to an AWS EFS file system. 

A StorageClass resource is defined as, whose provisioner attribute determines which volume plugin is used for provisioning a PersistentVolume (PV). Here the StorageClass specifies the EFS Provisioner Pod as an external provisioner by referencing the value of the provisioner name

Role-based access control (RBAC) is a method of regulating access to a computer or network resources based on the roles of individual users. RBAC authorization allows us to dynamically configure policies through the Kubernetes API.