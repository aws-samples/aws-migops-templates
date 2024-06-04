
# Module: Technical delivery
## Task 1: System Delivery
#### Description
SAP delivery team to provide access to the cloud systems.Once the Customer has signed the contract and all prerequisite technical details have been received, SAP provision the systems as per the customer's contract. Providing the PPF was complete within the stipulated time and as per the CDD, the customer's IT contact will receive the system handover e-mails with the URL, login ID, and password for all the respective systems. These emails will contain all necessary information to start the provisioning of the SAP solution. The Admin user ID and password will be provided in separate email communication. The systems handover detailed information will be accessible in the SAP One Support Launchpad useful link.Procedure:Locate the provisioning e-mails sent to the IT contact with system details. Confirm delivery and access to the systems. Follow the provisioning emails for details procedure. Follow the credentials email to receive and update the technical username and password.Note(s):The SAP Project Lead will securely provide the initial logon credentials.The technical user is a local SAP S/4HANA user and is not intended for day-to-day use, but rather for the creation of the new administrator business user.For any questions related to the status of the systems, the customer can reach out to the SAP team via email: engage-rise@sap.com or they can contact the Customer Interaction Center (CIC).

## Task 1: Subtask 1: Conduct Encryption, Data Protection and KMS Keys Governance Workshop
#### Description
AWS provides services that help you protect your data, accounts, and workloads from unauthorized access. Understand AWS encryption and key-management options to meet data protection requirements.
#### Tools
AWS Key Management Service
#### Acceptance Criteria
•  Defined AWS KMS Security policies
#### Acceptance Criteria
• Learned how encryption is done in AWS 
#### Acceptance Criteria
• Discovered data protection-related AWS services
#### Acceptance Criteria
• Considered your own encryption requirements 
#### Acceptance Criteria
• Understood customer responsibility for data in AWS 
## Task 1: Subtask 2: Document Data Protection Current and Readiness  State
#### Description
Capture documentation on the current state of data protection capability, including policy, process, tools, and teople, to identify gaps that need to be filled in order to achieve a security readiness state in AWS.
#### Acceptance Criteria
• Documented Data Protection Discovery and Analysis. This includes the following: 
a) Current State Overview 
b) Policy 
c) Process 
d) Tools 
e) People
## Task 1: Subtask 3: Conduct Data Protection Security Readiness  State Gap Analysis and Story Development
#### Description
Complete the gap analysis.
#### Acceptance Criteria
•  Completed gap analysis
## Task 1: Subtask 4: Define encryption at rest and transit strategy
#### Description
Encryption at rest means encryption of the data that is stored in the databases and is not moving through networks. Defining data management requirements, implementing secure key management, enforcing access control, and enforcing encryption at rest, all align to well-architected best practices 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Data-Protection/Encryption-At-Rest-Design.md). Encryption in transit is when the encrypted data is active and moving between devices and networks like the internet or within a company, or being uploaded to the cloud. It follows well-architected best practices to define data-protection-in-transit requirements, such as encryption standards, based on data classification to meet organizational, legal, and compliance requirements. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Data-Protection/Encryption-In-Transit-Design.md)
#### Tools
AWS Elastic File System
#### Tools
AWS S3  
#### Tools
AWS RDS
#### Tools
AWS Virtual Private Cloud (VPC)
#### Tools
AWS Elastic Block Store
#### Tools
AWS EC2
#### Acceptance Criteria
•  AWS resource encryption strategy for data in transit
#### Acceptance Criteria
•  AWS resource encryption strategy for data at rest
## Task 1: Subtask 5: Define KMS CMK administrators and users
#### Description
Implement  least privilege model for KMS CMKs so that only authorized consumers have access  to the keys.
#### Tools
AWS Key Management Service
#### Acceptance Criteria
•  Defined AWS KMS CMK administrators and users
## Task 1: Subtask 6: Develop encryption security controls
#### Description
Ensure that any data stored or transmitted inappropriately will be detected, so that workload and data owners get notified and automated corrective actions can be taken.
#### Tools
AWS CloudFormation
#### Tools
AWS Lambda
#### Acceptance Criteria
•  AWS CloudFormation template and AWS Lambda code to deploy standard data protection  controls
## Task 2: Verify delivered systems
#### Description
Partner to check that the system is delivered with the requested pre-configured business content.

