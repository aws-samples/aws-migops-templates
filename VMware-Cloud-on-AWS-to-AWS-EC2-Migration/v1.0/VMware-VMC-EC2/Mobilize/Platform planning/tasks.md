
# Module: Platform planning
## Task 1: Create Target Account Architecture
#### Description
Create Target Account Architecture
## Task 1: Subtask 1: Implement Target Account Model
#### Description
Ensure that the target account model in the landing zone follows best practices.For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Account-Design.md)
Create an account-architecture document that hightlights the overall account structure. 
## Task 1: Subtask 2: Conduct design sessions, workshops to define network strategy
#### Description
Conduct Basic training, design landing zone/control tower setups to define account configurations, naming conventions, networking, security and tagging strategy.

https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Workshops/Landing-Zone-Training.md
https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Workshops/Ozone-Core-Account-Onboarding.md
[Landing-Zone-VPC-and-Subnet-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-VPC-and-Subnet-Design.md)
[Landing-Zone-AWS-Region-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-AWS-Region-Design.md)
[Landing-Zone-Transit-Gateway-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Transit-Gateway-Design.md)
https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-VPC-and-Subnet-Design.md
https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-DNS-Design.md

## Task 1: Subtask 3: Overview and Design Core Account Configuration and Naming Conventions
#### Description
An AWS multi-account landing zone requires the provisioning of a new AWS account to act as the Master Account in the AWS multi-account landing zone environment.For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Workshops/Ozone-Core-Account-Onboarding.md)
## Task 2: Networking
#### Description
Define scope, objectives, and expected outcomes for the workstream
## Task 2: Subtask 1: Design VPC and CIDR and AZ
#### Description
Provisioning a landing zone requires designing multiple AWS services. Some of the core components are: 
1) VPC and subnets 
2) CIDR 
3) AZ 

For more information, see GitHub: 
[Landing-Zone-VPC-and-Subnet-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-VPC-and-Subnet-Design.md)
[Landing-Zone-AWS-Region-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-AWS-Region-Design.md)
[Landing-Zone-Transit-Gateway-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Transit-Gateway-Design.md)
## Task 2: Subtask 2: Design Security Groups and NACL
#### Description
A security group controls the traffic that is allowed to reach and leave the resources that it is associated with. When you create a VPC, it comes with a default security group. You can create additional security groups for each VPC. You can associate a security group only with resources in the VPC for which it is created. For each security group, you add rules that control the traffic based on protocols and port numbers. There are separate sets of rules for inbound traffic and outbound traffic.
## Task 2: Subtask 3: Design WAN and VPC Connectivity
#### Description
Provisioning a landing zone requires designing multiple AWS services. VPC and WAN connectivity are critical while setting up landing zone. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-VPC-and-Subnet-Design.md)
## Task 2: Subtask 4: Design Name Resolution and DNS
#### Description
A Domain Name System (DNS) is like a phone book that translates human-readable domain names into computer-friendly IP addresses. DNS providers contain records of domains and their corresponding IP Addresses. The most commonly used DNS records are CNAME, ANAME, and NS records. More information is available here: [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-DNS-Design.md)
## Task 3: Implement/extend Landing Zone
#### Description
Implement/extend Landing Zone
## Task 3: Subtask 1: Review & Implement Landing Zone Parameters
#### Description
Ensure the following checklist is completed : 
1) Control Tower Region 
2) Landing Zone Core Account Configuration 
3) Log Archive Email Address ( Email address used to create a centralized log archive account) 
4) Security Account Email Address (Email address used create a centralized security account) 
5) Security Alert Email Address (Email for all the Security Alerts related to Landing Zone)

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Control-Tower---Launch-Parameters.md)

When all the prerequisites and parameters are met, set up the landing zone in the desired AWS Region. For more information, see [Review and Set up](https://docs.aws.amazon.com/controltower/latest/userguide/review-and-set-up.html.)
## Task 3: Subtask 2: Implement/extend Landing Zone
#### Description
When all the prerequisites and parameters are met, set up the landing zone in the desired AWS Region. For more information, see [Review and Set up](https://docs.aws.amazon.com/controltower/latest/userguide/review-and-set-up.html.)
## Task 4: Inventory existing AWS accounts and Resources
#### Description
Inventory existing AWS accounts and resources
## Task 4: Subtask 1: Conduct Interviews to understand current account structure
#### Description
Review the current account structure details to help create new accounts in AWS Landing Zone.
Create required accounts, architecture diagrams based on new account structure. Establish networking resources
https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Network-Design.md

Verify AWS limits and requests quotas where necessary, work with the responsible teams to define monitoring & observability needs, define tagging strategy

https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Account-Design.md

https://docs.aws.amazon.com/controltower/latest/userguide/monitoring-overview.html.
## Task 5: Kick Off Long Range Planning
#### Description
A clear understanding of the landing zone workstream delivery workflow.
## Task 5: Subtask 1: Review the workstream scope, objectives and expected outcomes
#### Description
Establish a landing zone that extends the customer's on-prem hosting capability, making it possible to migrate existing applications and to develop new applications in AWS. Review the workstream scope, objectives, and expected outcomes. Review the workstream action items with my team so that responsibilities can be properly established and assigned.
## Task 5: Subtask 2: Review and refine workstream backlog
#### Description
Review the workstream action items with my team so that responsibilities can be properly established and assigned.