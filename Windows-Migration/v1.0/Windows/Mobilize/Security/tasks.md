
# Module: Security
## Task 1: Data Protection
#### Description
Establish and implement at-rest and in-transit encryption methodologies for AWS resources to safeguard data in AWS.
#### Tools
AWS Elastic File System
#### Tools
AWS EC2  
#### Tools
AWS Lambda
#### Tools
AWS CloudFormation
#### Tools
AWS Key Management Service
#### Tools
AWS Elastic Block Store
#### Tools
AWS S3  
#### Tools
AWS Virtual Private Cloud (VPC)
#### Tools
AWS RDS
#### Acceptance Criteria
• Defined AWS KMS security policies
#### Acceptance Criteria
• AWS resource encryption strategy for data in transit
#### Acceptance Criteria
• Documented data-protection piscovery and Analysis which includes
#### Acceptance Criteria
• AWS resource encryption strategy for data at rest
#### Acceptance Criteria
• Completed gap analysis
## Task 1: Subtask 1: Conduct  Encryption and Data Protection Workshop
#### Description
AWS provides services that help you protect your data, accounts, and workloads from unauthorized access.  
#### Acceptance Criteria
• Understood customer responsibility for data in AWS 
#### Acceptance Criteria
• Learned how encryption is done in AWS 
#### Acceptance Criteria
• Considered your own encryption requirements 
#### Acceptance Criteria
• Discovered data protection-related AWS services
## Task 1: Subtask 2: Conduct KMS Keys Governance Workshop
#### Description
Understand  AWS encryption and key-management options to meet data protection  requirements.
#### Tools
AWS Key Management Service
#### Acceptance Criteria
•  Defined AWS KMS Security policies
## Task 1: Subtask 3: Document Data Protection Current and Readiness  State
#### Description
Capture documentation on the current state of data protection capability, including policy, process, tools, and teople, to identify gaps that need to be filled in order to achieve a security readiness state in AWS.
#### Acceptance Criteria
• Documented Data Protection Discovery and Analysis. This includes the following: 
a) Current State Overview 
b) Policy 
c) Process 
d) Tools 
e) People
## Task 1: Subtask 4: Conduct Data Protection Security Readiness  State Gap Analysis and Story Development
#### Description
Complete the gap analysis.
#### Acceptance Criteria
•  Completed gap analysis
## Task 1: Subtask 5: Define encryption at rest strategy
#### Description
Encryption at rest means encryption of the data that is stored in the databases and is not moving through networks. Defining data management requirements, implementing secure key management, enforcing access control, and enforcing encryption at rest, all align to well-architected best practices 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Data-Protection/Encryption-At-Rest-Design.md)
#### Tools
AWS RDS
#### Tools
AWS S3  
#### Tools
AWS Elastic Block Store
#### Tools
AWS Elastic File System
#### Acceptance Criteria
•  AWS resource encryption strategy for data at rest
## Task 1: Subtask 6: Define encryption in transit strategy
#### Description
Encryption in transit is when the encrypted data is active and moving between devices and networks like the internet or within a company, or being uploaded to the cloud. It follows well-architected best practices to define data-protection-in-transit requirements, such as encryption standards, based on data classification to meet organizational, legal, and compliance requirements. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Data-Protection/Encryption-In-Transit-Design.md)
#### Tools
AWS Virtual Private Cloud (VPC)
#### Tools
AWS EC2  
#### Acceptance Criteria
•  AWS resource encryption strategy for data in transit
## Task 1: Subtask 7: Determine key management integration
#### Description
AWS KMS integrates with AWS services to encrypt data at rest or to facilitate signing and verification using an AWS KMS key. To protect data at rest, integrated AWS services use envelope encryption, where a data key is used to encrypt data and is itself encrypted under a KMS key stored in AWS KMS. For signing and verification, integrated AWS services use a key pair from an asymmetric KMS key in AWS KMS. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Data-Protection/Encryption-At-Rest-Design.md)
#### Tools
AWS Key Management Service
#### Acceptance Criteria
•  Defined key management infrastructure, including integration with AWS services
## Task 1: Subtask 8: Define key management and governance policy
#### Description
AWS KMS provides the following capabilities and benefits: 