#### Acceptance Criteria
• Setup Initial AWS accounts      
a) configure Root  
b) BreakGlass Password  
c) MFA  
d) Password Policy  
e) Alternative Contacts  
f) Security Challenge Questions  
g) Support Plan
#### Acceptance Criteria
• Documented  Identity and Access Management Discovery and Analysis 
#### Acceptance Criteria
• Completed gap analysis  
## Task 2: Subtask 1: Conduct Deep  Dive on Identity and Access Management Workshop
#### Description
With AWS Identity and Access Management (IAM), specify who or what can access services and resources in AWS, centrally manage fine-grained permissions, and analyze access to refine permissions across AWS.
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
• Decided on roles and policies
#### Acceptance Criteria
• Learned AWS Identity and Access Management (IAM)   
#### Acceptance Criteria
• Discovered identity federation options
#### Acceptance Criteria
• Reviewed AWS IAM policy language
#### Acceptance Criteria
• Understood when and where to use AWS IAM
## Task 2: Subtask 2: Document Identity and Access Management Current  and Readiness State
#### Description
Capture documentation on the current state of identity-and-access-management capability, including policy, process, tools, and people. Identify gaps that need to be filled to achieve a security readiness state in AWS.
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
• Learned AWS Identity and Access Management (IAM) 
#### Acceptance Criteria
• Discovered identity federation options 
#### Acceptance Criteria
• Understood when and where to use AWS IAM 
#### Acceptance Criteria
• Decided on roles and policies
#### Acceptance Criteria
• Documented AWS IAM discovery and analysis. This includes the following: 
a) Current state overview 
b) Policy 
c) Process 
d) Tools 
e) People
#### Acceptance Criteria
• Reviewed AWS IAM policy language 
## Task 2: Subtask 3: Conduct Identity and Access Management Security  Readiness State Gap Analysis and Story Development
#### Description
Conduct a gap analysis between the current and security-readiness states of identity and access management and develop stories to implement required changes, to achieve a security readiness state in AWS.
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Completed gap analysis
## Task 2: Subtask 4: Define permanent credentials usage policy
#### Description
Define the permanent credentials usage policy for AWS IAM users. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Human-IAM-Roles-and-Policies-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Defined AWS permanent credentials accounts and its usage policy so that  credentials need not be changed frequently
## Task 2: Subtask 5: Define multi account user authentication policy
#### Description
Define the multi-account user authentication policy for AWS IAM users. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Human-IAM-Roles-and-Policies-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Defined AWS multi-account users and usage policy 
## Task 2: Subtask 6: Define base IAM roles and IAM policies naming  standard and definition
#### Description
Define the naming conventions for AWS IAM roles and policies. It is important to have a standard naming style across all AWS resources. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/IAM-Resources-Naming-Convention.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Followed the naming conventions for AWS IAM roles and policies as defined in the guidelines
## Task 2: Subtask 7: Define base preventative controls SCPs
#### Description
Define base security control policies (SCPs).  For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Service-Control-Policies-(SCPs)-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Well-defined base security control policies (SCPs)
## Task 2: Subtask 8: Build base preventative controls SCPs
#### Description
Define base security control policies (SCPs).  For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Service-Control-Policies-(SCPs)-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Built base security control policies (SCPs)
## Task 2: Subtask 9: Build base IAM identities such as IAM roles and  IAM policies
#### Description
Manage access in AWS by creating policies and attaching them to AWS IAM identities (users, groups of users, or roles) or AWS resources. A policy is an object in AWS that, when associated with an identity or resource, defines their permissions For more information, see [Access Policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html.)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Defined and built AWS IAM roles and policies
## Task 2: Subtask 10: Implement multi account AWS Console and API  access solution
#### Description
Users can use their directory credentials for single sign-on access to multiple AWS accounts. Users can also single sign-on through the AWS Command Line Interface (CLI), AWS SDKs, or AWS Console Mobile Application using their directory credentials for a consistent authentication experience. For more information, see [AWS IAM Identity Center](https://aws.amazon.com/iam/identity-center/).
#### Tools
AWS IAM Identity Center
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Implemented multi-account for accessing the AWS Management Console and for API access
## Task 2: Subtask 11: Configure BreakGlass IAM User
#### Description
The organization management account is used to provide break-glass access to AWS accounts within the organization. Break glass (which draws its name from breaking the glass to pull a fire alarm) refers to a quick means for a person who does not have access privileges to certain AWS accounts to gain access in exceptional circumstances, using an approved process. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authentication-IAM-Users-Credentials-Management-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Configured a beak-glass AWS IAM user as per the guidelines 
## Task 2: Subtask 12: Create Email DLs for AWS accounts alternative  contacts
#### Description
Add alternative contacts for accounts, so that billing, operations, and security notifications are routed to the responsible teams.
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Created email distribution lists for AWS accounts and alternative contacts
## Task 2: Subtask 13: Prepare AWS accounts for secure and efficient  operations
#### Description
Configure all new accounts with minimum  controls so that accounts are adequately protected.
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
• Set up initial AWS accounts 
a) Configured the root account 
b) Set up a break-glass password 
c) Set up MFA 
d) Set up a password policy 
e) Established alternative contacts 
f) Set up security challenge questions 
g) Created a support plan
## Task 3: Deliver PCE systems
#### Description
System set up activities post system hardening handover and before handover to Functional teams; handover of Development (DEV), Quality Assurance (QA), and Production (PRD) systems from SAP to Customer and Partner project team.

