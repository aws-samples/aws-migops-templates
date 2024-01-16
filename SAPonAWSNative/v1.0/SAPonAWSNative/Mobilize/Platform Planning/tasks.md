
# Module: Platform Planning
## Task 1: Confirm architecture patterns and finalize future state AWS architecture for SAP
#### Description
Based on the preliminary AWS future-state architecture, work with all stakeholders to confirm the architecture patterns, and AWS services required to run your SAP environment in the AWS Cloud (compute, storage, networking, etc).  Once confirmed, finalize design of the future state AWS architecture for the SAP environment.
#### Tools
SAP Netweaver on AWS
#### Tools
Amazon EC2 Instance Types for SAP on AWS
#### Tools
Architecture patterns for SAP 
#### Tools
Architecture patterns for SAP HANA on AWS
#### Tools
AWS Services overview
#### Tools
SAP on AWS Planning
#### Acceptance Criteria
• Future state AWS architecture defined
• Create architecture diagrams that highlights the overall SAP Landscape, connections between systems and external dependencies  .
• Create SAP architecture diagram that show steady state, HA and DR scenarios.
## Task 1: Subtask 1: Review SAP on AWS Architecture guidelines
#### Description
Review architecture guidelines  on  AWS services  typically used for SAP workloads and some of the key points to understand when designing your architecture for hosting SAP on AWS. If you are already familiar with these AWS services, you can skip this section. 
#### Tools
Architecture guidelines and decisions 
## Task 1: Subtask 2: SAP on AWS cost estimation
#### Description
AWS offers pay-as-you-go pricing. You only pay for the services you use, for as long as you use them. There are no long-term contracts or complex licensing requirements. 
Understand pricing characteristics of AWS services that are frequently used for the deployment and operation of SAP systems on AWS. This includes: 
* AWS Region :
* Compute 
* Storage
* Network
* Automation
* Backup, restore, and recovery
* Migration
* Monitoring
* Operating System licenses
* AWS Marketplace
* AWS Support

Amazon EC2 provides the following purchasing options to enable you to optimize your costs based on your needs:
•	On-Demand Instances – Pay, by the second, for the instances that you launch.
•	Savings Plans – Reduce your Amazon EC2 costs by making a commitment to a consistent amount of usage, in USD per hour, for a term of 1 or 3 years.
•	Reserved Instances – Reduce your Amazon EC2 costs by making a commitment to a consistent instance configuration, including instance type and Region, for a term of 1 or 3 years.
•	Spot Instances – Request unused EC2 instances, which can reduce your Amazon EC2 costs significantly.
•	Dedicated Hosts – Pay for a physical host that is fully dedicated to running your instances, and bring your existing per-socket, per-core, or per-VM software licenses to reduce costs.
•	Dedicated Instances – Pay, by the hour, for instances that run on single-tenant hardware.
•	Capacity Reservations – Reserve capacity for your EC2 instances in a specific Availability Zone for any duration.

#### Tools
SAP on AWS cost estimation
#### Tools
AWS Pricing Calculator
#### Tools
Instance purchasing options
#### Acceptance Criteria
• Estimated Cost for SAP on AWS Architecture based on the migration needs. 
## Task 1: Subtask 3: Determine Architecture patterns based on failure scenarios.
#### Description
Examine the architecture patterns available to handle the various failure scenarios for your SAP system. 
Determine if single region or multi-region architecture patterns is most suited for you SAP workloads.  If your SAP production systems are critical to your business and you require minimal downtime in the event of failure, you should select a Multi-Region pattern to ensure that your production systems are highly available at all times. When deploying a Multi-Region pattern, you can benefit from using an automated approach (such as, Cluster solution) for fail over between Availability Zones to minimize the overall downtime and remove the need for human intervention. Multi-Region patterns not only provide high availability but also disaster recovery, thereby lowering overall costs.
#### Tools
Architecture patterns
#### Tools
Failure scenarios
#### Acceptance Criteria
• Established usage of Single or Multi Region Pattern for the SAP workload migration.
## Task 1: Subtask 4: Design VPC and Determine Subnet Zoning patterns for SAP Workloads
#### Description
Determine your VPC network for SAP applications to be accessed both internally and externally based on the need. Document the possible ways in which SAP applications need to be accessed. Typically applications access falls into one of these four categories : 
* Internal-only access,
* Internal and controlled external access, 
* Internal and uncontrolled external access,
* External-only access.

