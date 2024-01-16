
# Module: SAP landscape Discovery and Technical Approach
## Task 1: Conduct SAP landscape review and finalize scope
#### Description
In the preliminary stages of your project, it is important to verify all SAP systems and SAP landscapes that are in scope for migration (as well as out of scope components to confirm integration/dependancies). The goal is to make sure that all SAP core & peripheral components in the migration scope are identified for AWS migration. For example, SAP ECC / HANA, BW, PI, SolMan, databases, Operating  Systems, Bolt-ons etc. It's important to clarify, this step is identifying high level scope & landscape, vs. detailed server inventory which will be done in a later task.

There are discovery tools available which can optionally be used to automatically collect customers landscape information (see subtasks / tools section for more information)
#### Acceptance Criteria
List of SAP workloads in scope to migrate
## Task 1: Subtask 1: Collect SAP architecture / landscape diagrams
#### Description
Collect SAP architecture / landscape diagrams to understand data flow between existing systems, external interfaces, network separation.
#### Acceptance Criteria
Detailed SAP architecture / landscape diagrams captured
## Task 1: Subtask 2: Document comprehensive SAP inventory details for customer's entire SAP landscape
#### Description
Obtain / collect comprehensive SAP inventory details for customer's entire SAP landscape. This should include all SAP systems and bolt-ons whether in-scope or out of scope (to ensure awareness of entire landscape).  The following details should be captured:

* All server information with details such as: SERVER NAME, pCore, Allocated vCPU, mem capacity, storage capacity, OS, Physical or virtual, CPU Arch, Host/VMName, OS, # of CPUs, Memory capacity, Provisioned storage, Used storage.
* All relevant OS versions in use, patch levels, license status, etc.
* All SAP systems & related bolt-ons/applications (whether SAP products or third party/SaaS solutions), SAP components or modules that are part of the complete SAP landscape (e.g. ECC, S4HANA, BW, Solution Manager, PI, GRC, etc), with details such as: SAP Component/module, Business processes managed, Type of app (SAP, 3rd party, custom), Hosted on-prem or cloud/SaaS, System landscapes (# of landscapes & types Dev/Test/Prod/Sandbox), Architecture - Application only or App + DB.



#### Tools
SAP on AWS Questionnaire
#### Tools
SAP System Inventory
#### Acceptance Criteria
• Completed inventory spreadsheet with full server, system and application details for entire SAP landscape 
## Task 1: Subtask 3: Collect SAP EWA reports
#### Description
Collect SAP EarlyWatch Reports for all systems included in the migration scope.

Review SAP Note: 2357073 - How to Create an Ad Hoc EarlyWatch Alert SAP - Solution Manager 7.2 for details on how to generate Ad Hoc EWA reports Review SAP Note: 207223 - SAP EarlyWatch Alert Processed at SAP for details on how to generate EWA reports without SAP Solution Manager
#### Acceptance Criteria
Most recent SAP EarlyWatch Alert report for each SAP system
## Task 1: Subtask 4: Run HANA sizing report
#### Description
Run HANA sizing report to collect HANA memory footprint and requirements. This is applicable for both HANA to HANA migrations and AnyDB to HANA migrations

Refer to SAP Note: 1872170 - ABAP on HANA sizing report (S/4HANA, Suite on HANA...) for details on running the HANA sizing report on ABAP-based systems.
#### Acceptance Criteria
Generate the reports for each SAP HANA system and download from SAP
## Task 1: Subtask 5: OPTIONAL Automated SAP data collection tools
#### Description
AWS offers three complimentary services to provide automated data collection for on-premise system details.  
* AWS Application Discovery Service (ADS) helps customers plan migration projects by gathering information about their on-premises data centers. 
* AWS Migration Evaluator identifies the most cost-effective options, provides visibility into multiple migration strategies, and captures insights into how reusing existing software licensing reduces costs even further. 
* AWS Migration Hub provides network visualization that lets customers accelerate migration planning by quickly identifying servers and their dependencies, identifying the role of a server, and grouping servers into applications.
#### Tools
Amazon Migration Evaluator
#### Tools
Overview of AWS automated data collection tools
#### Tools
AWS Migration Hub Discovery
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
* Inventory and system utilization captured for on-premise systems
* After you successfully configure the Migration Evaluator collector tool, validate the collected data and document any missing details and dependencies
## Task 2: Determine your migration approach
#### Description
Depending on your situation, you can choose a homogeneous or heterogeneous migration approach. A homogeneous migration is generally more straightforward, while a heterogeneous migration is more elaborate.
Migration Approach.

*Homogeneous *: A homogeneous SAP migration involves migrating your SAP applications (including the database) to a new environment with the same operating system and database platform. This is also known as a rehost or as-is migration approach.

*Heterogeneous* : A heterogeneous SAP migration is migrating to a new environment with a different operating system or database platform.















#### Tools
Migraiton Scenarios
#### Acceptance Criteria
Initial alignment on migration approach for each SAP application
## Task 3: Design initial future state architecture and estimate pricing
#### Description
There are AWS specific considerations relating to network configurations, compute, storage, and security that help you get the most out of your SAP environment on AWS.  Architecting your SAP landscape on AWS does require a  mind-set change to take advantage of the agility and scalability that AWS offers for SAP workloads. You’ll also want to understand how SAP architectures leverage various AWS services, and how the AWS environment provides better security and availability than a traditional environment. 

Work with your AWS account team to design your future-state cloud architecture and provide pricing estimates for your migration project. 
#### Tools
Getting Started with Architecting SAP on the AWS Cloud
#### Tools
SAP on AWS Planning
#### Acceptance Criteria
AWS account team provides preliminary AWS future-state architecture and pricing estimate