#### Acceptance Criteria
• Completed a workshop to understand the incident-response strategy in AWS 
#### Acceptance Criteria
• Documented Incident Response Discovery and Analysis, which includes 
a) Completed gap analysis 
b) Completed playbooks for common security incidents 
c) Standard operating procedure (SOP) for performing incident response activities in AWS
## Task 3: Subtask 1: Conduct  Incident Response Workshop
#### Description
The AWS cloud has a shared responsibility model. AWS manages security of the cloud. Customers are responsible for security in the cloud. Customers retain control of the security that they choose to implement. Access to hundreds of tools and services to help meet security objectives is available. These capabilities help customers establish a security baseline that meets objectives for applications running in the cloud. When a deviation from baseline does occur, customers might need to respond and investigate. To successfully do so, it is important to understand the basic concepts of security incident response within the AWS environment, as well as the issues needed to consider to prepare, educate, and train cloud teams before security issues occur.
#### Acceptance Criteria
• Completed workshop to a understand the AWS incident response strategy
## Task 3: Subtask 2: Document Incident Response Current and  Readiness State
#### Description
Capture documentation on the current state of incident response capability, including policy, process, tools, and people, to identify gaps that need to be filled in order to achieve a security readiness state in AWS.

#### Acceptance Criteria
• Documented incident response discovery and analysis, which includes the following: 
a) Current state overview 
b) Policy 
c) Process 
d) Tools 
e) People
## Task 3: Subtask 3: Conduct Incident Response Security Readiness  State Gap Analysis and Story Development
#### Description
Conduct Incident Response Security Readiness  State Gap Analysis and Story Development
#### Acceptance Criteria
•  Completed gap analysis
## Task 4: Setup users and assign authorisations
#### Description
Once the systems have been received, the Customer should create the initial users in the System that will participate in the implementation project. The System Administrator will also set up user accounts in the target system and assign user specific authorization profiles that will allow them to access the appropriate system functionality and/or transactions. This activity is essential before the users can be trained and before they can log into the system.

#### Acceptance Criteria
• Defined an administrative access policy for EC2 instances
#### Acceptance Criteria
• Defined a secret-management policy 
#### Acceptance Criteria
• Documented and defined common security groups and NACLs to be used across AWS accounts 
#### Acceptance Criteria
• Completed gap analysis 
#### Acceptance Criteria
• Defined WAF rules management 
#### Acceptance Criteria
• Defined a certificate management policy 
#### Acceptance Criteria
• Defined IDS/IPS strategy 
#### Acceptance Criteria
• Identified a list of AWS VPC security features to be implemented 
## Task 4: Subtask 1: Conduct AWS  Network Security Design Workshop
#### Description
Infrastructure protection is a key part of an information security program. It ensures that systems and services within workloads are protected against unintended and unauthorized access and potential vulnerabilities.  Define trust boundaries (network and account boundaries), system security configuration and maintenance (for example, hardening, minimization, and patching), operating system authentication and authorizations (users, keys, and access levels), and other appropriate policy-enforcement points (web application firewalls and/or API gateways). 
#### Tools
AWS Virtual Private Cloud (VPC)
#### Acceptance Criteria
• Identified a  list of AWS VPC security features to implement
## Task 4: Subtask 2: Document Infrastructure Protection Current and  Readiness State
#### Description
To identify gaps that need to be filled in order to achieve a security readiness state in AWS, capture documentation on the current state of infrastructure protection capability, including policy, process, tools, and people.

#### Acceptance Criteria
• Documented infrastructure protection discovery and analysis, which includes the following: 
a) Current state overview 
b) Policy 
c) Process 
d) Tools 
e) People
## Task 4: Subtask 3: Conduct Infrastructure Protection Security  Readiness State Gap Analysis and Story Development
#### Description
To achieve a security readiness state in AWS, conduct a gap analysis between the current state and the security readiness state of infrastructure protection and develop stories to implement required changes.

