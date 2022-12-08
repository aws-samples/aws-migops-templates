
# Module: Initial Engagement with AWS
## Task 1: Get an overview of the AWS migration methodology
#### Description
To migrate applications to AWS, we recommend that you use an approach that consists of four phases: assessment, mobilization, migration, and operation. Before you start a migration, get an overview of these phases and of the AWS tools to consider in each phase. These details help simplify and automate the entire migration experience. 

For an overview of the phases and tools that we recommend you use for migrations, see [AWS Migration Hub.](https://docs.aws.amazon.com/migrationhub/latest/ug/whatishub.html.)

For an overview of the migration process, see [AWS Cloud Migration.](https://aws.amazon.com/cloud-migration/.)
#### Tools
Overview of AWS Migration Services
#### Acceptance Criteria
• Understood the phases of a migration.
#### Acceptance Criteria
• Discovered the list of AWS tools to use in each phase.
## Task 2: Document migration goals
#### Description
Document the type of applications that you want to migrate. Determine the main concerns that you need to address and the outcomes that you want to achieve by migrating to AWS. Example outcomes are cost savings and increased IT productivity. 

The questions and solutions that you document during the discussion help determine the overall direction for the migration.  

For more details, see [AWS Cloud Migration](https://aws.amazon.com/cloud-migration/) and [AWS Prescriptive Guidance](https://aws.amazon.com/prescriptive-guidance/.)
#### Acceptance Criteria
• Documented a comprehensive list of workloads to migrate
#### Acceptance Criteria
• Documented the list of concerns and suggested solutions for AWS  migration.  
#### Acceptance Criteria
• Documented the list of outcomes to be achieved with migration. 
## Task 2: Subtask 1: Application workloads to migrate
#### Description
Create  an initial list of applications that need to be migrated to AWS. Workloads may include  applications, websites, databases, storage, physical or virtual servers and  data centers from an on-premises environment, hosting facility, or other  cloud infrastructures to AWS.
#### Acceptance Criteria
•  Document a comprehensive list of workloads to migrate 
## Task 2: Subtask 2: Address migration concerns
#### Description
There  may be various concerns regarding migrating to cloud such as Application  migration strategies, Software licensing, Cost savings, performance  disruption during migration, migration project resources, developing a  foundation for operating in the cloud, Security and compliance etc. Engaging  with AWS experts will address those prioritized concerns.  

AWS Cloud Migration provides answers to above mentioned concerns:  [AWS Migrations](https://aws.amazon.com/cloud-migration/) 

Also AWS Prescriptive Guidance provides various strategies for AWS  Migrations: [AWS Prescriptive Guidance](https://aws.amazon.com/prescriptive-guidance/)
#### Acceptance Criteria
•  Document list of concerns and suggested solutions for AWS migration.
## Task 3: Perform first planning checkpoint
#### Description
After you complete a deep dive and address the major concerns, prepare a central deck or document where you outline the best solutions and services that AWS provides for migrations.  

Include the following in the deck:  
1) A migration plan for your application portfolio
2) A potential operating model and service management framework
3) A plan to use an experienced AWS partner
4) A plan to use AWS programs such as MAP for the migration
#### Acceptance Criteria
•  A presentation deck with the best solutions and services AWS provides for migrations to AWS
# Module: Migration Readiness Assessment
## Task 1: MRA -  Review objectives and best practices
#### Description
Migration Readiness Assessment (MRA) is a critical step early in the migration journey. Its goal is to assess the readiness of your applications for migrating to AWS. You gain critical  insights regarding readiness and build a plan to close the identified gaps. 

The MRA also provides AWS and AWS partners with an opportunity to build trust and to be positioned as the preferred provider as customers expand their adoption into the AWS Cloud.

As part of the MRA workflow, the primary task is to review the targeted objectives of the migration journey. Targeted objectives might include building an overall vision, creating a reliable implementation roadmap, identifying gaps, and providing corrective actions.

In this module, you review the current architecture, security, and governance. You also create concrete deliverables to prepare for cloud adoption. By validating migration readiness against the available best practices, you can identify the strengths and weaknesses of the current architecture and avoid possible roadblocks while migrating.

For more information about MRA, see [Migration Readiness](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-readiness/welcome.html.)
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Reviewed the current architecture and identify strengths and weaknesses
#### Acceptance Criteria
• Created an implementation roadmap for migration based on best practices
## Task 2: Perform MRA pre-workshop activities
#### Description
Perform  pre-workshop activities as a first step in the MRA.  The pre-workshop activities include the following:  

1) Identifying attendees
2) Pre-workshop questionnaire 
3) Planning the delivery (teneral and technical scope)
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Created a list of attendees who support the MRA delivery
#### Acceptance Criteria
• Created a pre-workshop questionnaire
## Task 2: Subtask 1: Identifying  stakeholders
#### Description
Create a list of attendees who will be part of a unified team that supports the delivery of the MRA. The attendees include a migration expert who facilitates the assessment activities and a customer expert who drives the customer relationship.

