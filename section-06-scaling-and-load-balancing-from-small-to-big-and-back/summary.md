## AWS Compute Scaling Services

### EC2 Auto Scaling
  - service which can be used to automatically add / remove EC2 instances (based on conditions that we set).
  - ensures sufficient capacity at all times, without over-provisioning.

### Elastic Load Balancer (ELB)
  - service to distribute load evenly across available instances.
  - ensures that all available instances are utilized equally.
  - two types:
    - ALB => application load balancer (limited to: http & https)
    - NLB => network load balancer (TCP, UDP, TLS)
  - ALB & NLB don't automatically distribute traffic across all instances that exist. Instead, you have to define which instances should be covered (via target groups).