Design sub-net zoning patterns based on access routes and   security requirements.Finally map the individual applications to various network  zones depending on the requirements.

#### Tools
VPC Subnet Zoning Patterns for SAP on AWS, Part 2: Network Zoning
#### Tools
VPC Subnet Zoning Patterns for SAP on AWS, Part 1: Internal-Only Access
## Task 1: Subtask 5: Determine Connectivity options for SAP Applications on AWS
#### Description
Amazon VPC provides multiple network connectivity options for you to use, depending on your current network designs and SAP environment  requirements. These connectivity options include using either the internet or an AWS Direct Connect connection as the network backbone and terminating the connection into AWS or user-managed network endpoints. Additionally, with AWS, you can choose how network routing is delivered between Amazon VPC and your networks, leveraging either AWS services or user-managed network equipment and routes. 

* Determine Connectivity options for **Network-to-Amazon VPC** : This is needed for integrating AWS resources with your existing on-site services (for example, monitoring, authentication, security, data or other systems) by extending your internal networks into the AWS Cloud. This network extension also allows your internal users to seamlessly connect to resources hosted on AWS just like any other internally facing resource. 

* Determine Connectivity options for VPC-to-Amazon VPC  : This is needed for integrating multiple Amazon VPCs into a larger virtual network. Often customers require multiple VPCs due to security, billing, presence in multiple regions, or internal charge-back requirements, to more easily integrate AWS resources between Amazon VPCs. 

* Determine connectivity options of Software remote access-to-Amazon VPC connectivity options: This is required for SAP GUI, HANA Studio and other rich client tools used in the SAP landscape.
#### Tools
How to connect SAP solutions running on AWS with AWS accounts and services
#### Tools
Deploying SAP GUI on Amazon AppStream 2.0
#### Tools
Amazon Virtual Private Cloud Connectivity Options
## Task 2: Capacity Planning
#### Description
Conduct Sizing exercise to determine hardware requirements such as memory, CPU power, disk space, I/O capacity, and network bandwidth. It is an iterative process to translate business requirements into hardware requirements, and is usually performed early in the project. Ensure Sizing exercise is completed and required capacity planning on AWS is conducted .


#### Tools
SAP Sizing guidelines
#### Tools
1656099 - SAP Applications on AWS: Supported DB/OS and AWS EC2 products
#### Tools
1656250 - SAP on AWS: Support prerequisites
#### Tools
SAP Product Availability Matrix (PAM)
#### Tools
2493172 - SAP HANA Hardware and Cloud Measurement Tools
#### Acceptance Criteria
• Instance type family is identified for Compute, Storage and Network
• Capacity Reservation is done as required.
## Task 2: Subtask 1: Gather SAP EWA from the current landscape
#### Description
SAP EWA reports are provided by SAP regularly. Focus on the Hardware Configuration section of the EWA report. The h/w section provides your CPU, cores and memory size information of the current SAP instances.These reports provide an overview of historical system use. Analyze these reports to see if your existing SAP system is overused or underused. You can use this information to right size your environment. Gather the SAPS values configured on the on-prem hardware.
## Task 2: Subtask 2: Understand various sizing methods and guidelines offered by SAP
#### Description
Greenfield Sizing: If you want to size a new SAP applications from scratch.

Brownfield Sizing: If you have an SAP system running that you want to extend with new functionality (Delta Sizing – mix between greenfield and brownfield sizing) and/or add new users (Re-Sizing) or migrate to SAP HANA.