For more information about the attendees, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-readiness/assessment-meeting.html#attendees)
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Create a list of attendees who support the MRA delivery
## Task 2: Subtask 2: Pre-workshop Questionnaire
#### Description
A facilitator, a sponsor, and participants of the MRA carry out this task. The facilitator owns the assessment with support from the sponsor and the participants. The facilitator follows the  pre-workshop questionnaire workflow and assigns, follows up, and reviews the questionnaire.


#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Complete pre-workshop  questionnaire.
## Task 2: Subtask 3: Planning the delivery
#### Description
After completing the pre-workshop questionnaire, the facilitator reviews the responses and understands the targeted outcomes. In addition to scheduling the workshop events as part of the MRA, the facilitator also  reviews the technical scope of the MRA. 
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Identify detailed plan of deliverables
## Task 3: Perform MRA workshop activities
#### Description
The facilitator organizes the workshop activities as a second step in the MRA. The workshop agenda includes the following:

1) Executive perspective
2) Trends, success patterns, and alignment
3) Discovery
4) Financial enablement
5) Workshop results and closure
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Prepared a detailed MRA report
#### Acceptance Criteria
• Created a document describing the next phase proposal 
## Task 4: Perform MRA post-workshop activities
#### Description
After you complete the workshop, start preparing for the Mobilize phase. The preparation must cover the following:

1) Customers identify the leader for the migration within the organization
2) Customers have commitment to move forward with the migration phases
3) Customers to decide on governance, security, and operating processes  
4) Creation of a final SOW for the Mobilize phase
#### Tools
Migration Readiness Assessment (MRA)
#### Acceptance Criteria
• Created a detailed SOW for the Mobilize phase
# Module: Data collection setup
## Task 1: Collect data using appropriate data collection tool
#### Description
To evaluate the current migrating environment to AWS, you need to collect the inventory and performance data of the  environment that needs to be migrated. To collect this data, you set up and run the Migration Evaluator collector tool. The collector tool accumulates data with a high level of accuracy, which helps to analyze and suggest the appropriate approach for migration.

For information about the tool, see [Agentless collector overview](https://d1.awsstatic.com/migration-evaluator-resources/agentless_collector_overview.pdf.)




#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• A document (PDF or spreadsheet) with current inventory data and performance data
## Task 1: Subtask 1: Migration Evaluator collector tool overview
#### Description
Migration  Evaluator collector tool document outlines the flow of data while using the  tool, in which the customer chooses to acquire provisioning and utilization  patterns via the on-premises agentless Migration Evaluator Collector.   

More details regarding the tool can be found here:  [Agentless collector overview](https://d1.awsstatic.com/migration-evaluator-resources/agentless_collector_overview.pdf)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• Overview of Migration Evaluator tool.  
#### Acceptance Criteria
• Clear understanding how data is collected and retained using the collector tool.
## Task 1: Subtask 2: Run pre installation checklist
#### Description
After you gain a clear understanding of the Migration Evaluator collector tool, run through a checklist of items before you install the  tool. 

The following document highlights the [checklist](https://d1.awsstatic.com/migration-evaluator-resources/collector_install-guide.pdf.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
•  Run through the checklist and ensure that all prerequisites are satisfied. 
## Task 1: Subtask 3: Install the Migration Evaluator collector tool
#### Description
After you ensure that the items in the pre-installation checklist are satisfied, install the tool. See [here](https://d1.awsstatic.com/migration-evaluator-resources/collector_install-guide.pdf.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• Installed the Migration Evaluator Bootstrapper 
#### Acceptance Criteria
• Installed the Migration Evaluator collector
## Task 1: Subtask 4: Configure the Migration Evaluator collector  tool
#### Description
After  successfully installing the Migration Evaluator collector tool, it needs to  be configured to collect the desired inventory data. This depends on the type  of resources that needs to be migrated to AWS. There could be different types  of resources in a migrating environment such as VMWare, SQL Servers, Bare  metal servers, Hyper V servers etc. 

#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
•  Configured the tool for the desired resources in the environment
## Task 1: Subtask 5: Add notes about collected data
#### Description
After you successfully configure the Migration Evaluator collector tool, validate the collected data and document any missing details and dependencies.
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
•  Added notes and upload the data back to the tool.
## Task 2: Upload existing collector tool data 
#### Description
If a complete list of servers with their provisioning, software, and utilization is already available, the Migration Evaluator tool supports uploading the existing environment data.

Use the data-import template to upload the data. See [Data Import template](https://d1.awsstatic.com/migration-evaluator-resources/ME_DataImport_Simple.68724f31e3dd1469c1095a13597d74c79dd734b9.xlsx.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• Gathered provisioning, software, and utilization data for the existing environment
#### Acceptance Criteria
• Used the data-import template to upload the collected data
# Module: Directional Business Case creation
## Task 1: Generate  quick insights report 
#### Description
Provides a summary of discovered infrastructure, highlighting the savings that can be achieved by rightsizing workloads to match actual utilization. 

Business stakeholders can download a one-page summary highlighting the estimated savings to rehost on AWS based on usage patterns with costs broken down by infrastructure and software licenses.

For a more technical audience, detailed per-server and per-SQL-server data is also available.

For a Quick Insights report sample, see [Quick Insights Sample Report](https://d1.awsstatic.com/asset-repository/Migration_Evaluator_Quick_Insights_Sample_Report.pdf.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• A detailed Quick Insights report that provides a summary of the discovered migrating environment
## Task 2: Generate directional business case
#### Description
A  business case report is provided at the end of the migration assessment. The report includes the following: 

1)  Scope overview
2)  On-premises estimate using industry benchmarks and cost modelling scenarios
3)  Microsoft SQL core insights  
4)  Utilization patterns.For the directional business case, see [Business Case Sample](https://d1.awsstatic.com/asset-repository/tso-logic/MigrationEvaluator_TSOLogic_AWS_BusinessCaseSample.pdf.)

#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
•  A detailed directional-business-case document 
# Module: Specialized assessment Optimization and Licensing Assessment OLA
## Task 1: OLA  Secure customer agreement
#### Description
As part of the  OLA process, secure a customer agreement that includes the following: 

1) Migration project scope
2) Business objective 
3) Project contacts
4) Security and privacy
5) Project-timeline review


