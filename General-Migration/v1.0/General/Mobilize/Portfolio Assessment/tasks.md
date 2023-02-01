
# Module: Portfolio Assessment
## Task 1: Portfolio Prerequisites
#### Description
This task helps in assessing data for the migrating environment, procuring discovery tools, and identifying key stakeholders for the portfolio discovery.
#### Tools
Data Source Discovery Assessment
#### Acceptance Criteria
• Finalize the discovery tool for the migrating environment
#### Acceptance Criteria
• Procure the discovery tool 
#### Acceptance Criteria
• Get approval to deploy the discovery tool in the migrating environment 
#### Acceptance Criteria
• Identify the stakeholders who will be involved as part of the migrating environment discovery
## Task 1: Subtask 1: Assess Discovery Data Sources & Tooling
#### Description
For migrating an environment to AWS, identifying and documenting existing sources of data and appropriate tooling is critical. Answering the following questions gives more details regarding the migrating environment�s current data. 

1) How accurate and up to date are the current infrastructure and application inventory?  
2) Does the inventory contain dependency data?
3) Does the inventory contain a catalog of licenses and licensing agreements for each product? 

Based on the level of trust assigned to these data points, choose the best discovery tool. 

For the full guidance, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/understanding-initial-assessment-data-requirements.html.)
#### Tools
Data Source Discovery Assessment
#### Acceptance Criteria
•  Get clear data points on the current infrastructure and its dependencies  
#### Acceptance Criteria
• Choose a discovery tool based on the collected data points
## Task 1: Subtask 2: Procure Discovery Tooling and/or Obtain  Approval for Deployment
#### Description
After you choose the discovery tool, procure the licenses and NDAs for usage and the cost to purchase for deployment in the current infrastructure.  Next, submit these details to organization leadership and stakeholders for approval for deployment in the existing environment.
#### Acceptance Criteria
• Procure the discovery tool by analyzing the cost, license agreements 
#### Acceptance Criteria
• Get approval from organization leadership and stakeholders to deploy in the current environment.
## Task 1: Subtask 3: Identify Stakeholders for Portfolio Discovery
#### Description
Migration of an environment is performed by both AWS personnel and customer stakeholders. It is important to determine who performs which tasks in this phase.  

Determining the answers for the following questions gives more clarity on the stakeholders

1) Who is impacted by the migration?  
2) Who are the decision makers?  
3) Who benefits from this migration?  
4) Who is responsible for performing the migration? 

For more guidance, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/understanding-initial-assessment-data-requirements.html)


