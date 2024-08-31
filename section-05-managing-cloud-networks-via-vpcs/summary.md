## VPCs => Virtual Private Cloud (under Networking & Content Delivery services)

resourrces (e.g., EC2 instances) are grouped & organaized in a customer-managed network.
IP address assignment & network traffic can be controlled via VPCs


Public Subnet => associated with a route table that has an internet gateway route.
              => instances can communicate with each other AND THE INTERNET.

Private Subnet => associated with a route table that has no internet gateway route.
               => instances can communicate with each other only.

CIDR = "Classless Inter-Domain Routing", (CIDR notation example : 172.31.0.0/16)

### Elastic IPs
  automatically assigned IPs (by subnet) will change when instances are stopped / restarted
  => you can't control which public IP address gets assigned to an instance

  Elastic IPs don't change and can be re-assigned
  Elastic IPs are managed & assigned by you
  
### VPC Peering => for connecting 2 VPCs
### Transit Gateways => for connecting more than 2 VPCs

### VPC Endpoints => connect AWS services to VPCs, send request via AWS network (AWS PrivateLink) - no internet connectivity required.