#### Acceptance Criteria
• Customer confirms readiness to kick-start the OLA project. 
## Task 2: OLA  Kick off project
#### Description
After the customer confirms readiness to kickstart the OLA project, do the following:

1) Kick off the OLA project
2) Install the data collector tool (Migration Evaluator collector tool) on the desired migrating environment infrastructure
3) Use the tool to collect utilization data
#### Acceptance Criteria
• Provisioned the data collector tool with the desired migrating environment infrastructure
#### Acceptance Criteria
• Used the Migration Evaluator collector tool to collect utilization data for the migrating environment
## Task 3: OLA  Document results
#### Description
After you use the Migration Evaluator collector tool to collect the data, do the following:

1) Prepare the final output presentation based on the collected data
2) Move to the next steps to integrate with partners and Proserve teams
#### Acceptance Criteria
•  Generated the OLA report using the collected data
# Module: Specialized assessment Storage Discovery Analysis SDA
## Task 1: SDA  First planning checkpoint
#### Description
Prepare a central document that outlines the following:

1) Current storage-infrastructure performance and capacity data in the migrating environment
2) Mappings to AWS storage services for each storage infrastructure discovered in the migrating environment
3) Directional cost estimation
4) High-level engagement plan
#### Acceptance Criteria
• Prepare a  presentation where you highlight the discovered storage infrastructure and directional business case
## Task 2: SDA  project kickoff
#### Description
After you create the document, do the following:  

1) Kick off the SDA project
2) Get customer agreement to register for the NetApp Cloud Insights tool 
3) Install the NetApp Cloud Insights tool
4) Use the tool to collect capacity, performance, space savings, storage type, access type, workload type, and architecture details


#### Acceptance Criteria
• NetApp Cloud Insights tool provisioned with the desired migrating environment infrastructure
#### Acceptance Criteria
• Migrating environment utilization data collected using the tool
## Task 3: SDA  Document results
#### Description
After you use the Migration Evaluator collector tool to collect the data, prepare the following: 

1) The final output presentation based on the collected data
2) The next steps to integrate with p artners and Proserve teams


#### Acceptance Criteria
• Documented business case for an on-premises storage migration to AWS  including a one-year directional cost analysis. 
#### Acceptance Criteria
• Documented on-premises storage footprint insights, analysis, and mapping to  AWS storage services  
#### Acceptance Criteria
• Documented roadmap proposal for one (1) pilot storage workload migration (in partnership with ProServe)
# Module: Mobilize Phase readiness
## Task 1: Document  Mobilize phase execution plan
#### Description
Mobilize phase  is performed by both AWS personnel, AWS partners or customer stakeholders. It is  important to determine who performs which Tasks in the mobilize phase. Plan ahead of time by engaging the AWS and customer stakeholders determines who will be performing the tasks. 


#### Acceptance Criteria
• Determine  the AWS Personnel and Customer stakeholder to perform the Mobilize phase  tasks. 
## Task 2: Record  appropriate artifacts and decisions
#### Description
In  order to sign off on the Assess phase as part the AWS Migration the following artifacts must be completed. Some artifacts may not be relevant depending on the type of migration:  

1) Central repository of all migration decisions  
2) Migration Readiness Assessment (MRA) report  
3) Migrating environment infrastructure discovery data   
4) Directional Business Case   
5) Optimization and Licencing Assessment (OLA)  
6) Storage Discovery & Analysis (If needed)  
7) Signed Statement of Work (SOW) if AWS Professional Services or partner is executing the migration


#### Acceptance Criteria
• Present central repository of all migration decisions taken till now
#### Acceptance Criteria
• Ensure upload of Migration Readiness Assessment (MRA) is complete  
#### Acceptance Criteria
• Ensure migrating environment infrastructure discovery data is available
#### Acceptance Criteria
• Ensure Directinal Business Case is approved by senior management  
#### Acceptance Criteria
• Complete Optimization and Licencing Assessment (OLA)
#### Acceptance Criteria
• Complete Storage Discovery & Analysis (If needed)
#### Acceptance Criteria
• Decide who will perform the migration and upload statements of work as needed