Expert Sizing: If you are working in a large company with complex business structures, and/or custom coding, you should perform an expert sizing.
#### Tools
SAP Quick Sizer
#### Tools
1872170 - ABAP on HANA sizing report (S/4HANA, Suite on HANA...)
#### Tools
2296290 - New Sizing Report for SAP BW/4HANA
#### Tools
SAP Hardware sizing decision tree
## Task 2: Subtask 3: Identify compute , storage and networking needs on AWS
#### Description
Evaluate and estimate the performance requirements using metrics from the SAP tools and existing workloads. Map the compute requirements to the SAP supported instances best suited to your workload. Consider any specific storage or network requirements for the instance types as well as the availability of the required instance types in your chosen AWS Region and Availability Zones.

Evaluate  storage-infrastructure performance and capacity data in the current SAP environment. Gather  I/O and throughput information for the existing SAP workloads.  Map the  requirement to AWS  storage types based performance, scalability , Cost and redundancy. Plan to scale linearly using LVM striping mechanisms .Map AWS storage services for each storage infrastructure discovered in the SAP environment . Consider Identify Amazon FSx for NetApp® ONTAP storage need for critical SAP workloads. Consider Amazon EFS (Linux) and Amazon FSx (Windows) for durable file storage needs (like saptrans )  that can span multiple Availability Zones or needs to be accessed by multiple instances.

Although Network performance is often not explicitly stated as a requirement in SAP sizing, but you should check the network performance requirement for of each SAP workloads to ensure that the target architecture is going to  deliver the required performance. Also Identify needs for instance proximity to meet workload specific SLA needs ( placement groups , Inter AZ latency etc) 
#### Tools
Amazon EC2 instance types for SAP on AWS
#### Tools
Optimal compute solution for SAP on AWS
#### Tools
Storage Configuration for SAP HANA
#### Tools
SAP HANA on AWS with Amazon FSx for NetApp ONTAP
## Task 2: Subtask 4: Identify need for Dedicated Hosts and High memory instances ahead of time
#### Description
Amazon EC2 Dedicated Hosts are physical servers with EC2 instance capacity fully dedicated to your use..It is really important to Identify needs for Dedicated Hosts and High memory instances as certain types of instance families need sufficient lead time for the capacity to be available in the AZ. Engage your technical account manager /AWS account team early on to discuss needs and get options.
## Task 2: Subtask 5: Identify need for On-Demand Capacity Reservations
#### Description
On-Demand Capacity Reservations enable you to reserve compute capacity for your Amazon EC2 instances in a specific Availability Zone for any duration. Capacity Reservations mitigate against the risk of being unable to get On-Demand capacity in case there are capacity constraints

 Create a Capacity Reservation to ensure that you always have access to Amazon EC2 capacity when you need it, for as long as you need it.
 
 **Common use cases for Capacity Reservations:**

Disaster recovery — you can reserve capacity in a different Availability Zone or Region to ensure that the capacity you need is available during a fail over event.

Regulatory requirements — you can use Capacity Reservations to satisfy regulatory requirements for high availability. Capacity Reservations ensure that capacity is in place to meet those requirements, even if you aren't utilizing those resources.

Events — you can create Capacity Reservations before your business-critical events to ensure that you can scale when you need to.

## Task 3: Define Security Requirements for SAP Workloads
#### Description
The security module goal is to help customers structure the selection and implementation of controls that are right for the organization. The directive, preventive, detective, and responsive components of the AWS Cloud Adoption Framework (CAF) security perspective organize the principles that will help drive the transformation of organization’s security culture.
#### Tools
Security and auditing in SAP network design
#### Tools
SAP HANA Security
#### Acceptance Criteria
• Security and compliance strategies
## Task 3: Subtask 1: Understand the shared responsibility model
#### Description
Security is a shared responsibility between AWS and you. The shared responsibility model describes this as security of the cloud and security in the cloud:

