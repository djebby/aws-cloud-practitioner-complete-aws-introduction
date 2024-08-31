## Using AWS to run compute tasks in the could

- EC2 (Elastic Compute Cloud) => rent a virtual remote server/computer, FULLY CONFIGURABLE, run any kind of workload in the cloud.
- ECS (Elastic Container) / EKS (Elastic Kubernetes) => alternative to EC2 for containerized workloads.

- Lambda (Serverless Code Execution) => run code without provisioning any infrastructure.

EC2 Instance = virtual server that use a slice of the physical machine completely isolated from other instances, choose hardware profile, operating system and install any software.

### Launch an instance
  1) Choose an Application and OS Images
  2) Instance Type [Amazon EC2 Instance Types](https://aws.amazon.com/ec2/instance-types/)
  3) Key pair (login) [Connect with SSH](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/connect-linux-inst-ssh.html)
  4) Network settings (pick a security group)
  5) Configure storage

### EC2 Pricing
  - On Demand Instances:
    - default & most flexible option
    - pay for usage
    - no discounts
    - price depends on chosen config
  - Spot Instances
    - spare instances, can be reclaimed any time.
    - ideal for workloads that can be interrupted.
  - Savings Plan
    - pay in advance (for chosen amt. of usage)
    - discounts over on-demand pricing
  - Reserved Instances
    - pay in advance (for chosen instance types)