1) Handles the complexity and security of creating and managing cryptographic keys. 
2) Customer-managed keys (CMKs) are protected by hardware security modules (HSMs) that are validated by the FIPS 140-2 Cryptographic Module Validation Program. 
3) Uses FIPS-approved encryption algorithm - AES-GCM with 256 keys. 
4) Uses the encryption context as additional authenticated data (AAD) to support authenticated encryption. 
5) Integrated with many AWS services for server-side encryption. 
6) Integrates with AWS encryption clients and AWS encryption SDK for client-side encryption. 
7) Integrates with AWS CloudTrail and Amazon CloudWatch to provide auditable logs of key usage for regulatory and compliance activities. 
8) Supports direct encryption using CMKs for data under 4KB in size and envelope encryption for larger data sets. 
9) Supports granular access control using IAM policies and CMK resource-based policies with key tagging capability. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Data-Protection/Encryption-At-Rest-Design.md)
#### Tools
AWS Key Management Service
#### Acceptance Criteria
•  Defined key management governance, including integration with AWS services
## Task 1: Subtask 9: Define KMS CMK administrators and users
#### Description
Implement  least privilege model for KMS CMKs so that only authorized consumers have access  to the keys.
#### Tools
AWS Key Management Service
#### Acceptance Criteria
•  Defined AWS KMS CMK administrators and users
## Task 1: Subtask 10: Develop encryption security controls
#### Description
Ensure that any data stored or transmitted inappropriately will be detected, so that workload and data owners get notified and automated corrective actions can be taken.
#### Tools
AWS CloudFormation
#### Tools
AWS Lambda
#### Acceptance Criteria
•  AWS CloudFormation template and AWS Lambda code to deploy standard data protection  controls
## Task 2: Identity and Access Management
#### Description
Securely control  access to AWS services and resources for users to provision and orchestrate  AWS resources.
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
• Documented  Identity and Access Management Discovery and Analysis 
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
• Completed gap analysis  
## Task 2: Subtask 1: Conduct Deep  Dive on Identity and Access Management Workshop
#### Description
With AWS Identity and Access Management (IAM), specify who or what can access services and resources in AWS, centrally manage fine-grained permissions, and analyze access to refine permissions across AWS.
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
• Learned AWS Identity and Access Management (IAM)   
#### Acceptance Criteria
• Decided on roles and policies
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
• Reviewed AWS IAM policy language 
#### Acceptance Criteria
• Decided on roles and policies
#### Acceptance Criteria
• Understood when and where to use AWS IAM 
#### Acceptance Criteria
• Learned AWS Identity and Access Management (IAM) 
#### Acceptance Criteria
• Documented AWS IAM discovery and analysis. This includes the following: 
a) Current state overview 
b) Policy 
c) Process 
d) Tools 
e) People
#### Acceptance Criteria
• Discovered identity federation options 
## Task 2: Subtask 3: Conduct Identity and Access Management Security  Readiness State Gap Analysis and Story Development
#### Description
Conduct a gap analysis between the current and security-readiness states of identity and access management and develop stories to implement required changes, to achieve a security readiness state in AWS.
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Completed gap analysis
## Task 2: Subtask 4: Define AWS root account usage policy
#### Description
The AWS root user is accessed by signing in with the email address and password that were used to create an AWS account. This user is unconstrained by AWS IAM policies. A set of preventative and detective security controls will be deployed to protect AWS root credentials and prevent deviations from the developed IAM credentials management baseline, which follows well-architected best practices. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authentication-Root-Credentials-Management-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Defined AWS root account and its usage policy
## Task 2: Subtask 5: Define permanent credentials usage policy
#### Description
Define the permanent credentials usage policy for AWS IAM users. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Human-IAM-Roles-and-Policies-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Defined AWS permanent credentials accounts and its usage policy so that  credentials need not be changed frequently
## Task 2: Subtask 6: Define multi account user authentication policy
#### Description
Define the multi-account user authentication policy for AWS IAM users. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Human-IAM-Roles-and-Policies-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Defined AWS multi-account users and usage policy 
## Task 2: Subtask 7: Define base IAM roles and IAM policies naming  standard and definition
#### Description
Define the naming conventions for AWS IAM roles and policies. It is important to have a standard naming style across all AWS resources. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/IAM-Resources-Naming-Convention.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Followed the naming conventions for AWS IAM roles and policies as defined in the guidelines
## Task 2: Subtask 8: Define base preventative controls SCPs
#### Description
Define base security control policies (SCPs).  For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Service-Control-Policies-(SCPs)-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Well-defined base security control policies (SCPs)
## Task 2: Subtask 9: Build base preventative controls SCPs
#### Description
Define base security control policies (SCPs).  For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Service-Control-Policies-(SCPs)-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Built base security control policies (SCPs)
## Task 2: Subtask 10: Build base IAM identities such as IAM roles and  IAM policies
#### Description
Manage access in AWS by creating policies and attaching them to AWS IAM identities (users, groups of users, or roles) or AWS resources. A policy is an object in AWS that, when associated with an identity or resource, defines their permissions For more information, see [Access Policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html.)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Defined and built AWS IAM roles and policies
## Task 2: Subtask 11: Implement multi account AWS Console and API  access solution
#### Description
Users can use their directory credentials for single sign-on access to multiple AWS accounts. Users can also single sign-on through the AWS Command Line Interface (CLI), AWS SDKs, or AWS Console Mobile Application using their directory credentials for a consistent authentication experience. For more information, see [AWS IAM Identity Center](https://aws.amazon.com/iam/identity-center/).
#### Tools
AWS IAM Identity Center
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Implemented multi-account for accessing the AWS Management Console and for API access
## Task 2: Subtask 12: Enforce MFA for AWS Console and  CLI usage during federation
#### Description
AWS IAM has roles for human users and workloads that access AWS resources so that they use temporary credentials. However, for scenarios in which AWS IAM or root users are needed, we recommend AWS Multi-Factor Authentication (MFA) for additional security. With MFA, users have a device that generates a response to an authentication challenge. Each user's credentials and device-generated response are required to complete the sign-in process. For more information, see [here](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html.)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Multi-factor authentication enabled for using the AWS Management Console and the CLI
## Task 2: Subtask 13: Configure BreakGlass IAM User
#### Description
The organization management account is used to provide break-glass access to AWS accounts within the organization. Break glass (which draws its name from breaking the glass to pull a fire alarm) refers to a quick means for a person who does not have access privileges to certain AWS accounts to gain access in exceptional circumstances, using an approved process. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authentication-IAM-Users-Credentials-Management-Design.md)
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Configured a beak-glass AWS IAM user as per the guidelines 
## Task 2: Subtask 14: Define periodic resource management cleanup  policy
#### Description
AWS IAM provides last-accessed information to help identify unused permissions and to remove them. Use last-accessed information to refine policies and allow access to only the services and actions that are used by entities. For more information, see [here.](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_access-advisor.html).
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Defined a resource management cleanup policy
## Task 2: Subtask 15: Create Email DLs for AWS accounts alternative  contacts
#### Description
Add alternative contacts for accounts, so that billing, operations, and security notifications are routed to the responsible teams.
#### Tools
AWS Identity and Access Management (IAM)
#### Acceptance Criteria
•  Created email distribution lists for AWS accounts and alternative contacts
## Task 2: Subtask 16: Prepare AWS accounts for secure and efficient  operations
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
## Task 3: Incident Response
#### Description
Develop and implement an incident response plan and methodology to quickly detect, respond to and, recover from a security incident.
#### Tools
AWS EC2  
#### Acceptance Criteria
• Documented Incident Response Discovery and Analysis, which includes 
a) Completed gap analysis 
b) Completed playbooks for common security incidents 
c) Standard operating procedure (SOP) for performing incident response activities in AWS
#### Acceptance Criteria
• Completed a workshop to understand the incident-response strategy in AWS 
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
## Task 3: Subtask 4: Define IR framework and playbooks
#### Description
The Incident Response (IR) process includes the following four stages: 1) Preparation 2) Detection and analysis 3) Containment, eradication, and recovery 4) Post-incident activity These stages outline the steps necessary to ensure the effective response and handling of security incidents that affect the availability, integrity, or confidentiality of customer information assets. Playbooks can be developed as per the mentioned stages to prepare for future incidents. 

