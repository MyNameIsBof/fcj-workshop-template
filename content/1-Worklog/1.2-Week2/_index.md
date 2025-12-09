---
title: "Week 2 Worklog"
date: "2025-09-09"
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---


### Week 2 Objectives:

* Gain proficiency in AWS network security concepts, specifically Security Groups and Network ACLs.
* Explore VPC connectivity options and understand different network interconnection methods.
* Study load balancing principles and familiarize with AWS Elastic Load Balancer types and their use cases.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Study Security Groups: <br>&emsp; + Core concepts and stateful behavior <br>&emsp; + Rule creation and configuration procedures <br>&emsp; + Application to Elastic Network Interfaces | 08/11/2025 | 08/11/2025 | <https://cloudjourney.awsstudygroup.com/> |
| 3 | - Explore Network ACL (NACL): <br>&emsp; + Fundamental concepts and stateless characteristics <br>&emsp; + Key differences between NACL and Security Groups <br>&emsp; + Sequential rule evaluation from top to bottom | 08/12/2025 | 08/12/2025 | <https://cloudjourney.awsstudygroup.com/> |
| 4 | - **Hands-on Practice:** <br>&emsp; + Create Security Group for EC2 instance <br>&emsp; + Configure NACL for subnet <br>&emsp; + Compare security effectiveness between both methods <br> - Study VPC Flow Logs | 08/13/2025 | 08/13/2025 | <https://cloudjourney.awsstudygroup.com/> |
| 5 | - Learn about VPC connectivity: <br>&emsp; + VPC Peering and its limitations <br>&emsp; + Transit Gateway <br>&emsp; + Site-to-Site VPN <br>&emsp; + AWS Direct Connect | 08/14/2025 | 08/14/2025 | <https://cloudjourney.awsstudygroup.com/> |
| 6 | - Study Elastic Load Balancing: <br>&emsp; + ELB concepts and types <br>&emsp; + Application Load Balancer (ALB) <br>&emsp; + Network Load Balancer (NLB) <br>&emsp; + Sticky Session and Health Check <br> - **Hands-on Practice:** <br>&emsp; + Create ALB to distribute traffic <br>&emsp; + Configure Target Groups | 08/15/2025 | 08/15/2025 | <https://cloudjourney.awsstudygroup.com/> |


### Week 2 Achievements:

* Developed clear understanding of Security Groups and NACL:

  * Security Groups function as stateful firewalls that only permit "allow" rules

  * NACL serves as a stateless firewall applied at the subnet level

  * Security Groups operate at the instance level, while NACL affects all servers within a subnet

* Learned to utilize VPC Flow Logs for monitoring IP traffic within VPC without capturing packet contents.

* Understood various VPC connection methods:

  * VPC Peering connects two VPCs but does not support transitive routing

  * Transit Gateway enables connectivity between multiple VPCs and on-premises networks

  * Site-to-Site VPN uses Virtual Private Gateway and Customer Gateway

  * AWS Direct Connect provides dedicated connections with low latency (20-30ms)

* Gained proficiency in Elastic Load Balancing:

  * Four main types: ALB, NLB, Classic Load Balancer, and Gateway Load Balancer

  * ALB operates at Layer 7, supporting HTTP/HTTPS and path-based routing

  * NLB operates at Layer 4, supporting TCP/TLS and providing static IP addresses

  * Key features include Health Check, Sticky Session, and Access Logs

* Successfully completed hands-on practice:

  * Created Security Groups for EC2 with appropriate rules

  * Configured NACL for subnet with logical rule ordering

  * Set up Application Load Balancer with Target Groups

  * Verified Load Balancer operation and traffic distribution

* Developed ability to compare and select appropriate security solutions and network connectivity options for specific use cases.