#### Acceptance Criteria
• Create a list of stakeholders who will be affected by the migration or benefit from it. 
#### Acceptance Criteria
• Determine the decision makers those and responsible to perform the migration tasks.
## Task 2: Portfolio Discovery
#### Description
This first stage of  assessment focuses on the initial steps of obtaining and analyzing data at  the Portfolio Level. The main objective is to identify business drivers and  collect general data from applications and infrastructure in order to obtain  an initial view of the portfolio, including high-level technical and business  attributes such as application names, environment, product versions,  criticality, performance values, and others. This is key in order to  understand the scope of the project, identify initial migration candidates,  and inform the business case.
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
• Document a detailed plan to perform migrating environment discovery including the scope, prioritization, configuration and data collection.
#### Acceptance Criteria
• Document migrating environment Business drivers such as Accelerate innovation, Reduce operational and infrastructure costs, Increase operational resiliency etc.
#### Acceptance Criteria
• Capture complete application and infrastructure metadata.
#### Acceptance Criteria
• Document complete list of systems which will be part of the data collection.
#### Acceptance Criteria
• Create a prioritized list of applications with a stack rank in order of priority to migrate.
#### Acceptance Criteria
• Create a plan to iteratively collect data requirements of migrating applications.
#### Acceptance Criteria
• Detailed knowledge of the migrating environment
#### Acceptance Criteria
• Interdependencies of the portfolio
#### Acceptance Criteria
• Migration plan with appropriate workloads and timelines
## Task 2: Subtask 1: Plan Portfolio  Discovery Party
#### Description
The primary goals of the discovery party are to level up on the discovery process, identify the addressable scope, introduce an initial application prioritization criteria, and install, configure, and test the discovery tooling (if applicable), including rolling out data collection. To do so, it is necessary that the sources of data be clearly identified. Also, it is key that the requirements for tooling deployment, as well as the technical particularities of the environment where the tool will be deployed, be considered in advance. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/tree/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning)
#### Acceptance Criteria
• Document a detailed plan to perform migrating environment discovery including the scope, prioritization, configuration, and data collection
## Task 2: Subtask 2: Document Portfolio Business Drivers
#### Description
To validate whether the outcomes have been achieved, link business drivers to a metric that can be measured throughout the migration journey. The company�s strategic goals and annual reports can act as a starting point. Focus the conversation on where the company wants to be, based on existent and projected metrics, as a result of moving to the cloud. Consider goals and business outcomes. Also, consider what success looks like as cloud adoption increases.  Next, establish the importance level of each driver. What are the priorities? What are the expected benefits? How do the benefits support the business goals and outcomes? In the context of application portfolio assessment, this will help to assist workload prioritization for migration and to establish technical guiding principles. However, business drivers will define and impact the migration program as a whole.  

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Business-Drivers-and-Technical-Guiding-Principles.md)

