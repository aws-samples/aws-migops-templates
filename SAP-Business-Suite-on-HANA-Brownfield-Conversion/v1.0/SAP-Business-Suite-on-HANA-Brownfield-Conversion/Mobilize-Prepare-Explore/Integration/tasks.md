
# Module: Integration
## Task 1: Prepare Integration Set-up
#### Description
Customer / Partner sets up integration to SAP.

## Task 1: Subtask 1: Implement Target  Account Model
#### Description
Ensure that the target account model in the landing zone follows best practices.For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Account-Design.md)
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
• Created landing zone and target account model
## Task 1: Subtask 2: Create Target State Architecture Document
#### Description
Create an account-architecture document that hightlights the overall account  structure. 
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
•  Documented desired-state architecture
## Task 2: Provision Integration
#### Description
SAP provision SAP integration to Customer and Partner project team. These are components like the cloud connector.

#### Tools
AWS Landing Zone
#### Tools
AWS Control Tower
#### Acceptance Criteria
• Complete knowledge on AWS Landing Zone and AWS Control  Tower
#### Acceptance Criteria
• Provisioned core components in AWS Landing Zone and AWS Control  Tower
## Task 2: Subtask 1: Basic Training
#### Description
An initial  knowledge of AWS Landing Zone and AWS Control Tower is important. A landing zone is a well-architected, multi-account AWS environment  that is a starting point from which you can deploy workloads and  applications. It provides a baseline to get started with multi-account  architecture, identity and access management, governance, data security,  network design, and logging. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Workshops/Landing-Zone-Training.md)
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
• Complete  knowledge on AWS Landing Zone and AWS Control Tower
## Task 2: Subtask 2: Overview and Design Core Account Configuration and Naming Conventions
#### Description
An AWS  multi-account landing zone requires the provisioning of a new AWS account to act as the Master Account in the AWS multi-account  landing zone environment.For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Workshops/Ozone-Core-Account-Onboarding.md)

#### Acceptance Criteria
•  Provisioned new Amazon Web Services (AWS) account
## Task 2: Subtask 3: Design VPC  and CIDR and AZ
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
AWS Virtual Private Cloud (VPC)
#### Tools
AWS Control Tower
#### Acceptance Criteria
•  Provisioned core components such as   
a) VPC and subnets  
b) CIDR  
c) AZ
## Task 2: Subtask 4: Design  Security Groups and NACL
#### Description
A  security group controls the traffic that is allowed to reach and leave the  resources that it is associated with. When you create a VPC, it comes with a  default security group. You can create additional security groups for each  VPC. You can associate a security group only with resources in the VPC for  which it is created.  For each security group, you add rules that control the traffic based on  protocols and port numbers. There are separate sets of rules for inbound  traffic and outbound traffic.
#### Tools
AWS Security Groups
#### Tools
Network ACLs
#### Acceptance Criteria
•  Created AWS security groups and NACLs
## Task 2: Subtask 5: Design WAN and VPC Connectivity
#### Description
Provisioning a landing zone requires designing multiple AWS services. VPC and WAN  connectivity are critical while setting up landing zone. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-VPC-and-Subnet-Design.md)
#### Tools
AWS Virtual Private Cloud (VPC)
#### Tools
AWS Control Tower
#### Acceptance Criteria
•  Set up of VPC and WAN connectivity is complete
## Task 2: Subtask 6: Design Name Resolution and DNS
#### Description
A  Domain Name System (DNS) is like a phone book that translates human-readable  domain names into computer-friendly IP addresses. DNS providers contain  records of domains and their corresponding IP Addresses. The most commonly  used DNS records are CNAME, ANAME, and NS records.  More information is available here:   [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-DNS-Design.md)
#### Tools
AWS Control Tower
#### Tools
AWS Virtual Private Cloud (VPC)
#### Acceptance Criteria
•  Completed domain name resolution
## Task 2: Subtask 7: Design Tagging
#### Description
[Landing-Zone-DNS-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-DNS-Design.md)
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
•  Completed tagging
## Task 3: Provision BTP
#### Description
The BTP platform must be provisioned and as part of the RISE welcome email, a section on BTP will be included, detailing the BTP provisioning process.