Common playbooks include the following: 1) Account credential compromise 2) DDoS 3) Amazon EC2 instance compromise 

For more information, see the following resources. [Incident-Response-Framework](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Incident-Response/Incident-Response-Framework.md), [Incident-Response-Playbook-Account-Credentials-Compromise](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Incident-Response/Incident-Response-Playbook-Account-Credentials-Compromise.md), [Incident-Response-Playbook-DDoS](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Incident-Response/Incident-Response-Playbook-DDoS.md), [Incident-Response-Playbook-Instance-Compromise](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Incident-Response/Incident-Response-Playbook-Instance-Compromise.md)

#### Tools
AWS EC2  
#### Acceptance Criteria
•  Completed playbooks for common security incidents
## Task 3: Subtask 5: Develop a standard operating procedure for IR  activities
#### Description
Standard technical and business controls need to be established to support an effective incident response and security operations in the AWS cloud. Incident response best practices include the following:  1) Defining an investigation process 2) Identifying key personnel and external resources 3) Tooling  4) Forensics capabilities 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Incident-Response/Incident-Response-Preparation.md)
#### Acceptance Criteria
• A standard operating procedure (SOP) for performing incident response activities in AWS
## Task 4: Infrastructure Protection
#### Description
Implement secure and  compliant infrastructure to have a reliable and trustable infrastructure for  business workloads to run on.
#### Tools
AWS SSM Parameter Store 
#### Tools
AWS Lambda
#### Tools
Network ACLs
#### Tools
AWS WAF
#### Tools
AWS EC2  
#### Tools
AWS Virtual Private Cloud (VPC)
#### Tools
AWS Security Groups
#### Tools
AWS Secrets Manager
#### Tools
AWS CloudFormation
#### Acceptance Criteria
• Defined a certificate management policy 
#### Acceptance Criteria
• Defined a secret-management policy 
#### Acceptance Criteria
• Identified a list of AWS VPC security features to be implemented 
#### Acceptance Criteria
• Completed gap analysis 
#### Acceptance Criteria
• Defined IDS/IPS strategy 
#### Acceptance Criteria
• Documented and defined common security groups and NACLs to be used across AWS accounts 
#### Acceptance Criteria
• Defined WAF rules management 
#### Acceptance Criteria
• Defined an administrative access policy for EC2 instances
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
AWS Security Groups
#### Tools
Network ACLs
#### Acceptance Criteria
•  Documented and defined common security groups and NACLs to use across AWS  accounts
## Task 4: Subtask 5: Define IDS and IPS strategy
#### Description
Host-based IDS/IPS protection provides the following general capabilities and benefits: 1) Acts as an additional layer of security for Layer3/Layer4 traffic by scanning and analyzing suspicious content for potential threats. 2) Placed in the direct communication path, an IPS takes automatic action on suspicious traffic within the network. 3) Makes it possible to automatically scale protection with the load. 4) Makes it possible to use additional context available on the host for anomaly detection. 5) Simplifies network design and operations. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Infrastructure-Protection/IDS-and-IPS-Design.md)