• Security of the cloud – AWS is responsible for protecting the infrastructure that runs AWS services in the AWS Cloud. AWS also provides you with services that you can use securely.
• Security in the cloud – Your responsibility is determined by the AWS service that you use. You are also responsible for other factors including the sensitivity of your data, your company’s requirements, and applicable laws and regulations
#### Acceptance Criteria
• Knowledge of the shared responsibility model in AWS for SAP migrations.
## Task 3: Subtask 2: Create a data protection strategy
#### Description
To safeguard data in AWS, establish and implement a methodology for encryption at rest and in transit for AWS resources. Use the following steps and create subtasks if needed.
1. Document the current and readiness states of data protection.
2. Conduct a data protection readiness gap analysis and story development.
3. Define an encryption-at-rest strategy.
4. Define encryption-in-transit strategy.
5. Develop encryption security controls.
#### Tools
Amazon GaurdDuty
#### Tools
AWS Security Hub
#### Tools
AWS CloudFormation
#### Tools
Amazon Macie
#### Tools
AWS Key Management Service
#### Acceptance Criteria
• Identified a data protection strategy.
• Completed a data protection gap analysis.
• An AWS resource encryption strategy for data at rest.
• An AWS resource encryption strategy for data in transit.
## Task 3: Subtask 3: Create an IAM strategy
#### Description
AWS Identity and Access Management (IAM) is a service that helps an administrator securely control access to AWS resources. IAM administrators control who can be authenticated and authorized. Securely control access to AWS services and resources for users to provision and orchestrate AWS resources. Perform the following steps and create subtasks if necessary.

1. Document the identity-and-access-management current and readiness states.
2. Conduct an identity-and-access-management security readiness state gap analysis.
3. Define IAM roles and policies.
4. Define IAM break-glass policies.
#### Tools
AWS IAM
#### Acceptance Criteria
• An identity-and-access-management readiness report.
• Completed an identity-and-access-management gap analysis.
• Completed an identity-and-access-management strategy.
## Task 3: Subtask 4: Create an infrastructure protection strategy
#### Description
To have a reliable and trustable infrastructure for business workloads to run on, create a strategy for a secure and compliant infrastructure.

Perform the following steps and create subtasks if necessary.
Perform an infrastructure protection security readiness state gap analysis
Define an infrastructure protection strategy
Define a certificate and secrets management policy
Build infrastructure security controls

#### Tools
AWS IAM Security Groups
#### Acceptance Criteria
• Completed infrastructure protection gap analysis.
• An infrastructure protection readiness report.
• Completed infrastructure protection strategy.
## Task 3: Subtask 5: Create a compliance strategy
#### Description
When you perform a SAP  migration to AWS, the responsibility for compliance is determined by the sensitivity of the data, the company's compliance objectives, and applicable laws and regulations. AWS provides the following resources to help with compliance:

• Security and Compliance Quick Start Guides - These deployment guides discuss architectural considerations and provide steps for deploying security- and compliance-focused baseline environments on AWS.
• Architecting for HIPAA Security and Compliance Whitepaper – This whitepaper describes how companies can use AWS to create HIPAA-compliant applications.
• AWS Compliance Resources – This collection of workbooks and guides might apply to your industry and location.
• Evaluating Resources with Rules - assesses how well your resource configurations comply with internal practices, industry guidelines, and regulations.
• AWS Security Hub – This AWS service provides a comprehensive view of your security state within AWS that helps you check your compliance with security industry standards and best practices.
#### Acceptance Criteria
• Defined compliance strategy.
## Task 4: Define Resiliency Goals for SAP Workloads
#### Description
The AWS global infrastructure is built around AWS Regions and Availability Zones. Regions provide multiple physically separated and isolated Availability Zones, which are connected through low-latency, high-throughput, and highly redundant networking. With Availability Zones, you can design and operate applications and databases that automatically fail over between zones without interruption. Availability Zones are more highly available, fault tolerant, and scalable than traditional single or multiple data center infrastructures.
#### Tools
AWS Global Infrastructure
#### Tools
SAP on AWS HA Setup (Netweaver)
#### Tools
SAP on AWS HA Setup Guide (HANA)
#### Acceptance Criteria
• HA/DR Strategy for SAP Production and non-prod workloads (optional).
## Task 4: Subtask 1: Define HA strategy for  HANA databases on AWS
#### Description