#### Acceptance Criteria
• Document migrating environment business drivers such as Accelerate innovation, Reduce operational and infrastructure costs, and Increase operational resiliency
## Task 2: Subtask 3: Review Application Infrastructure Attributes  and Data Requirements
#### Description
Capturing application and infrastructure metadata (regardless of the source) is an iterative approach. It can take several weeks to obtain the desired level of detail. The recommendation is to focus on the data that can be obtained now and to keep enriching the data set as more data become available. A full inventory list includes tooling, assessment process, prioritization, migration strategy, and wave planning. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
#### Acceptance Criteria
•  Capture complete application and infrastructure metadata
## Task 2: Subtask 4: Identify Addressable Application/Infrastructure  Scope
#### Description
To perform the preliminary analysis, it is essential to understand which systems are in scope for discovery. Likewise, when discovery tooling is being used, it is essential to understand which systems will be targeted for data collection.
#### Acceptance Criteria
•  Document complete list of systems which will be part of the data  collection
## Task 2: Subtask 5: Establish Default Application Prioritization  Criteria
#### Description
The objective of application prioritization is to select the application attributes (typically 2 to 10) that will be used to establish the order in which the applications will be moved to AWS, and to then assign a corresponding score or weighting to the possible values of those attributes. Next, you define the importance level of each attribute for prioritization. For example, if two attributes are being considered, the first step is to define the score for each possible value for those attributes. The next step will be to establish one of the attributes to have more importance or relevance for the prioritization of applications. The result of prioritization will be a ranking of applications. If the scoring is correct, the top 20 applications will be good candidates to select from for the initial migration and will be aligned to the desired criteria. If the outcome is not agreed upon, adjust the criteria and recreate the list. It takes several iterations to obtain baselined criteria. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Application-Prioritization-Criteria.md)
#### Acceptance Criteria
•  Create a prioritized list of applications to migrate 
## Task 2: Subtask 6: Create Discovery Tooling roll-out plan
#### Description
It is unlikely that the discovery tool will be collecting data from all targeted systems by the end of the discovery party. Likewise, if a discovery tool is not being used, data collection will typically require more time and manual effort.  In general, data collection (and agent install, if required) will follow a progressive approach throughout several days or weeks. Clarify these aspects and plan for the rollout accordingly.  Data collection is a key input for the upcoming portfolio analysis party and it is recommended to obtain at least 1 or 2 weeks of discovery data from all targeted systems before conducting a data analysis. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
#### Acceptance Criteria
•  Create a plan to iteratively collect the data requirements of migrating  applications
## Task 2: Subtask 7: Intall, Configure, and Test Discovery Tooling
#### Description
The AWS Discovery Agent is AWS software that you install on on-premises servers and VMs targeted for discovery and migration. Agents capture system configurations, system performance, running processes, and details of the network connections between systems. Agents support most Linux and Windows operating systems.
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
• Detailed knowledge of the migrating environment
#### Acceptance Criteria
• Interdependencies of the portfolio  
#### Acceptance Criteria
• Migration plan with appropriate workloads and timelines
## Task 2: Subtask 8: Initiate Discovery Tooling Data Collection
#### Description
Where possible, start data collection during the party targeting the first chunk of systems as defined in the rollout plan. Consider that rolling out discovery tooling requires troubleshooting, especially related to security constraints such as authentication, permissions, and firewall rules. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/Portfolio-Runbooks/AWS-Application-Discovery-Service.md)
#### Tools
AWS Application Discovery Service
## Task 2: Subtask 9: Complete Post Discovery Paty Open Items
#### Description
Review of party outcomes and next steps (for example, ad-hoc sessions to iterate over and finalize elements of the agenda).
#### Acceptance Criteria
•  Review of party outcomes and next steps
## Task 3: Portfolio Data Collection
#### Description
Data collection is the process of gathering metadata from applications and infrastructure. The process is iterative throughout all stages of assessment. Data quantity and fidelity increase as progress is made. At this stage, the focus is on gathering general data that can help to establish an initial inventory leading to the creation of a directional business case and the identification of initial migration candidates. The objective of this group of activities is to complete the data collection rollout (with the discovery tool collecting data from all targeted systems) and monitor its progress, collect manual information from infrastructure assets that cannot be targeted by the discovery tool (for example, legacy systems and secure zones), and to collect application metadata.
#### Tools
AWS Application Discovery Service
#### Tools
Inventory Template
#### Acceptance Criteria
• Data collected and  available on a defined data repository
## Task 3: Subtask 1: Monitor  progress of discovery tooling rollout
#### Description
Ensure that data collection is progressing and that any issues are being actively addressed. Assist the customer with obtaining support from the tooling vendor if required.
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
• Ensure the continuity of data collection without problems 
## Task 3: Subtask 2: Gather application metadata
#### Description
Work with the relevant teams to identify key application attributes such as application names, mapped infrastructure, environments, criticality, complexity, and others. Use the ongoing output of the discovery tool where possible in order to label auto-discovered applications. Use the Migration Portfolio Assessment (MPA) tool functionality to send customized online questionnaires to ingest application data whenever possible. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
#### Tools
Inventory Template
#### Acceptance Criteria
• Work with the relevant teams to gather application metadata
#### Acceptance Criteria
• Use the MPA tool to gather additional metadata
## Task 3: Subtask 3: Perform manual discovery workshops and activities if applicable
#### Description
In most environments there are cases where the discovery tool of choice doesn�t support a given legacy system. Examples include old operating system versions and legacy platforms such as AS400 or Mainframe.  If these systems are in scope for migration, recommend and perform manual discovery. This might require connecting to those systems directly, or the use of scripts that can be obtained from the discovery tooling vendor or platform teams or by specialized AWS practices. Conduct manual discovery workshops when necessary. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
#### Acceptance Criteria
• Collect data manually for systems that don't support tools
## Task 4: Preliminary Portfolio Analysis
#### Description
The objective of this  group of activities is to perform a preliminary analysis of the collected data.
#### Tools
AWS Migration Evaluator
#### Tools
AWS Migration Evaluator
#### Acceptance Criteria
• Initial application and infrastructure inventory
#### Acceptance Criteria
• Migration evaluator directional business case 
#### Acceptance Criteria
• Prioritized applications identified
## Task 4: Subtask 1: Review Asset  and Dependency from Discovery Tooling Output
#### Description
This session is intended to review all available data and construct an initial inventory of applications and infrastructure and to identify gaps. For more information, see the Portfolio Data Collection Task.
#### Acceptance Criteria
• Review the data collected from the migrating environment data collection 
#### Acceptance Criteria
• Create an initial inventory of applications and infrastructure
## Task 4: Subtask 2: Directional Business Case
#### Description
Some discovery tools include the option to export data in a format that is suitable for the AWS Migration Evaluator. If this is not the case, obtain the latest AWS Migration Evaluator data import template, transfer the data, and create a new Migration Evaluator assessment and upload the data. 

