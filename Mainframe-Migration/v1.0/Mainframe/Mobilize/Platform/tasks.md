
# Module: Platform
## Task 1: Security compliance and resiliency
#### Description
The security perspective goal is to help customers structure the selection and implementation of controls that are right for the organization. As an AWS customer, you benefit from a data center and network architecture that is built to meet the requirements of the most security-sensitive organizations.
#### Tools
AWS Mainframe Modernization
#### Acceptance Criteria
â€¢ Security, compliance, and resiliency strategies
## Task 1: Subtask 1: Understand the shared responsibility model
#### Description
Security is a shared responsibility between AWS and you. The [shared responsibility model](http://aws.amazon.com/compliance/shared-responsibility-model/) describes this as security of the cloud and security in the cloud:  

• Security of the cloud – AWS is responsible for protecting the infrastructure that runs AWS services in the AWS Cloud. AWS also provides you with services that you can use securely.   
• Security in the cloud – Your responsibility is determined by the AWS service that you use. You are also responsible for other factors including the sensitivity of your data, your company’s requirements, and applicable laws and regulations   



 
#### Tools
AWS Mainframe Modernization
#### Acceptance Criteria
â€¢ Knowledge of the shared responsibility model in AWS for mainframe migrations.
## Task 1: Subtask 2: Create a data protection strategy
#### Description
To safeguard data in AWS, establish and implement a methodology for encryption at rest and in transit for AWS resources. Use the following steps and create subtasks if needed.

1) Document the current and readiness states of data protection.
2) Conduct a data protection readiness gap analysis and story development.
3) Define an encryption-at-rest strategy.
4) Define encryption-in-transit strategy.
5) Develop encryption security controls.



#### Tools
AWS CloudFormation
#### Tools
AWS Key Management Service
#### Tools
AWS Security Hub
#### Tools
Amazon Macie
#### Tools
Amazon GaurdDuty
#### Acceptance Criteria
â€¢ An AWS resource encryption strategy for data at rest.
#### Acceptance Criteria
â€¢ An AWS resource encryption strategy for data in transit.
#### Acceptance Criteria
â€¢ Completed a data protection gap analysis.
#### Acceptance Criteria
â€¢ Identified a data protection strategy.
## Task 1: Subtask 3: Create an IAM strategy
#### Description
AWS Identity and Access Management (IAM) is a service that helps an administrator securely control access to AWS resources. IAM administrators control who can be authenticated and authorized. Securely control access to AWS services and resources for users to provision and orchestrate AWS resources.

Perform the following steps and create subtasks if necessary.

1) Document the identity-and-access-management current and readiness states.
2) Conduct an identity-and-access-management security readiness state gap analysis.
3) Define IAM roles and policies.
4) Define IAM break-glass policies. 



#### Tools
AWS Identity and Access Management (IAM)
#### Tools
AWS Mainframe Modernization
#### Acceptance Criteria
â€¢ An identity-and-access-management readiness report.
#### Acceptance Criteria
â€¢ Completed an identity-and-access-management gap analysis.
#### Acceptance Criteria
â€¢ Completed an identity-and-access-management strategy.
## Task 1: Subtask 4: Create an infrastructure protection strategy
#### Description
To have a reliable and trustable infrastructure for business workloads to run on, create a strategy for a secure and compliant infrastructure.

Perform the following steps and create subtasks if necessary.

1) Perform an infrastructure protection security readiness state gap analysis.
2) Define an infrastructure protection strategy
3) Define a certificate and secrets management policy
4) Build infrastructure security controls



#### Tools
AWS Mainframe Modernization
#### Tools
AWS IAM security groups
#### Acceptance Criteria
â€¢ An infrastructure protection readiness report.
#### Acceptance Criteria
â€¢ Completed infrastructure protection gap analysis.
#### Acceptance Criteria
â€¢ Completed infrastructure protection strategy.
## Task 1: Subtask 5: Create a compliance strategy
#### Description
When you perform a mainframe migration to AWS, the responsibility for compliance is determined by the sensitivity of the data, the company's compliance objectives, and applicable laws and regulations. AWS provides the following resources to help with compliance:  