#### Acceptance Criteria
•  Defined IDS/IPS strategy
## Task 4: Subtask 6: Define Certificate Management Policy
#### Description
AWS Secrets Manager and AWS Systems Manager Parameter Store improve the security posture by removing hard-coded credentials from application source code, by not storing credentials on the instances, and by replacing them with a runtime call to the service, so that the credentials are retrieved dynamically when needed. Dynamic retrieval of the credentials also simplifies their rotation. 

AWS Secrets Manager provides the following capabilities and benefits: 
1) Provides scalable, hosted secrets management service with no servers to manage. 
2) Stores key-value pairs with versioning enabled. 
3) Stores values with up to 10KB in size. 
4) Enforces encryption of all values at rest with KMS and in transit with TLS. 
5) Enforces recovery window for secrets deletion. 
6) Provides native support for automatic passwords rotation for Amazon RDS, Amazon DocumentDB, and Amazon Redshift databases. 
7) Supports granular access control using IAM policies and Secrets resource-based policies with secrets tagging capability. 

AWS SSM Parameter Store provides the following capabilities and benefits: 
1) Provides scalable, hosted secrets management service with no servers to manage. 
2) Stores configuration data and secure strings in hierarchies with versioning enabled. 
3) Stores values with up to 8 kB in size (advanced tier). 
4) Protects secure strings with KMS encryption and enforces TLS for all transfers. 
5) Supports granular access control using IAM policies with parameters pathing and tagging capability. 
6) Supports parameters expiration and notification polices (advanced tier). 
7) Allows to reference AWS Secrets Manager secrets by using Parameter Store parameters. 
8) Supports integration with other Systems Manager capabilities and AWS services to retrieve secrets and configuration data from a central store. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Infrastructure-Protection/Secrets-Management-Design.md)

