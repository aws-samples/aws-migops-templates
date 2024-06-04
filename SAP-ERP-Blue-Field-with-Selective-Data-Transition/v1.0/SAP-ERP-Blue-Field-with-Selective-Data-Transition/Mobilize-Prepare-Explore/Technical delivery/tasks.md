
# Module: Technical delivery
## Task 1: System Delivery
#### Description
SAP delivery team to provide access to the cloud systems.Once the Customer has signed the contract and all prerequisite technical details have been received, SAP provision the systems as per the customer's contract. Providing the PPF was complete within the stipulated time and as per the CDD, the customer's IT contact will receive the system handover e-mails with the URL, login ID, and password for all the respective systems. These emails will contain all necessary information to start the provisioning of the SAP solution. The Admin user ID and password will be provided in separate email communication. The systems handover detailed information will be accessible in the SAP One Support Launchpad useful link.Procedure:Locate the provisioning e-mails sent to the IT contact with system details. Confirm delivery and access to the systems. Follow the provisioning emails for details procedure. Follow the credentials email to receive and update the technical username and password.Note(s):The SAP Project Lead will securely provide the initial logon credentials.The technical user is a local SAP S/4HANA user and is not intended for day-to-day use, but rather for the creation of the new administrator business user.For any questions related to the status of the systems, the customer can reach out to the SAP team via email: engage-rise@sap.com or they can contact the Customer Interaction Center (CIC).

## Task 2: Verify delivered systems
#### Description
Partner to check that the system is delivered with the requested pre-configured business content.

## Task 3: Deliver PCE systems
#### Description
System set up activities post system hardening handover and before handover to Functional teams; handover of Development (DEV), Quality Assurance (QA), and Production (PRD) systems from SAP to Customer and Partner project team.

#### Tools
AWS EC2  
#### Acceptance Criteria
• Documented Incident Response Discovery and Analysis, which includes 
a) Completed gap analysis 
b) Completed playbooks for common security incidents 
c) Standard operating procedure (SOP) for performing incident response activities in AWS
#### Acceptance Criteria
• Completed a workshop to understand the incident-response strategy in AWS 
## Task 4: Setup users and assign authorisations
#### Description
Once the systems have been received, the Customer should create the initial users in the System that will participate in the implementation project. The System Administrator will also set up user accounts in the target system and assign user specific authorization profiles that will allow them to access the appropriate system functionality and/or transactions. This activity is essential before the users can be trained and before they can log into the system.

#### Tools
AWS EC2  
#### Tools
AWS Security Groups
#### Tools
AWS WAF
#### Tools
AWS Lambda
#### Tools
AWS SSM Parameter Store 
#### Tools
AWS CloudFormation
#### Tools
AWS Virtual Private Cloud (VPC)
#### Tools
Network ACLs
#### Tools
AWS Secrets Manager
#### Acceptance Criteria
• Completed gap analysis 
#### Acceptance Criteria
• Defined an administrative access policy for EC2 instances
#### Acceptance Criteria
• Identified a list of AWS VPC security features to be implemented 
#### Acceptance Criteria
• Defined a secret-management policy 
#### Acceptance Criteria
• Defined a certificate management policy 
#### Acceptance Criteria
• Defined WAF rules management 
#### Acceptance Criteria
• Defined IDS/IPS strategy 
#### Acceptance Criteria
• Documented and defined common security groups and NACLs to be used across AWS accounts 
## Task 5: System Design Handover
#### Description
After receiving and reviewing the technical assessment form from the customer, the CAA (Partner CAA for indirect, SAP CAA for direct deals) will then validate and confirm the form with the customer.

#### Tools
AWS CloudWatch Alarms
#### Tools
AWS CloudFormation
#### Tools
Amazon VPC flow logs
#### Tools
AWS Access Analyzer  
#### Tools
AWS CloudTrail
#### Tools
AWS Config  Rules
#### Tools
Amazon GaurdDuty
#### Acceptance Criteria
• Logging and Monitoring Discovery and Analysis
#### Acceptance Criteria
• Completed gap  analysis  
#### Acceptance Criteria
• Logging best practices  
## Task 6: Temporary Hardware for Shell Creation
#### Description
Temporary hardware is required to create Shell systems from the source system (via system copy)

## Task 7: Shell System creation (via system copy) from ECC.
#### Description
Create a shell ECC system from source ECC (production) system with just configuration & ABAP repository copied over to shell system.
## Task 8: Shell System Conversion from SAP ECC to SAP S/4HANA
#### Description
Perform a one time conversion of SAP ECC to SAP S/4HANA.
## Task 9: Golden Copy Backup of converted SAP S/4HANA system
#### Description
Take a Golden Copy Backup of converted SAP S/4HANA system. This will be used to build dev, quality, test production systems.