#### Acceptance Criteria
•  Completed gap analysis
## Task 4: Subtask 4: Define Security Group and NACL management
#### Description
AWS security groups and NACLs provide the following capabilities and benefits: 1) Security groups act as stateful firewalls and use connection tracking to track information about traffic to and from the instances. 2) Security group rules are always permissive and make it possible to control access based on IP, protocol, and port numbers. 3) Network ACLs are stateless and can either allow or deny traffic. 4) Network ACLs make it possible to control access based on IP, protocol, and port numbers. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Infrastructure-Protection/Security-Groups-and-NACLs-Design.md)
#### Tools
Network ACLs
#### Tools
AWS Security Groups
#### Acceptance Criteria
•  Documented and defined common security groups and NACLs to use across AWS  accounts
## Task 4: Subtask 5: Define IDS and IPS strategy
#### Description
Host-based IDS/IPS protection provides the following general capabilities and benefits: 1) Acts as an additional layer of security for Layer3/Layer4 traffic by scanning and analyzing suspicious content for potential threats. 2) Placed in the direct communication path, an IPS takes automatic action on suspicious traffic within the network. 3) Makes it possible to automatically scale protection with the load. 4) Makes it possible to use additional context available on the host for anomaly detection. 5) Simplifies network design and operations. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Infrastructure-Protection/IDS-and-IPS-Design.md)

#### Acceptance Criteria
•  Defined IDS/IPS strategy
## Task 4: Subtask 6: Define WAF rules management
#### Description
Compute resources in workloads require multiple layers of defense to help protect from external and internal threats. Compute resources include EC2 instances, containers, AWS Lambda functions, database services, IoT devices and more. General recommendations:  
1) Define compute protection requirements 
2) Scan for and patch vulnerabilities 
3) Reduce attack surface 
4) Implement managed services 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Infrastructure-Protection/Compute-Resource-Protection-Design.md)
#### Tools
AWS EC2  
#### Acceptance Criteria
•  Defined an administrative access policy for AWS EC2 instances 
## Task 4: Subtask 7: Build infrastructure security controls
#### Description
Deploy  standard infrastructure protection controls to enforce a consistent layer  3/4/7 protection across AWS accounts.
#### Tools
AWS CloudFormation
#### Tools
AWS Lambda
#### Acceptance Criteria
•  AWS CloudFormation template and AWS Lambda code to deploy standard infrastructure  protection controls
## Task 5: System Design Handover
#### Description
After receiving and reviewing the technical assessment form from the customer, the CAA (Partner CAA for indirect, SAP CAA for direct deals) will then validate and confirm the form with the customer.

#### Tools
Amazon GaurdDuty
#### Tools
Amazon VPC flow logs
#### Tools
AWS Access Analyzer  
#### Tools
AWS CloudWatch Alarms
#### Tools
AWS CloudTrail
#### Tools
AWS Config  Rules
#### Tools
AWS CloudFormation
#### Acceptance Criteria
• Logging best practices  
#### Acceptance Criteria
• Completed gap  analysis  
#### Acceptance Criteria
• Logging and Monitoring Discovery and Analysis
## Task 5: Subtask 1: Sales to Delivery Handover
#### Description
GAD/IAE and CAA to perform the S2D handover to the ECS team (Project Lead). Information in regards of Confirmed Delivery Date, BOM, Scope is provided from Sales to ECS.

#### Tools
Amazon VPC flow logs
#### Tools
AWS CloudTrail
## Task 5: Subtask 2: Validate the Customer Checklist 
#### Description
Before the system build can start, the SAP CAA needs to check and validate the customer checklist/customer landscape information questionnaire. Check if the Customer input on IP Addresses, System IDs, Languages, Installation numbers etc. aligns with the onboarding form.

#### Acceptance Criteria
• Documented logging and monitoring discovery and analysis, which includes the following: 
a) Current state overview 
b) Policy 
c) Process 
d) Tools 
e) People
## Task 5: Subtask 3: Confirm CDD with Customer
#### Description
Project Lead to confirm the CDD date with the customer, as to when the system will be handed over to the customer.

#### Acceptance Criteria
•  Completed gap analysis
## Task 5: Subtask 4: Conduct Delivery and Operations Kick-Off
#### Description
The ECS client delivery manager (CDM) introduces the SAP technical team. After S2D handover takes place. At this point the ECS onboarding sessions kick off.

## Task 5: Subtask 5: Engage Customer to Setup Network Integration (example: VPN)
#### Description
This is to clarify the network route from the Customer site to SAP. Note, for partner led implementations: The partner has to access SAP via the customer, so additional actions may be needed to establish a trusted relationship between customer and partner.

Leverage AWS best practice recommendations for networking and landing zone configuration. 

## Task 5: Subtask 6: Tools Access
#### Description
As part of the Enterprise Cloud Services onboarding, an introduction will be delivered to the customer and partner project teams, sharing the SAP launchpad and the tools that are available to the customer for them to see dashboards of their systems. The dashboards cover items including EWA reports, KPI's and system utilization metrics.