#### Tools
AWS SSM Parameter Store 
#### Tools
AWS Secrets Manager
#### Acceptance Criteria
•  Defined a certificate management policy
## Task 4: Subtask 7: Define Secrets Management Policy
#### Description
AWS Secrets Manager and AWS Secrets Manager Parameter Store improve the security posture by removing hard-coded credentials from applications’ source code, by not storing credentials on the instances, and by replacing them with a runtime call to the service, so that the credentials are retrieved dynamically when needed. Dynamic retrieval of the credentials also simplify their rotation. 

AWS Secrets Manager provides the following capabilities and benefits: 
1) Provides scalable, hosted secrets management service with no servers to manage. 
2) Stores key-value pairs with versioning enabled. 
3) Stores values with up to 10 kB in size. 
4) Enforces encryption of all values at rest with KMS and in transit with TLS. 
5) Enforces recovery window for secrets deletion. 
6) Provides native support for automatic passwords rotation for Amazon RDS, Amazon DocumentDB, and Amazon Redshift databases. 
7) Supports granular access control using AWS IAM policies and Secrets resource-based policies with secrets tagging capability. 

AWS SSM Parameter Store provides the following capabilities and benefits: 
1) Provides scalable, hosted secrets management service with no servers to manage.
2) Stores configuration data and secure strings in hierarchies with versioning enabled. 
3) Stores values with up to 8 kB in size (advanced tier). 
4) Protects secure strings with KMS encryption and enforces TLS for all transfers. 
5) Supports granular access control using AWS IAM policies with parameters pathing and tagging capability. 
6) Supports parameters expiration and notification polices (advanced tier). 
7) Allows to reference AWS Secrets Manager secrets by using Parameter Store parameters. 
8) Supports integration with other Systems Manager capabilities and AWS services to retrieve secrets and configuration data from a central store. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Infrastructure-Protection/Secrets-Management-Design.md)
#### Tools
AWS SSM Parameter Store 
#### Tools
AWS Secrets Manager
#### Acceptance Criteria
•  Defined Secret Management Policy
## Task 4: Subtask 8: Define WAF rules management
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
## Task 4: Subtask 9: Build infrastructure security controls
#### Description
Deploy  standard infrastructure protection controls to enforce a consistent layer  3/4/7 protection across AWS accounts.
#### Tools
AWS Lambda
#### Tools
AWS CloudFormation
#### Acceptance Criteria
•  AWS CloudFormation template and AWS Lambda code to deploy standard infrastructure  protection controls
## Task 5: Logging and Monitoring
#### Description
Implement logging and  monitoring framework to monitor the interactions within AWS resources.
#### Tools
Amazon VPC flow logs
#### Tools
AWS CloudTrail
#### Tools
AWS CloudFormation
#### Tools
Amazon GaurdDuty
#### Tools
AWS Config  Rules
#### Tools
AWS CloudWatch Alarms
#### Tools
AWS Access Analyzer  
#### Acceptance Criteria
• Completed gap  analysis  
#### Acceptance Criteria
• Logging best practices  
#### Acceptance Criteria
• Logging and Monitoring Discovery and Analysis
## Task 5: Subtask 1: Conduct Logging  and Alerting Design Workshop
#### Description
Logging and monitoring are very important parts of maintaining the reliability, availability, and performance of AWS solutions. AWS provides several tools for monitoring AWS resources.
#### Tools
AWS CloudTrail
#### Tools
Amazon VPC flow logs
#### Acceptance Criteria
• Learned ways to extract value from multiple data sources
#### Acceptance Criteria
• Understood what logs are available
#### Acceptance Criteria
• Logging best practices 
#### Acceptance Criteria
• Discovered new services to enhance security awareness
## Task 5: Subtask 2: Document Logging and Monitoring Current and  Readiness State
#### Description
To identify gaps that need to be filled in order to achieve a security readiness state in AWS, capture documentation on the current state of logging and monitoring capabilities, including policy, process, tools, and people.
#### Acceptance Criteria
• Documented logging and monitoring discovery and analysis, which includes the following: 
a) Current state overview 
b) Policy 
c) Process 
d) Tools 
e) People
## Task 5: Subtask 3: Conduct Logging and Monitoring Security  Readiness State Gap Analysis and Story Development
#### Description
To achieve a security readiness state in AWS, conduct a gap analysis between the current state and the security readiness state of logging and monitoring, and develop stories to implement the required changes.

