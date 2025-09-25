# Networking

Networking is the process of connecting computers, devices, and systems so they can communicate, share resources, and exchange data. In cloud computing, networking provides the foundation that allows services (compute, storage, databases, applications) to interact securely and efficiently across the internet and within private environments.


> Examples of Networking in AWS

Hosting a website on an EC2 instance and making it accessible through the internet using an Internet Gateway.

Creating a private subnet for a database that can only be reached from an application server, not the internet.

Using Route 53 to map a domain name (like myapp.com) to an AWS resource.

Connecting on-premises data centers to AWS via a VPN or Direct Connect for hybrid cloud setups.


> Key Concepts I Learned

VPC (Virtual Private Cloud): My own isolated network inside AWS.

Subnets: Logical divisions of a VPC; public subnets for internet-facing resources and private subnets for internal ones.

Route Tables: Rules that control where traffic flows.

Gateways:

Internet Gateway (IGW): Connects AWS resources to the internet.

NAT Gateway: Allows private resources outbound access to the internet.

Security Layers:

Security Groups: Instance-level, stateful firewalls.

Network ACLs: Subnet-level, stateless firewalls.

DNS (Domain Name System): Managed in AWS with Route 53 to translate human-readable names into IP addresses.

Hybrid Networking: VPNs and Direct Connect for linking AWS with on-premises environments.


>Reflections

Learning networking in AWS showed me that:

Networking is the backbone of the cloud — without it, services cannot communicate or scale effectively.

Designing secure networks requires careful planning of subnets, gateways, and security rules.

I realized the importance of balancing accessibility and security — for example, keeping databases in private subnets while allowing application servers controlled internet access.

The hands-on labs (building VPCs, launching EC2 instances, configuring gateways) helped me understand abstract concepts through practice.

Networking knowledge will be crucial for my future role as it ties directly into cloud architecture, security, and troubleshooting.
