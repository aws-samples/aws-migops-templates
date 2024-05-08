
# Module: Security
## Task 1: Data Protection, IAM, Infrastructure protection, monitoring & logging, workload specific security
#### Description
Establish and implement security safeguards, controls and protection for AWS resources is of paramount importance. 
## Task 1: Subtask 1: Review your AWS environment security
#### Description
Leverage the security pillar in AWS Well-Architected framework if you are defining AWS accounts for the first time to ensure that you are setup with the appropriate security controls across data protection, IAM, infrastructure protection, monitoring & logging among others. 

For customers leveraging existing accounts, it is still recommended to review AWS WAF security controls.

https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html

For migrations, there are specific controls recommended by AWS. More details can be found here. 

https://docs.aws.amazon.com/wellarchitected/latest/migration-lens/security.html
## Task 2: Data Protection
#### Description
Establish and implement at-rest and in-transit encryption methodologies for AWS resources to safeguard data in AWS.
## Task 2: Subtask 1: Conduct Encryption, Data Protection and KMS Keys Governance Workshop
#### Description
AWS provides services that help you protect your data, accounts, and workloads from unauthorized access. Understand AWS encryption and key-management options to meet data protection requirements.
## Task 2: Subtask 2: Document Data Protection Current and Readiness State
#### Description
Capture documentation on the current state of data protection capability, including policy, process, tools, and teople, to identify gaps that need to be filled in order to achieve a security readiness state in AWS.
## Task 2: Subtask 3: Conduct Data Protection Security Readiness State Gap Analysis and Story Development
#### Description
Complete the gap analysis.
## Task 2: Subtask 4: Define encryption at rest and transit strategy
#### Description
Encryption at rest means encryption of the data that is stored in the databases and is not moving through networks. Defining data management requirements, implementing secure key management, enforcing access control, and enforcing encryption at rest, all align to well-architected best practices 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Data-Protection/Encryption-At-Rest-Design.md). Encryption in transit is when the encrypted data is active and moving between devices and networks like the internet or within a company, or being uploaded to the cloud. It follows well-architected best practices to define data-protection-in-transit requirements, such as encryption standards, based on data classification to meet organizational, legal, and compliance requirements. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Data-Protection/Encryption-In-Transit-Design.md)
## Task 2: Subtask 5: Define KMS CMK administrators and users
#### Description
Implement least privilege model for KMS CMKs so that only authorized consumers have access to the keys.
## Task 3: Identity and Access Management
#### Description
Securely control access to AWS services and resources for users to provision and orchestrate AWS resources.
## Task 3: Subtask 1: Conduct Deep Dive on Identity and Access Management Workshop
#### Description
With AWS Identity and Access Management (IAM), specify who or what can access services and resources in AWS, centrally manage fine-grained permissions, and analyze access to refine permissions across AWS.
## Task 3: Subtask 2: Document Identity and Access Management Current and Readiness State
#### Description
Capture documentation on the current state of identity-and-access-management capability, including policy, process, tools, and people. Identify gaps that need to be filled to achieve a security readiness state in AWS.
## Task 3: Subtask 3: Define AWS root account usage policy - MSR.IAM.2
#### Description
The AWS root user is accessed by signing in with the email address and password that were used to create an AWS account. This user is unconstrained by AWS IAM policies. A set of preventative and detective security controls will be deployed to protect AWS root credentials and prevent deviations from the developed IAM credentials management baseline, which follows well-architected best practices. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authentication-Root-Credentials-Management-Design.md)
## Task 3: Subtask 4: Define permanent credentials usage policy
#### Description
Define the permanent credentials usage policy for AWS IAM users. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Human-IAM-Roles-and-Policies-Design.md)
## Task 3: Subtask 5: Define multi account user authentication policy
#### Description
Define the multi-account user authentication policy for AWS IAM users. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Human-IAM-Roles-and-Policies-Design.md)
## Task 3: Subtask 6: Define base IAM roles and IAM policies naming standard and definition
#### Description
Define the naming conventions for AWS IAM roles and policies. It is important to have a standard naming style across all AWS resources. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/IAM-Resources-Naming-Convention.md)
## Task 3: Subtask 7: Define base preventative controls SCPs
#### Description
Define base security control policies (SCPs). For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Service-Control-Policies-(SCPs)-Design.md)
## Task 3: Subtask 8: Build base preventative controls SCPs
#### Description
Define base security control policies (SCPs). For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authorization-Service-Control-Policies-(SCPs)-Design.md)
## Task 3: Subtask 9: Build base IAM identities such as IAM roles and IAM policies
#### Description
Manage access in AWS by creating policies and attaching them to AWS IAM identities (users, groups of users, or roles) or AWS resources. A policy is an object in AWS that, when associated with an identity or resource, defines their permissions For more information, see [Access Policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html.)
## Task 3: Subtask 10: Implement multi account AWS Console and API access solution
#### Description
Users can use their directory credentials for single sign-on access to multiple AWS accounts. Users can also single sign-on through the AWS Command Line Interface (CLI), AWS SDKs, or AWS Console Mobile Application using their directory credentials for a consistent authentication experience. For more information, see [AWS IAM Identity Center](https://aws.amazon.com/iam/identity-center/).
## Task 3: Subtask 11: Enforce MFA for AWS Console and CLI usage during federation - MSR.IAM.4
#### Description
AWS IAM has roles for human users and workloads that access AWS resources so that they use temporary credentials. However, for scenarios in which AWS IAM or root users are needed, we recommend AWS Multi-Factor Authentication (MFA) for additional security. With MFA, users have a device that generates a response to an authentication challenge. Each user's credentials and device-generated response are required to complete the sign-in process. For more information, see [here](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa.html.)
## Task 3: Subtask 12: Configure BreakGlass IAM User
#### Description
The organization management account is used to provide break-glass access to AWS accounts within the organization. Break glass (which draws its name from breaking the glass to pull a fire alarm) refers to a quick means for a person who does not have access privileges to certain AWS accounts to gain access in exceptional circumstances, using an approved process. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Identity-and-Access-Management/Authentication-IAM-Users-Credentials-Management-Design.md)
## Task 3: Subtask 13: Create Email DLs for AWS accounts alternative contacts
#### Description
Add alternative contacts for accounts, so that billing, operations, and security notifications are routed to the responsible teams.
## Task 3: Subtask 14: Prepare AWS accounts for secure and efficient operations
#### Description
Configure all new accounts with minimum controls so that accounts are adequately protected.
## Task 4: Incident Response
#### Description
Develop and implement an incident response plan and methodology to quickly detect, respond to and, recover from a security incident.
## Task 4: Subtask 1: Document Incident Response Current and Readiness State
#### Description
Capture documentation on the current state of incident response capability, including policy, process, tools, and people, to identify gaps that need to be filled in order to achieve a security readiness state in AWS.