#### Tools
Best Practices for HA Setup for HANA
## Task 4: Subtask 2: Define HA Strategy for SAP Applicaiton Tier on AWS
#### Description
Define HA strategy for ASCS, ERS and AAS for a resilient SAP application tier.
#### Tools
SAP NetWeaver on AWS Deployment and Operations Guide for Windows
#### Tools
SAP NetWeaver HA on AWS Configuration Guide for SLES and RHEL
#### Tools
SAP on AWS High Availability with Overlay IP Address Routing
## Task 4: Subtask 3: Define HA/DR Strategy for Business Objects systems
#### Description
Define strategy to setup HA and DR for Business Objects, Business Objects Data Services, Business Objects Information Steward landscape
#### Tools
SAP BusinessObjects BI Platform on AWS: HA/DR Guide for Linux
#### Tools
SAP BusinessObjects BI Platform on AWS: HA/DR Guide for Windows
#### Acceptance Criteria
• HA/DR strategy is defined using the best practices mentioned above for the provisioned infrastructure. 
## Task 4: Subtask 4: Define HA Strategy for other SAP systems
#### Description
Ensure HA strategy is defined for all other SAP workloads on AWS. ( application, databases , gui, fronted etc..)
## Task 4: Subtask 5: Define DR Strategy for SAP Applications
#### Description
Setup disaster recovery strategy for sap applications based on the recovery point objective and recovery time objective.
#### Tools
Passive Disaster Recovery for SAP applications using AWS Backup and AWS Backint Agent
#### Tools
Accelerating recovery during restarts for SAP HANA using AWS Elastic Disaster Recovery
#### Tools
Disaster Recovery SAP
#### Tools
Implementing disaster recovery on AWS cloud for SAP workloads
#### Acceptance Criteria
• Appropriate DR tool needs to be chosen based on the RPO and RTO requirements from the above list of tools. 
## Task 5: Establish Landing Zone/Control Tower and Foundational Security
#### Description
As SAP on AWS Customers start their Cloud Journey, it is important to follow a standardized approach towards establishing a secure cloud foundation, starting with establishing the Landing Zone & Control Tower. This task provides guidance and tools to ensure standards for design, build, and configuration of a secure AWS environment; implementation of foundational services in each AWS account; customizable native AWS solutions and security capabilities where applicable. 

AWS Landing Zone accelerates customer adoption of the cloud by providing a prescriptive set of instructions for deploying an AWS-recommended foundation of interrelated AWS accounts, networks, and core services. AWS Control Tower provides prescriptive guidance and best practice templates that a customer can deploy into their initial AWS environment, with confidence that it will grow to meet future business needs including security and regulatory compliance requirements.  
#### Tools
AWS Control Tower
#### Tools
AWS Landing Zone
#### Acceptance Criteria
• Completed Landing Zone for SAP migration.
• Verified checklist of items of landing-zone accounts
• Reviewed current account structure details
• Completed Target AWS Account structure for SAP Non-Prod & Prod Workloads.
## Task 5: Subtask 1: Inventory existing AWS accounts and Resources
#### Description
**Inventory existing AWS accounts and resources.**
1. Conduct Interviews to understand current account structure
2. Create missing Architecture Diagrams of Account structure
3. Identify and determine Network Resources for use in AWS
4. Complete Parameters Check List
5. Request AWS Limit Increases
6. Identify Monitoring Needs
7. Identify Organizational Tagging Strategy
8. Verify Level of AWS Support
9. Identify and Create Email Address Schema