For more information, see [Migration Evaluator](https://aws.amazon.com/migration-evaluator/)
#### Tools
AWS Migration Evaluator
#### Acceptance Criteria
• Create a new Migration Evaluator assessment and upload the data from those discovery tools that don�t support data in a format that suitable for the Migration Evaluator
## Task 4: Subtask 3: Identify Prioritized Applications
#### Description
Analyze the applications at a high-level. The expected outcome is to agree on the contents of the first migration wave and plan for a detailed assessment of those applications. Document the list of applications in the linked artifact. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Prioritized-Applications-(wave-1-or-pilots).md)
#### Acceptance Criteria
• Finalize the plan for the first migration wave
#### Acceptance Criteria
• Document the list of applications to be targeted in Wave 1 
## Task 5: Prioritized Applications Assessment
#### Description
The Prioritized Applications Assessment stage focuses on the detailed discovery of a subset of prioritized applications to produce an initial AWS architecture design and migration strategy. The strategy must take into account the estimated infrastructure run rate in AWS.
#### Tools
AWS Application Discovery Service
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
• Detailed application discovery
#### Acceptance Criteria
• An AWS application architecture design that includes an AWS run-rate estimate  
#### Acceptance Criteria
• A migration strategy that includes the handling of application dependencies
## Task 5: Subtask 1: Perform  Application Assessment Party
#### Description
The Application Assessment Party is a 1- to 3-day sprint-based, interactive event designed to assist the customer with the following: 
1) Prioritizing a subset of applications targeted for migration
2) Performing a detailed discovery
3) Conducting an AWS design session
4) Creating a draft migration strategy The party facilitates the identification of specific requirements and blockers for detailed application assessment, application design, and migration strategy for the in-scope applications, and resolves them. 

The duration of the party depends on the number of applications to be assessed and their complexity. The base estimate is of one day per application; the recommendations is to work with a maximum of 3 applications per party for a maximum duration of three days. However, this can change based on application complexity and customer needs.

#### Acceptance Criteria
• Prioritized  list of subset applications which are to be migrated to AWS. 
## Task 5: Subtask 2: Confirm Prioritized Applications
#### Description
The goal of this session is to establish which key attributes will determine the selection of applications for the party. In some cases, the applications that are being targeted will be known in advance. In other cases, it will be required to choose the most appropriate applications. The objective is to assist the customer in identifying key application attributes to determine priority. This includes assigning a corresponding weighting to the possible values of those attributes.  Next, define the attribute importance level for prioritization.The result will be a ranking of applications. If the weighting and criticality are correct, the top five will be good initial candidates for assessment. If the top applications don�t make sense, adjust the criteria as needed.  

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Template---Application-and-Infrastructure-Inventory.md)
#### Acceptance Criteria
•  Create a list of prioritized applications to be migrated to AWS
## Task 5: Subtask 3: Perform Prioritized Applications Deep Dive
#### Description
Use the suggested artifacts to conduct a detailed assessment. Ensure that the session includes the stakeholders that are needed to dive deep into the business, architecture, and technology aspects. The use of discovery tools for dependency analysis is highly recommended.  

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Prioritized-Applications-(wave-1-or-pilots).md)
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
•  Conduct a detailed assessment for the prioritized applications to be migrated to AWS
## Task 5: Subtask 4: Create first Draft for Prioritized Applications  Architecture Design
#### Description
After the data is collected for the prioritized applications that are to be migrated to AWS, create a first draft of a prioritized applications architecture design. Document, at a high-level, the functional and non-functional requirements for this architecture. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/2-Prioritized-Applications-Assessment/Template---Application-AWS-Architecture-Design-and-Migration-Strategy.md)

