
# Module: Platform planning
## Task 1: Design Workshops
#### Description
Define scope, objectives, and expected outcomes for the  workstream
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
• Complete knowledge on AWS Landing Zone and AWS Control  Tower
#### Acceptance Criteria
• Provisioned core components in AWS Landing Zone and AWS Control  Tower
## Task 1: Subtask 1: Basic Training
#### Description
An initial  knowledge of AWS Landing Zone and AWS Control Tower is important. A landing zone is a well-architected, multi-account AWS environment  that is a starting point from which you can deploy workloads and  applications. It provides a baseline to get started with multi-account  architecture, identity and access management, governance, data security,  network design, and logging. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Workshops/Landing-Zone-Training.md)
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
• Complete  knowledge on AWS Landing Zone and AWS Control Tower
## Task 1: Subtask 2: Overview and Design Core Account Configuration and Naming Conventions
#### Description
An AWS  multi-account landing zone requires the provisioning of a new AWS account to act as the Master Account in the AWS multi-account  landing zone environment.For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Workshops/Ozone-Core-Account-Onboarding.md)

#### Acceptance Criteria
•  Provisioned new Amazon Web Services (AWS) account
## Task 1: Subtask 3: Design VPC  and CIDR and AZ
#### Description
Provisioning a landing zone requires designing multiple AWS services. Some of the core  components are:  
1) VPC and subnets  
2) CIDR  
3) AZ 

For more information, see GitHub:   
[Landing-Zone-VPC-and-Subnet-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-VPC-and-Subnet-Design.md)
[Landing-Zone-AWS-Region-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-AWS-Region-Design.md)
[Landing-Zone-Transit-Gateway-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Transit-Gateway-Design.md)
#### Tools
AWS Control Tower
#### Tools
AWS Virtual Private Cloud (VPC)
#### Acceptance Criteria
•  Provisioned core components such as   
a) VPC and subnets  
b) CIDR  
c) AZ
## Task 1: Subtask 4: Design  Security Groups and NACL
#### Description
A  security group controls the traffic that is allowed to reach and leave the  resources that it is associated with. When you create a VPC, it comes with a  default security group. You can create additional security groups for each  VPC. You can associate a security group only with resources in the VPC for  which it is created.  For each security group, you add rules that control the traffic based on  protocols and port numbers. There are separate sets of rules for inbound  traffic and outbound traffic.
#### Tools
Network ACLs
#### Tools
AWS Security Groups
#### Acceptance Criteria
•  Created AWS security groups and NACLs
## Task 1: Subtask 5: Design WAN and VPC Connectivity
#### Description
Provisioning a landing zone requires designing multiple AWS services. VPC and WAN  connectivity are critical while setting up landing zone. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-VPC-and-Subnet-Design.md)
#### Tools
AWS Virtual Private Cloud (VPC)
#### Tools
AWS Control Tower
#### Acceptance Criteria
•  Set up of VPC and WAN connectivity is complete
## Task 1: Subtask 6: Design Name Resolution and DNS
#### Description
A  Domain Name System (DNS) is like a phone book that translates human-readable  domain names into computer-friendly IP addresses. DNS providers contain  records of domains and their corresponding IP Addresses. The most commonly  used DNS records are CNAME, ANAME, and NS records.  More information is available here:   [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-DNS-Design.md)
#### Tools
AWS Control Tower
#### Tools
AWS Virtual Private Cloud (VPC)
#### Acceptance Criteria
•  Completed domain name resolution
## Task 1: Subtask 7: Design Tagging
#### Description
[Landing-Zone-DNS-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-DNS-Design.md)
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
•  Completed tagging
## Task 1: Subtask 8: Running Active Directory in AWS
#### Description
Conduct a workshop to understand Active Directory deployment options. 
## Task 2: Inventory existing AWS accounts and Resources
#### Description
Inventory existing AWS accounts and resources
#### Acceptance Criteria
• Verified checklist of items of landing-zone accounts
#### Acceptance Criteria
• Reviewed current account structure details
#### Acceptance Criteria
• Completed architecture design including missing components if any
## Task 2: Subtask 1: Identify and determine Network Resources for  use in AWS
#### Description
After you identify and create any missing accounts, identify the network resources for use in the landing zone. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Network-Design.md)
#### Tools
AWS Landing Zone
#### Acceptance Criteria
•  Identified the network component in AWS Landing Zone
## Task 2: Subtask 2: Identify Monitoring Needs
#### Description
Monitoring is an important part of maintaining the reliability, availability, and  performance of AWS Control Tower and other AWS solutions. AWS provides the following monitoring tools to watch AWS Control Tower, report when something goes wrong, and take automatic actions when appropriate:  
1) Amazon CloudWatch  
2) Amazon CloudWatch Events  
3) Amazon CloudWatch Logs  
4) AWS CloudTrail

For more information, see [Monitoring overview](https://docs.aws.amazon.com/controltower/latest/userguide/monitoring-overview.html.)
#### Tools
AWS CloudTrail
#### Tools
Amazon CloudWatch Events
#### Tools
AWS CloudWatch
#### Tools
Amazon CloudWatch Logs
#### Acceptance Criteria
•  Completed list of AWS Monitoring tools
## Task 2: Subtask 3: Verify Level of AWS Support
#### Description
When setting up accounts, we recommend selecting the correct AWS support level for the accounts. By default all accounts are setup with basic support.  

For information about AWS support levels and their features and cost comparisons, see [Pricing](https://aws.amazon.com/premiumsupport/pricing/.)
#### Acceptance Criteria
•  Finalized AWS support strategy
## Task 3: Kick Off Long Range Planning
#### Description
A clear understanding of  the landing zone workstream delivery workflow.
#### Acceptance Criteria
• Review the workstream scope, objectives and expected outcomes
#### Acceptance Criteria
• Key milestones have been identified and agreed upon
## Task 3: Subtask 1: Review the workstream scope, objectives and expected outcomes
#### Description
Establish a landing zone that extends the customer's on-prem hosting capability, making it possible to migrate existing applications and to develop new applications in  AWS. Review the workstream scope, objectives, and expected outcomes. 
#### Acceptance Criteria
• Key milestones have been identified and agreed upon
#### Acceptance Criteria
• Review the  workstream scope, objectives and expected outcomes 
## Task 3: Subtask 2: Review and refine workstream backlog
#### Description
Review  the workstream action items with my team so that responsibilities can be  properly established and assigned.
#### Acceptance Criteria
•  Tasks that must be completed to achieve the outcomes have been identified and  agreed upon