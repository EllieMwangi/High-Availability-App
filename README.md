## Cloudformation Template for a High Availability App

The following cloudformation template seeks to deploy infastructure for a **high availability** app on AWS using the architecture diagram portrayed [here](https://github.com/EllieMwangi/High-Availability-App/blob/main/UdagramDiagram.jpeg)

#### Network Infastructure template: network.yml
Sets up a VPC, 4 Subnets(2 Private, 2 Public), 2 NAT Gateways and corresponding route tables.
#### Server and Security Group Infastructure template: server.yml
Sets up an auto scaling group, load balancer and corresponding security groups