#### Acceptance Criteria
• Document the first cut of the migration architecture design with functional and non-functional requirements
## Task 5: Subtask 5: Create first Draft for Prioritized Applications  Migration Strategy
#### Description
The next step is to document the migration strategy for the prioritized applications.  Review the 7R terms and finalize the migration strategy based on the migration patterns.  

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/2-Prioritized-Applications-Assessment/Template---Application-AWS-Architecture-Design-and-Migration-Strategy.md)

#### Acceptance Criteria
• Document the first cut of the migration architecture strategy such as Rehost, Rearchitect, etc.
## Task 5: Subtask 6: Complete Post ApplicationAssessment Party Open  Items
#### Description
Review the application assessment party outcomes and the next steps to perform.

#### Acceptance Criteria
•  Finalize the next steps to perform
## Task 6: Portfolio Analysis and Migration Planning
#### Description
The Portfolio Analysis and Migration Planning task focuses on iterating the work initiated in the previous stages in enriching the portfolio data and baseline a migration wave plan.
#### Acceptance Criteria
• Infrastructure and application inventory
#### Acceptance Criteria
• A tested 7R disposition tree 
#### Acceptance Criteria
• Prioritization criteria 
#### Acceptance Criteria
• Validated wave 1 
#### Acceptance Criteria
• Migration wave plan (draft) 
#### Acceptance Criteria
• MPA export
## Task 6: Subtask 1: Plan Portfolio  Analysis Party
#### Description
The primary outcome of the analysis party is to extract meaning out of available data and initiate the full assessment of the portfolio of applications.  Typically, the analysis party follows 1-Portfolio Discovery and Initial Planning, although it can also be performed independently whenever data is already available from other sources. This can be the case when a discovery tool has been deployed or when previous discovery-related engagements have taken place.  

The main prerequisite is the availability of one full week of programmatic data collection as a minimum (or equivalent data) from all in-scope systems, including asset communication data, in order to evaluate application dependencies.
#### Acceptance Criteria
• Initiated  full assessment of the portfolio of applications
## Task 6: Subtask 2: Review Asset and Dependency Discovery Tooling Output
#### Description
A quick review of the available data. Typically, the output of the discovery tooling or equivalent data. The goal is to learn how to access the data and how it is presented. This is a high-level review to train attendees on data usage and format.
#### Acceptance Criteria
•  Completed review of the output from the discovery tools
## Task 6: Subtask 3: Iterate Applications metadata
#### Description
The following data points describe the information required to obtain a complete portfolio view of the applications in the migration and their associated infrastructure: 
 
1) Application attributes along with inventory, prioritization, and recommended fidelity levels 
2) Infrastructure attributes along with inventory, prioritization, and recommended fidelity levels 
3) Network attributes along with inventory, prioritization, and recommended fidelity levels 
4) Migration attributes along with inventory, prioritization, and recommended fidelity levels To collect the data in the previous list, use the discovery tools and iterate multiples. 
#### Acceptance Criteria
•  Collected a detailed list of applications metadata iteratively until the entire  portfolio data are completed. 
## Task 6: Subtask 4: Iterate 7R Disposition Tree
#### Description
The 7R disposition tree is used as a guide for application owners and architects, among others, to evaluate which path to take when migrating an application. Each project has unique circumstances and decision-making processes that need to be incorporated into the tree logic. 