## Task 4: Subtask 2: Define IR framework and playbooks - MSR.IR.3
#### Description
The Incident Response (IR) process includes the following four stages: 1) Preparation 2) Detection and analysis 3) Containment, eradication, and recovery 4) Post-incident activity These stages outline the steps necessary to ensure the effective response and handling of security incidents that affect the availability, integrity, or confidentiality of customer information assets. Playbooks can be developed as per the mentioned stages to prepare for future incidents. 

Common playbooks include the following: 1) Account credential compromise 2) DDoS 3) Amazon EC2 instance compromise 

For more information, see the following resources. [Incident-Response-Framework](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Incident-Response/Incident-Response-Framework.md), [Incident-Response-Playbook-Account-Credentials-Compromise](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Incident-Response/Incident-Response-Playbook-Account-Credentials-Compromise.md), [Incident-Response-Playbook-DDoS](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Incident-Response/Incident-Response-Playbook-DDoS.md), [Incident-Response-Playbook-Instance-Compromise](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Incident-Response/Incident-Response-Playbook-Instance-Compromise.md)

## Task 4: Subtask 3: Develop a standard operating procedure for IR activities - MSR.IR.10
#### Description
Standard technical and business controls need to be established to support an effective incident response and security operations in the AWS cloud. Incident response best practices include the following: 1) Defining an investigation process 2) Identifying key personnel and external resources 3) Tooling 4) Forensics capabilities

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Incident-Response/Incident-Response-Preparation.md)
## Task 5: Infrastructure Protection
#### Description
Implement secure and compliant infrastructure to have a reliable and trustable infrastructure for business workloads to run on.
## Task 5: Subtask 1: Conduct AWS Network Security Design Workshop
#### Description
Infrastructure protection is a key part of an information security program. It ensures that systems and services within workloads are protected against unintended and unauthorized access and potential vulnerabilities. Define trust boundaries (network and account boundaries), system security configuration and maintenance (for example, hardening, minimization, and patching), operating system authentication and authorizations (users, keys, and access levels), and other appropriate policy-enforcement points (web application firewalls and/or API gateways). 
## Task 5: Subtask 2: Document Infrastructure Protection Current and Readiness State
#### Description
To identify gaps that need to be filled in order to achieve a security readiness state in AWS, capture documentation on the current state of infrastructure protection capability, including policy, process, tools, and people.

## Task 5: Subtask 3: Conduct Infrastructure Protection Security Readiness State Gap Analysis and Story Development
#### Description
To achieve a security readiness state in AWS, conduct a gap analysis between the current state and the security readiness state of infrastructure protection and develop stories to implement required changes.