•	Security and Compliance Quick Start Guides - These deployment guides discuss architectural considerations and provide steps for deploying security- and compliance-focused baseline environments on AWS.  
•	Architecting for HIPAA Security and Compliance Whitepaper  – This whitepaper describes how companies can use AWS to create HIPAA-compliant applications.   
•	AWS Compliance Resources – This collection of workbooks and guides might apply to your industry and location.  
•	Evaluating Resources with Rules - assesses how well your resource configurations comply with internal practices, industry guidelines, and regulations.  
•	AWS Security Hub – This AWS service provides a comprehensive view of your security state within AWS that helps you check your compliance with security industry standards and best practices.  



#### Tools
AWS Security Hub
#### Acceptance Criteria
â€¢ Defined compliance strategy.
## Task 1: Subtask 6: Create a resilience strategy
#### Description
The AWS global infrastructure is built around AWS Regions and Availability Zones. Regions provide multiple physically separated and isolated Availability Zones, which are connected through low-latency, high-throughput, and highly redundant networking. With Availability Zones, you can design and operate applications and databases that automatically fail over between zones without interruption. Availability Zones are more highly available, fault tolerant, and scalable than traditional single or multiple data center infrastructures.
#### Tools
AWS Global Infrastructure
#### Acceptance Criteria
â€¢ Defined a resilience strategy for mainframe migration to AWS.
## Task 2: Landing Zone
#### Description
This task provides guidance on how to deploy, extend and customize the publicly available AWS Landing Zone solution. AWS Landing Zone accelerates customer adoption of the cloud by providing a prescriptive set of instructions for deploying an AWS-recommended foundation of interrelated AWS accounts, networks, and core services. AWS Landing Zone provides prescriptive guidance and best practice templates that a customer can deploy into their initial AWS environment, with confidence that it will grow to meet future business needs including security and regulatory compliance requirements.
#### Tools
AWS Landing Zone
#### Tools
AWS Control Tower
#### Tools
AWS CloudWatch
#### Tools
AWS CloudTrail
#### Acceptance Criteria
â€¢ Completed Landing Zone for Mainframe migration
## Task 2: Subtask 1: Kick Off
#### Description
Get a clear understanding of the Landing Zone Workstream delivery workflow by reviewing and refining the workstream backlog. 



#### Tools
AWS Control Tower
#### Acceptance Criteria
â€¢ Tasks that must be completed to achieve the outcomes have been identified and agreed upon.
## Task 2: Subtask 2: Design Workshops
#### Description
Define scope, objectives, and expected outcomes for the workstream. Expected outcomes for the workstream includes (create subtasks if needed): 

1) Basic Training – initial knowledge on AWS Landing Zone and AWS Control Tower
2) Overview and Design - Core Account Configuration
3) Design - VPC \ CIDR \ AZ - Provisioning up a Landing Zone requires designing multiple AWS services
4) Design - Security Groups \ NACL - For each security group, add rules that control the traffic based on protocols and port numbers. There are separate sets of rules for inbound traffic and outbound traffic.
5) Design - WAN \ VPC Connectivity - VPC and WAN connectivity is critical while setting up landing zone.
6) Design – DNS
#### Tools
AWS Landing Zone
#### Tools
AWS Control Tower
#### Tools
AWS Virtual Private Cloud (VPC)
#### Acceptance Criteria
â€¢ Complete knowledge on AWS Landing Zone and AWS Control Tower
#### Acceptance Criteria
â€¢ Provisioned core components in AWS Landing Zone and AWS Control Tower
## Task 2: Subtask 3: Implement Landing Zone
#### Description
Once all the pre-requisite and parameters are met, set up the landing zone in the desired AWS region. More information is available [here](https://docs.aws.amazon.com/controltower/latest/userguide/review-and-set-up.html)
#### Tools
AWS Landing Zone
#### Tools
AWS Control Tower
#### Acceptance Criteria
â€¢ Created an AWS landing zone for the migration.