For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/3-Portfolio-Analysis-and-Migration-Planning/Artifact---7R-Disposition-Tree.md)
#### Acceptance Criteria
•  Documented the knowledge on 7R and justification for selecting any R strategy.
## Task 6: Subtask 5: Iterate Application Prioritization Criteria
#### Description
The goal of this session is to establish which key attributes will determine the order in which applications are to be migrated. This is a key input for constructing migration wave plans.If tooling in use lacks the capability/features to perform prioritization, use the Migration Portfolio Assessment. For more information, see [GitHub](https://github.com/aws-samples/aws-migops-guidance/blob/main/General-Migration/v1.0/Portfolio/PortfolioAssessment/1-Portfolio-Discovery-and-Initial-Planning/Artifact---Application-Prioritization-Criteria.md)
#### Acceptance Criteria
•  Prioritized a list of applications that are to be migrated to AWS. The list is  refreshed iteratively to reach a baselined version. 
## Task 6: Subtask 6: Draft Wave Plan
#### Description
The objective is to use the prioritization criteria and start shaping a wave plan. Wave planning can take several weeks. The intention is to outline a first draft and focus on validating the first few waves, especially Wave 1.  How much can be achieved during this task, will depend on the data available, the participants, and the size of the scope. If the discovery tool of choice doesn�t include wave planning features, you can use the MPA tool (available to AWS employees and partners) to construct the plan.  Ensure that all assets and communications data have been exported from the discovery tool (or equivalent) and imported it into MPA. This information is essential for the wave planning process. 

For more information, see [here](https://mpa.accelerate.amazonaws.com/.)
#### Acceptance Criteria
•  Created a first wave plan that includes the list of applications and prioritization criteria. 
## Task 6: Subtask 7: Complete Post Analysis Party Open Items
#### Description
Review  of party outcomes and next steps.
#### Acceptance Criteria
•  Finalized next steps to perform
## Task 6: Subtask 8: Baseline Application Prioritization Criteria
#### Description
To create high-confidence migration wave plans, you must establish a baseline for the portfolio of applications and its associated infrastructure.  

Prioritization criteria must be baselined by the end of the Wave 1. This will form the base for the rest of the waves. Update the criteria before each wave.

#### Acceptance Criteria
•  Created a base application prioritization criterion and iterated it for the  future waves.
## Task 6: Subtask 9: Baseline 7R Disposition Tree
#### Description
To create high-confidence migration wave plans, you must establish a baseline for the portfolio of applications and its associated infrastructure.  

When you establish a baseline for the portfolio, confirm a migration strategy for each application component. The migration strategy will be one of the 7 Rs for migration. A 7 R strategy must also be associated with each of the application's infrastructure components.
#### Acceptance Criteria
•  Confirmed that each application and its components are assigned on the 7Rs for  migration strategy.
## Task 6: Subtask 10: Baseline Portfolio Asset & Dependency  Discovery
#### Description
To  create high-confidence migration wave plans, you must establish a baseline  for the portfolio of applications and its associated infrastructure.   To establish a baseline version of the portfolio, including dependencies  and migration strategies.

#### Acceptance Criteria
•  Created a base application inventory and iterated it for the future waves.
## Task 6: Subtask 11: Baseline Application metadata
#### Description
To  create high-confidence migration wave plans, you must establish a baseline  for the portfolio of applications and its associated infrastructure.   Complement the data with information gathered from key stakeholders such as  application owners and infrastructure teams. Keep gathering data until you  obtain a complete portfolio inventory that matches the attributes and level  of fidelity for this stage. The resulting dataset will be essential in  driving the migration.
#### Acceptance Criteria
•  Created a base application metadata criteria and iterated it for the future  waves.
## Task 6: Subtask 12: Baseline Dependency Groups and Wave Plan
#### Description
To create high-confidence migration wave plans, you must establish a baseline for the portfolio of applications and its associated infrastructure.  Technical dependencies can be described in four categories: 1) Application-to-infrastructure  2) Application-component 3) Application-to-application 4) Application-to-infrastructure services 

For more information, see [Baseline Application Portfolio](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/baseline-application-portfolio.html.)

#### Acceptance Criteria
•  Created base dependency groups and iterated them for the future waves.