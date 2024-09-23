
# Module: Detailed Discovery Workstream
## Task 1: Detailed Discovery Data Collection
#### Description
1. Collect data as per the data collection sheet leveraging the below mechanism :- 
*  Discovery tool collection
*  Standardize data collection template
*  Application migration team interview sessions and workshops

2. Leverage [AWS Application Discovery Service](https://aws.amazon.com/application-discovery/) or [AWS Partner Discovery Tool](https://aws.amazon.com/prescriptive-guidance/migration-tools/migration-discovery-tools/) to perform the detail discovery. 

3. The selection of the tool will depend on the below areas :- 
* Customer requirement -  required metrics, dependency, analysis type, tool features and platform supportability
* Customer constrains -  collection mechanism (agent vs agentless),  data residency, data sovereignty, support resource requirement, access permission, connectivity, data type collection (PII data) and tooling cost.
* Collection of data as per the data collection sheet requirement.

4. Select a tool that can meet at least 85% of the IT inventory requirement and be prepared to manually assess the remaining workloads through application migration team interview and workshops sessions. Ensure the applications that have the most dependencies are part of the tool discovery.

5. The application migration team interview sessions and workshops are conducted in parallel to :-
* Collect data that is unable to be collected by the tool example business application names, application criticality, application function, licensing agreements, application roadmap, SLA, OLA, and compliance.
* Validate data collected by the tool to validate accuracy and state.

6. All data collected should be inserted into the data collection template for further detailed application assessment and analysis.
#### Tools
AWS Partner Discovery Tool
#### Tools
 AWS Application Discovery Service
#### Acceptance Criteria
1. Successful detail discovery data collection leveraging migration tooling, standardize template and application migration team interview sessions.
2. Successful documentation of the collected discovery data.
## Task 2: Detailed Application Assessment and Portfolio Analysis
#### Description
1. Detailed application assessment and portfolio analysis on the discovered applications.

2. Execution of 4 key task to analyze and build the application wave group :-
* Application Group Definition
* Application Target State Design
* Application Migration Strategy Definition
* Application Wave Group Prioritisation

3. Execution of additional modernisation assessment in a scenarios where customers business and technical drivers prioritizes cloud business value and requirements to leverage modern services on AWS to support the technical requirements of the application.
#### Acceptance Criteria
1. Successful analysis and building of the application wave group.
2. Successful prioritization of the application wave group.
3. Successful completion of modernisation data collection and assessment (if required).
## Task 2: Subtask 1: Application Group Definition
#### Description
1. Understand the application system, component and functionality in scope of the migration or modernization. 
 
2. Divide the application into two broad groups "infrastructure/Operations Applications" and "Business Applications". 
* **Infrastructure/operation application** - application that supports the current infrastructure, operating model, security and compliance services/functionality.
* **Business Application** - application that supports business /department specific services /functionality.

3. Group all infrastructure/operation application under a single group. These application will be further assessed , mapped and migrated during the operating model workstream.

4. Under the Business Application group, further group the listed application based on system or business application names.

5. Evaluate the connectivity between the system or business application sub-group.
* **Critical Dependency / Hard Dependency** : Involves transactional connection with low latency tolerance that require continues connection between application or application components.
* **Non-Critical Dependency / Soft Dependency** : Involves non-transactional connection in example batch or over the internet connections.

6. Group all application that have critical/hard dependency into application dependency groups which is also known as application wave group.

7. Select a potential wave group for the  pilot application known as wave group 1.

7. Leverage [Application Portfolio Assessment Guide](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/portfolio-analysis-migration-planning.html) for prescriptive guidance and best practice reference when executing application grouping definition task.
#### Tools
Migration Portfolio Assessment (MPA)
#### Tools
AWS Partner Tooling 
#### Acceptance Criteria
1. Successful definition of application wave group.
2. Successful selection of potential pilot application wave group (Wave Group 1).
## Task 2: Subtask 2: Application Target State Design
#### Description
1. Define and document reference architecture that will outline the target architecture baseline requirements and standards for applications running on AWS.

2. Leverage the reference baseline architecture to design the application target state design per application wave group.

3. Application target state design should take into considerations the below areas :-
*  Application roadmap requirements
*  Application drivers
*  Application infrastructure and performance requirements
*  Application connectivity, dependency and integration requirements
*  Application security and compliance requirements
*  AWS Service usage and availability

3. Leverage [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) as AWS best practice references when designing the target architecture .

4. Prioritise the target state design completion for Wave Group 1 - Pilot Application.

5. Define and document the pilot application target architecture diagram in the implementation documentation. This will also set the documentation standards required from a target state design standpoint for all application migrating or modernizing onto AWS.
#### Tools
AWS Well-Architected Framework
#### Acceptance Criteria
1. Successful completion of target state application design for Wave Group 1 - Pilot applications.

#### Acceptance Criteria
2. Successful establishment of baseline architecture standards which will be leveraged when architecting target architecture for remaining Application Wave Groups.
## Task 2: Subtask 3: Application Migration Strategy Definition
#### Description
1. Align the AWS 7R migration strategy to each application components or tier taking into consideration the below areas :-
*  Migration timelines
*  Existing and available investments
*  Application business and technical driver
*  Application roadmap and requirements
*  Selected AWS services that will host the application component based on the target architecture design. 

2. Leverage the [application portfolio assessment guide for AWS cloud migration](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/iterating-7-rs-migration-strategy-selection.html) and [migration pattern by workload prescriptive guidance](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/migration-migration-patterns-by-workload-pattern-list.html)  as best practice reference when executing migration strategy alignment to the respective application component/tier.

3. It is recommended to leverage the below general approach and services in most migration scenarios unless there are specific requirements identified during the discovery or assessment :-
*   Application Rehost onto AWS  - AWS Application Migration Service (MGN) applications
*   Database Rehost onto AWS -  Database Native Tool
*   Homogeneous Database Replatform onto AWS -  Database Native Tool or AWS Database Migration Service (DMS) 
*   Heterogeneous Database Replatform onto AWS -  AWS Schema Conversion Tool, AWS Database Migration Service (DMS)
*   Large Data migration - AWS Datasync

4. Align a migration tool to the selected application migration strategy to accelerate migration or modernisation execution.
#### Tools
AWS Migration and Transfer Services 
#### Acceptance Criteria
1. Application components assigned and aligned with an AWS Migration Strategy. 
2. Selected migration strategy has a defined tool/service assigned to execute the migration or modernization.
## Task 2: Subtask 4: Application Wave Group Prioritisation
#### Description
1. Define application wave group prioritisation. 

2. Prioritisation are defined by using the [prioritization criteria](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/iterating-prioritization-criteria.html) which takes into account :- 
* Application Business Criticality
* Application Technical Complexity
* Application Architecture and Design Complexity
* Application Operating Model
* Migration Strategy
* Application Driver

3. Application will broadly be grouped in Infrastructure/operating model application group and business application group. For business application group leverage the [portfolio playbook template](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-portfolio-playbook/samples/portfolio-playbook-templates.zip) to further score the application and design the wave group plan. 

4. Applications grouped under the infrastructure/operating model group which supports the infrastructure, operating model, security and compliance components  will be migrated or extended under Wave 0 under the Operating Model Workstream . This includes the below application  types :-
*  Authentication
*  Domain Name Services (DNS)
*  Time (Network Time Protocol)
*  Monitoring
*  Logging
*  Patching
*  Backup
*  Deployment (CI/CD)
*  Configuration Management
*  Inventory / Customer Management Database
*  Alerting
*  Service Catalogue
*  IT Service Management

5. Pilot applications will be selected based on the prioritization criteria to form Wave Group 1. It is recommended to select non business critical and non technical complex applications with a less effort migration to be part of the pilot migration to ensure accelerated success and quick wins.  However, the application selected should also be meaningful to the organization to allow them to invest confidence on future wave group migrations.

6. All selected application wave groups will be migrated by environment starting with non-production to production to de-risk the application wave group migration.

7. All wave groups must align to the defined migration timelines and meet the **maximum 24 months** completion from the project start date requirement of the Migration Acceleration Program (MAP). 


#### Tools
AWS Partner Tooling
#### Tools
Portfolio Playbook Templates
#### Tools
Migration Portfolio Assessment (MPA)
#### Acceptance Criteria
1. Successful completion of prioritisation of Application Wave Group defined under the Application Grouping task.
#### Acceptance Criteria
2. Successful Application Wave Group prioritisation alignment to the migration timelines and meets the allowed 24 months from the project's start date requirement of the Migration Acceleration Program (MAP).
## Task 2: Subtask 5: Modernisation Assessment 
#### Description
1. Plan and execute the AWS Modernization Assessment for identified  application for modernization leveraging the MODA tool . 

2. An application can be identified for modernization through the below tasks :- 
*  Migration Readiness Assessment (MRA) session
*  Detail application assessment and portfolio application interview sessions
*  Operating Model assessment sessions

3. Leverage the [MODA delivery guide](https://apg-library.amazonaws.com/content/9a0f200d-eb3b-4b13-b10a-6be0cc81e29d) to successfully conduct and complete the modernization assessment. MODA assessment tool is only available for AWS and AWS partner. If required please contact your AWS team for information.

4. Data collected through the MODA tool will be analyzed and selected application application for modernization will continue to undergo grouping, target state design, migration strategy definition and wave group prioritisation.
#### Tools
Modernization Assessment (MODA) Tool
#### Acceptance Criteria
1. Successful completion of modernization data collection.
2. Successful completion of modernization assessment and identification.