## Task 5: Subtask 2: Design Workshops for LZ/CT
#### Description
Workshop topics should include most of the following: 
1. Basic Training – initial knowledge on AWS Landing Zone and AWS Control Tower
2. Overview and Design - Core Account Configuration
3. Design - VPC \ CIDR \ AZ - Provisioning up a Landing Zone requires designing multiple AWS services
4. Design - Security Groups \ NACL - For each security group, add rules that control the traffic based on protocols and port numbers. There are separate sets of rules for inbound traffic and outbound traffic.
5. Design - WAN \ VPC Connectivity - VPC and WAN connectivity is critical while setting up landing zone.
6. Design – DNS
7. Design-Tagging
#### Tools
AWS VPC
#### Acceptance Criteria
• Complete knowledge on AWS Landing Zone and AWS Control Tower
• Provisioned core components in AWS Landing Zone and AWS Control Tower
## Task 5: Subtask 3: Implement Landing Zone
#### Description
Once all the pre-requisites and parameters are defined in the workshop, set up the landing zone in the desired AWS region. 
#### Tools
Control Tower Landing Zone setup
#### Tools
Building a Landing Zone
#### Acceptance Criteria
• Created an AWS landing zone for the migration.
## Task 5: Subtask 4: Review Architecture guidelines and decisions (compute, storage & network)
#### Description
Review AWS best practices and Architecture guidelines for SAP workloads and other key points from [SAP On AWS Whitepaper](https://docs.aws.amazon.com/sap/latest/general/arch-guide-architecture-guidelines-and-decisions.html) to understand when designing your landscape for hosting SAP on AWS. If you are already familiar with these AWS services, you can skip this section. 

Review the published guidelines in the following areas: 

* Regions and Availability Zones
* AWS account Model
* Compute
* Networking
* Storage
* Monitoring and audit

#### Tools
Review SAP on AWS Technical Documentation
## Task 5: Subtask 5: Determine how your SAP workloads align with your AWS account strategy and landing zone
#### Description
An important consideration when running SAP workloads in AWS is the AWS account strategy and landing zone approach that you adopt to meet your organization’s security controls. You should consider separating SAP from non-SAP workloads and having production workloads in a separate account from non-production workloads.Understand your organization’s existing AWS account management strategy, including the use of the AWS Organizations and AWS Control Tower. Consider isolating security and log capabilities into an isolated account.
#### Tools
AWS multi-account strategy for your AWS Control Tower landing zone
#### Tools
Well-Architected Framework [Security]
#### Tools
Organizing Your AWS Environment Using Multiple Accounts
#### Tools
Establishing your best practice AWS environment
#### Acceptance Criteria
• SAP workloads incorporated into overall AWS account strategy.
## Task 6: Define and execute tagging strategy for SAP Workloads
#### Description
Implementing a tagging strategy is a process of iteration and improvement. Start small with your immediate priority and grow the tagging schema as you need to.  Tags can be used for a variety of purposes, the overall tagging strategy can be split into areas of responsibility within an organization. Tagging allows a programmatic approach to activities that depend upon the characterization of resources. The range of stakeholders that can benefit from tagging will depend on the size of the organization and operational practices. Larger organizations can benefit from clearly defining the responsibilities of the teams involved in building and implementing a tagging strategy. Some stakeholders can be responsible for identifying the needs (defining use cases) for tagging, while others can be responsible for maintaining, implementing, and improving the tagging strategy.

By assigning ownership, you are in a good position to implement individual aspects of the strategy. Where appropriate, this ownership can be formalized as policy and documented in a responsibility matrix (for example, RACI: Responsible, Accountable, Consulted, and Informed), or in a shared responsibility model. In smaller organizations, teams might play multiple roles in a tagging strategy, from requirements definition to implementation and enforcement. 
#### Tools
Tagging for MAP (Migration Acceleration Program)
#### Tools
Tagging recommendations for SAP on AWS
#### Tools
AWS Tagging best practices
#### Acceptance Criteria
• All SAP workloads properly tagged according to the identified strategy
## Task 7: Determine IaC & Migration Tooling
#### Description
Identify infrastructure provisioning and automation tool preferences and define approach for the project. There are many  tools available such as AWS Cloud Formation, AWS Launch Wizard, Terraform, Ansible, Chef, Puppet, AWS Systems Manager etc.  Any existing enterprise standards should have been identified during the Assess phase and decision should be made at this point to leverage the standard, or utilize AWS provisioning tools like Cloud Formation / Launch Wizard.
#### Tools
Migration Tools and Methodologies
#### Tools
AWS Migration Hub Orchestrator
#### Tools
AWS Launch Wizard for SAP
#### Tools
DevOPs for SAP
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
Confirmation on infrastructure provisioning and automation tool