#### Acceptance Criteria
•  Completed gap analysis
## Task 5: Subtask 4: Establish logging pattern and strategy
#### Description
AWS provides several tools for logging. Establish logging patterns and strategy based on the needs and requirements of the migrating environment. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Logging-and-Monitoring/Logging-Log-Storage-and-Retention-Design.md)

#### Tools
AWS CloudTrail
#### Tools
Amazon VPC flow logs
#### Acceptance Criteria
•  Documented details of logging pattern
## Task 5: Subtask 5: Define required service logs for ingestion
#### Description
There are three log categories: 
1) AWS infrastructure logs 
2) AWS service logs 
3) Host-based logs. 

Each of these types of logs can be obtained using AWS tools like AWS CloudTrail or Amazon VPC Flow logs.  For more information, see the following resources, GitHub: [Logging-Logs-Processing-Design](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Logging-and-Monitoring/Logging-Logs-Processing-Design.md), [Security Logging and Monitoring](https://docs.aws.amazon.com/IAM/latest/UserGuide/security-logging-and-monitoring.html)
#### Tools
AWS CloudTrail
#### Tools
Amazon VPC flow logs
#### Acceptance Criteria
• Documented security-related information 
#### Acceptance Criteria
• Service logs collected from various logging tools in AWS 
## Task 5: Subtask 6: Establish long-term retention logging strategy
#### Description
Logs must be retained for analysis. To retain logs use efficient tools like Amazon S3 and AWS CloudWatch log groups.  For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Logging-and-Monitoring/Logging-Log-Storage-and-Retention-Design.md)
#### Tools
AWS CloudTrail
#### Tools
Amazon VPC flow logs
#### Acceptance Criteria
•  Documented a log-retention strategy
## Task 5: Subtask 7: Define required monitoring services to enable
#### Description
Define AWS monitoring and security services and features that will be enabled in each AWS account and that will consolidate findings in the centralized audit account. You can use AWS monitoring features like AWS Config rules and AWS CloudWatch alarms. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Logging-and-Monitoring/Monitoring-Security-Monitoring-Design.md)
#### Tools
AWS Config  Rules
#### Tools
AWS CloudWatch Alarms
#### Acceptance Criteria
•  Defined AWS monitoring and security services and features
## Task 5: Subtask 8: Define a base set of  detective controls to enable
#### Description
Define a base set of detective controls. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Logging-and-Monitoring/Monitoring-Detective-Controls-Design.md)
#### Tools
AWS Config  Rules
#### Tools
AWS CloudWatch Alarms
#### Acceptance Criteria
•  Listed detective controls to be enabled in AWS accounts  
a) root console logins and API calls  
b) access keys  
c) unused privileges to enforce least privilege
## Task 5: Subtask 9: Build a base set of detective controls to  enable
#### Description
Define a base set of detective controls. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Logging-and-Monitoring/Monitoring-Detective-Controls-Design.md)
#### Tools
AWS Config  Rules
#### Tools
AWS CloudWatch Alarms
#### Acceptance Criteria
•  List detective controls to be enabled in AWS accounts  
a) root console logins and API calls  
b) access keys  
c) unused privileges to enforce least privilege
## Task 5: Subtask 10: Build required monitoring services
#### Description
To capture logs, select the monitoring services that AWS provides and configure them. You can use AWS monitoring features like AWS Config rules, AWS Cloud Watch alarms, AWS Access Analyzer, and AWS Guard Duty for this purpose. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Logging-and-Monitoring/Monitoring-Security-Monitoring-Design.md)
#### Tools
Amazon GaurdDuty
#### Tools
AWS Access Analyzer  
#### Tools
AWS CloudWatch Alarms
#### Tools
AWS Config  Rules
#### Tools
AWS CloudFormation
#### Tools
AWS Lambda
#### Acceptance Criteria
• An AWS CloudFormation template and AWS Lambda code to enable security services