## Task 5: Subtask 4: Define Security Group and NACL management
#### Description
AWS security groups and NACLs provide the following capabilities and benefits: 1) Security groups act as stateful firewalls and use connection tracking to track information about traffic to and from the instances. 2) Security group rules are always permissive and make it possible to control access based on IP, protocol, and port numbers. 3) Network ACLs are stateless and can either allow or deny traffic. 4) Network ACLs make it possible to control access based on IP, protocol, and port numbers. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Infrastructure-Protection/Security-Groups-and-NACLs-Design.md)
## Task 5: Subtask 5: Define IDS and IPS strategy
#### Description
Host-based IDS/IPS protection provides the following general capabilities and benefits: 1) Acts as an additional layer of security for Layer3/Layer4 traffic by scanning and analyzing suspicious content for potential threats. 2) Placed in the direct communication path, an IPS takes automatic action on suspicious traffic within the network. 3) Makes it possible to automatically scale protection with the load. 4) Makes it possible to use additional context available on the host for anomaly detection. 5) Simplifies network design and operations. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Infrastructure-Protection/IDS-and-IPS-Design.md)

## Task 5: Subtask 6: Define Certificate Management and Secrets Management Policy - MSR.IP.9
#### Description
AWS Secrets Manager and AWS Secrets Manager Parameter Store improve the security posture by removing hard-coded credentials from applicationsí source code, by not storing credentials on the instances, and by replacing them with a runtime call to the service, so that the credentials are retrieved dynamically when needed. Dynamic retrieval of the credentials also simplify their rotation. 

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
## Task 5: Subtask 7: Define WAF rules management
#### Description
Compute resources in workloads require multiple layers of defense to help protect from external and internal threats. Compute resources include EC2 instances, containers, AWS Lambda functions, database services, IoT devices and more. General recommendations: 
1) Define compute protection requirements 
2) Scan for and patch vulnerabilities 
3) Reduce attack surface 
4) Implement managed services 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Infrastructure-Protection/Compute-Resource-Protection-Design.md)
## Task 5: Subtask 8: Build infrastructure security controls
#### Description
Deploy standard infrastructure protection controls to enforce a consistent layer 3/4/7 protection across AWS accounts.
## Task 6: Logging and Monitoring
#### Description
Implement logging and monitoring framework to monitor the interactions within AWS resources.
## Task 6: Subtask 1: Conduct Logging and Alerting Design Workshop
#### Description
Logging and monitoring are very important parts of maintaining the reliability, availability, and performance of AWS solutions. AWS provides several tools for monitoring AWS resources.
## Task 6: Subtask 2: Conduct Logging and Monitoring Security Readiness State Gap Analysis and Story Development
#### Description
To achieve a security readiness state in AWS, conduct a gap analysis between the current state and the security readiness state of logging and monitoring, and develop stories to implement the required changes.

## Task 6: Subtask 3: Establish logging pattern and strategy
#### Description
AWS provides several tools for logging. Establish logging patterns and strategy based on the needs and requirements of the migrating environment. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Logging-and-Monitoring/Logging-Log-Storage-and-Retention-Design.md)

## Task 6: Subtask 4: Define a base set of detective controls to enable
#### Description
Define a base set of detective controls. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Logging-and-Monitoring/Monitoring-Detective-Controls-Design.md)
## Task 6: Subtask 5: Build required monitoring services
#### Description
To capture logs, select the monitoring services that AWS provides and configure them. You can use AWS monitoring features like AWS Config rules, AWS Cloud Watch alarms, AWS Access Analyzer, and AWS Guard Duty for this purpose. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Security/Security-Artifacts/Logging-and-Monitoring/Monitoring-Security-Monitoring-Design.md)
## Task 7: Workload specific Security Requirements
#### Description
Identify and Implement workload specific security needs
## Task 7: Subtask 1: Migration security requirements - Customer & Workload
#### Description
Control - Have you mapped customer & workload specific security requirements to AWS services?

Based on the security cartography performed, define the control requirements necessary to migrate workloads to AWS.

 Aligning to a control framework mapping (which includes assurance framework and security requirements) helps you gain a better understanding of security capabilities provided by AWS, and responsibilities you have for operating securely in AWS. 

https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-security/discovery.html

## Task 7: Subtask 2: Migration security requirements - Customer & Workload
#### Description
Control - Have you listed the security requirements that the workload can inherit from the platform as is?

This is the initial security baseline available in the current platform(LZ)

Initial security baseline should be based on AWS architecture best practices for the core AWS CAF security epics: AWS Identity and Access Management (IAM), detective controls, infrastructure security, data protection, and incident response. 

http://aws.amazon.com/professional-services/CAF/