As part of the RISE welcome email that the Customer receives, a section on BTP will be included, detailing the provisioning of BTP.
## Task 3: Subtask 1: Review Landing  Zone Parameters
#### Description
Ensure the  following checklist is completed :  
1) Control Tower Region  
2) Landing Zone Core Account Configuration  
3) Log Archive Email Address ( Email address used to create a centralized  log archive account)  
4) Security Account Email Address (Email address used create a  centralized security account)  
5) Security Alert Email Address (Email for all the Security Alerts  related to Landing Zone)

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Control-Tower---Launch-Parameters.md)
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
• Reviewed  checklist of parameters required for creating an AWS landing zone
## Task 3: Subtask 2: Implement Landing Zone
#### Description
When all the prerequisites and parameters are met, set up the landing zone in the desired AWS Region. For more information, see [Review and Set up](https://docs.aws.amazon.com/controltower/latest/userguide/review-and-set-up.html.)
#### Tools
AWS Landing Zone
#### Tools
AWS Control Tower
#### Acceptance Criteria
• Reviewed checklist of parameters required for creating an AWS landing zone
#### Acceptance Criteria
• AWS landing zone created
## Task 4: Connectivity VPN/MPLS
#### Description
Customer and SAP work together with AWS to get the VPN setup or Direct Connect setup. Customer organises MPLS connection with SAP support.

#### Acceptance Criteria
• Verified checklist of items of landing-zone accounts
#### Acceptance Criteria
• Completed architecture design including missing components if any
#### Acceptance Criteria
• Reviewed current account structure details
## Task 4: Subtask 1: Conduct  Interviews to understand current account structure
#### Description
Review the  current account structure details to help create new accounts in AWS Landing  Zone.
#### Tools
AWS Landing Zone
#### Acceptance Criteria
• Reviewed  current account structure details
## Task 4: Subtask 2: Create missing Architecture Diagrams of Account  structure
#### Description
After you identify the account structure, create any missing accounts and complete the architecture diagrams for the account structure. 
#### Tools
AWS Landing Zone
#### Acceptance Criteria
• Completed architecture design including any missing components
## Task 4: Subtask 3: Identify and determine Network Resources for  use in AWS
#### Description
After you identify and create any missing accounts, identify the network resources for use in the landing zone. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Network-Design.md)
#### Tools
AWS Landing Zone
#### Acceptance Criteria
•  Identified the network component in AWS Landing Zone
## Task 4: Subtask 4: Complete Parameters Check List
#### Description
Ensure  the following checklist is completed:  
1) AWS Control Tower Region  
2) AWS Landing Zone core account configuration  
3) Log archive email address (Email address used to create a centralized  log archive account)  
4) Security account email address (Email address used to create a  centralized security account)  
5) Security alert email address (Email for all security alerts  related to the landing zone)
#### Tools
AWS Landing Zone
#### Tools
AWS Control Tower
#### Acceptance Criteria
•  Verified checklist of items of AWS Landing Zone accounts
## Task 4: Subtask 5: Request AWS Limit Increases
#### Description
AWS service quotas to be aware of while using AWS Control Tower: 
1) Email addresses of shared accounts in the security OU can be changed, but you must update your landing zone to see these changes in the AWS Control Tower console. 
2) A limit of 5 SCPs per OU applies to OUs in your AWS Control Tower landing zone. 
3) Existing OUs with over 300 accounts cannot be registered or re-registered in AWS Control Tower. 
4) The quota for EnableControl and DisableControl updates in AWS Control Tower is 10 concurrent operations. 

For more information, see [Limits](https://docs.aws.amazon.com/controltower/latest/userguide/limits.html.)
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
•  Finalized limit for each resource in AWS 
## Task 4: Subtask 6: Identify Monitoring Needs
#### Description
Monitoring is an important part of maintaining the reliability, availability, and  performance of AWS Control Tower and other AWS solutions. AWS provides the following monitoring tools to watch AWS Control Tower, report when something goes wrong, and take automatic actions when appropriate:  
1) Amazon CloudWatch  
2) Amazon CloudWatch Events  
3) Amazon CloudWatch Logs  
4) AWS CloudTrail

For more information, see [Monitoring overview](https://docs.aws.amazon.com/controltower/latest/userguide/monitoring-overview.html.)
#### Tools
AWS CloudWatch
#### Tools
AWS CloudTrail
#### Tools
Amazon CloudWatch Logs
#### Tools
Amazon CloudWatch Events
#### Acceptance Criteria
•  Completed list of AWS Monitoring tools
## Task 4: Subtask 7: Identify Organizational Tagging Strategy
#### Description
Determine the organizational tagging schema
#### Tools
AWS Landing Zone
#### Tools
AWS Control Tower
#### Acceptance Criteria
•  Completed resource tagging
## Task 4: Subtask 8: Verify Level of AWS Support
#### Description
When setting up accounts, we recommend selecting the correct AWS support level for the accounts. By default all accounts are setup with basic support.  

For information about AWS support levels and their features and cost comparisons, see [Pricing](https://aws.amazon.com/premiumsupport/pricing/.)
#### Acceptance Criteria
•  Finalized AWS support strategy
## Task 4: Subtask 9: Identify and Create Email Address Schema
#### Description
Design  details for the landing zone accounts. This is a reference implementation for  the landing zone that must be customized during design workshops to meet the specific needs of the customer.

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/LandingZone-ControlTower/Landing-Zone-Artifacts/Landing-Zone-Account-Design.md)
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
•  Identified AWS Landing Zone accounts
## Task 5: Optional Integration Suite provisioning
#### Description
Once the e-mail is received from SAP the customer can then provision the integration Suite (previously with CPI this was done by SAP) but now the customer has the ability to provision the tennant.

#### Acceptance Criteria
• Review the workstream scope, objectives and expected outcomes
#### Acceptance Criteria
• Key milestones have been identified and agreed upon
## Task 5: Subtask 1: Review the workstream scope, objectives and expected outcomes
#### Description
Establish a landing zone that extends the customer's on-prem hosting capability, making it possible to migrate existing applications and to develop new applications in  AWS. Review the workstream scope, objectives, and expected outcomes. 
#### Acceptance Criteria
• Key milestones have been identified and agreed upon
#### Acceptance Criteria
• Review the  workstream scope, objectives and expected outcomes 
## Task 5: Subtask 2: Review and refine workstream backlog
#### Description
Review  the workstream action items with my team so that responsibilities can be  properly established and assigned.
#### Acceptance Criteria
•  Tasks that must be completed to achieve the outcomes have been identified and  agreed upon
## Task 6: Integration Planning & Design
#### Description
After the Fit-to-Standard workshops, develop an aligned and optimized list of integrations to be implemented and tested during the Realize phase.The list is developed in four steps:
1. Handover of Business Requirements to Technical Expert
2. Check for SAP Best Practices
3. Define details, Optimise and align to develop final high-level list
4. Sign off list with customer
