![Image]"2-Tier Multi-AZ Server Infrastructure.png"
# multi-tier-server-infrastructure
# Deploy 2-Tier Multi-AZ Server Infrastructure

I have completed a project involving deploying a two-tier, multi-AZ server infrastructure. The architecture was designed to meet the following requirements:

- Two private Linux servers in different availability zones (AZ).
- Two public Linux servers in different AZs.
- Servers allocated to private and public subnets.
- Main and custom route tables equipped with an internet gateway and NAT gateway.

## Project Overview

This project aimed to deploy a resilient and scalable infrastructure utilizing Linux servers across multiple availability zones. Key features include:

- **Multi-AZ Deployment:** Strategic placement for redundancy.
- **Subnet Configuration:** Enhanced security and traffic control.
- **Routing Infrastructure:** Internet and NAT gateways for communication and external connectivity.
- **Secure Access:** Connection to private Linux servers via a jump or bastion server in the public subnet.

## Technology Stack

- **Operating System:** Linux (Ubuntu, CentOS, etc.)
- **AWS Services:**
  - Amazon EC2 for virtual servers.
  - Amazon VPC for networking and subnet isolation.
  - Amazon Route 53 for DNS management.
  - Amazon NAT Gateway for outbound internet traffic.
  - ...

## Deployment Process

The deployment process prioritized reliability, security, and best practices.

## Connectivity

After deployment, secure connections to private Linux servers were established using a jump or bastion server in the public subnet.

## Conclusion

This project successfully implemented a multi-tier, multi-AZ server infrastructure, meeting specified requirements with optimal reliability and security.


