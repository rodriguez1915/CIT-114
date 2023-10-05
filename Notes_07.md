# Storage
_______________________________________________________________
### Storage is another AWS core service category. Some broad categories of storage include: instance store (ephemeral storage), Amazon EBS, Amazon EFS, Amazon S3, and Amazon S3 Glacie

## Amazon ELastic Block Store (Amazon EBS)
### Persistent storageis any datastoragedevice that retains data after power to that device is shut off. It is also sometimes called non-volatile storage. 
### Each Amazon EBS volume is automatically replicated within its Availability Zone to protect you from component failure. It is designed for high availability and durability. Amazon EBS volumes provide the consistent and low-latency performance that is needed to run your workloads.
#### Amazon EBS enables you to createindividualstoragevolumesand attachthemto an Amazon EC2 instance:
##### •Amazon EBS offers block-level storage.
##### •Volumes are automatically replicated within its Availability Zone.
##### •It can be backed up automatically to Amazon S3 through snapshots.
##### •Uses include –
##### •Boot volumes and storage for Amazon Elastic Compute Cloud (Amazon EC2) instances
##### •Data storage with a file system
##### •Database hosts

## Amazon Simple Storage Service (Amazon S3)

### Amazon S3 is object-level storage, which means that if you want to change a part of a file, you must make the change and then re-upload the entire modified file. Amazon S3 stores data as objects within resources that are called buckets. 

## Amazon Elastic File System (Amazon efs)

### Amazon Elastic File System (Amazon EFS)provides simple, scalable, elastic file storagefor use with AWS services and on-premises resources. It offers a simple interface that enables you to create and configure file systems quickly and easily.

### Amazon EFS is built to dynamically scale on demand without disrupting applications—it will grow and shrink automatically as you add and remove files. It is designed so that your applications have the storage they need, when they need it.

## Amazon Simple Storage Service Glacier 

    Amazon S3 Glacier is a secure, durable, and extremely low-cost cloud storage service for data archiving and long-term backup

### Amazon S3 Glacier is a dataarchivingservicethat is designed for security, durability, and an extremelylowcost.
  * Amazon S3 Glacier is designed to provide 11 9s of durability for objects.
  * It supports the encryption of data in transit and at rest through Secure Sockets Layer (SSL) or Transport Layer Security (TLS).
  * The Vault Lock feature enforces compliance through a policy.
  * Extremely low-cost design works well for long-term archiving.
  * Provides three options for access to archives—expedited, standard, and bulk—retrieval times range from a few minutes to several hours.
