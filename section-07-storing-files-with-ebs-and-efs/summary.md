
### EBS => Elastic Block Store
### EFS => Elastic File System

### Differen Kinds of File Storage:
  - Block Storage: an unformatted hard drive attached to ec2 instance, format and structure before using
    => Attach a virtual hard drive to a server : [EBS]
  - Object Storage: no information about underlying system, store and retrive files of any kind of size as needed
    => store files without caring about the underlying system: [S3]
  - File System: a network file system, a pre-formatted and configured file system 
    => get a virtual file system without any manual setup: [EFS, FSx]

### EC2 Instance Storage => default EBS-backed as a base storage for EC2 instances.

### EBS vs EFS
  - unformatted hard drive vs pre-formatted file system
  - ec2-exclusive(only for ec2 instances) vs can be used with multiple services.

