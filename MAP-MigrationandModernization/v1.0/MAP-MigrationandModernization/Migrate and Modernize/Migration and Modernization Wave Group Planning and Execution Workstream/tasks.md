
# Module: Migration and Modernization Wave Group Planning and Execution Workstream
## Task 1: Migration Project Governance
#### Description
The activities to formalize the migration plan and project governance are as below :-
* Migration Wave Planning
* Migration Team Resource Allocation
* Migration Status Communication and Tracking
* Migration RACI creation or update

#### Acceptance Criteria
1. Successful build, schedule and documentation of the migration wave groups.
2. Successful Migration Team resource allocation.
3. Successful establishment of migration communication plan.
4. Successful creation of detailed RACI.
## Task 1: Subtask 1: Migration Wave Planning & Work Breakdown Structure creation
#### Description
1. Perform sprint planning for scheduled waves . 

2.  Refer to the [large migration play book](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-migration-playbook/task-one-sprint-planning.html) and [wave planning](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/wave-planning.html) for best practices on sprint planning.

3. Create a Work Breakdown Structure (WBS) using suitable tools or in standardize template. This should include :-
 * Phases
 * Tasks
 * Sub-tasks, 
 * Task Dependencies 
 * Resource allocation, 
 * Task Expected Start and End Dates
 * Task Expected Effort
 * Task Actual  Start and End Dates
 * Task Actual Effort
#### Tools
Migration Hub - Journeys
#### Acceptance Criteria
1. Successful scheduling of migration wave group.
2. Successful documentation of migration wave group.
## Task 1: Subtask 2: Migration Team Resource Allocation
#### Description
1. Analyse the list of project resources required for the tasks in the current sprint plan and WBS

2. Identify and allocate project team member resources to the tasks based on the skill and proficiency level as tracked in the training tracker. Refer to [large migration foundation playbook](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-foundation-playbook/team-org.html) for resource allocation best practices.

3. Periodically review and update the Work Breakdown Structure (WBS) with changes in tasks, and resource allocations, along with start and end date information.
#### Acceptance Criteria
1. Successful migration team definition and resource allocation.
## Task 1: Subtask 3: Migration Status Communication and Tracking
#### Description
1. Summarize the progress of the migration phases and tasks as tracked in the sprint planning and WBS documents.

2. Schedule and track ongoing migration communication through defined communication plan mechanism. Refer to the [large migration play book](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-governance-playbook/stage2.html) as best practice reference to execute migration communication.

3. Maintain & review the Risks, Actions, Issues and Dependencies (RAID) log for any risks and issues identified and include these in your project status reporting based on the decided reporting mechanism and frequency. Ensure transparency in communication to all relevant stakeholders.
#### Acceptance Criteria
1. Successful definition of the migration communication plan.
2. Successful establishment of RAID log.
## Task 1: Subtask 4: Create/Update Detailed RACI (Responsible, Accountable, Consulted, Informed) Matrix
#### Description
1. Review and update the detailed RACI matrix defined in the Mobilize Phase with any new or changed tasks in the mobilize and migration activity requirements. 

2. Refer to the [large migration foundation playbook](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-foundation-playbook/team-org.html#raci) for best practices in defining the RACI leveraging the required steps and starter template.

3. Share the updated RACI matrix with all stakeholders on an ongoing basis in the status report.
#### Acceptance Criteria
1. Successful creation or update of detailed migration RACI.
## Task 2: Migration Financial Governance
#### Description
Creating migration financial governance by configuring the below areas :-
* Financial Reporting
* Billing Alerts
#### Acceptance Criteria
1. Successful configuration of financial reporting
2. Successful configuration of billing alerts.
## Task 2: Subtask 1: Financial Reporting Process Creation
#### Description
1. Validate if financial reporting process established. 

2. Create a financial reporting process if not created during the Mobilize Phase. For best practice guidance refer to the prescriptive guidance [financial reporting steps](https://docs.aws.amazon.com/prescriptive-guidance/latest/large-migration-governance-playbook/task-project-management.html#step-financial-reporting).

3. Project manager should be aware of AWS Billing and Cost Management concepts and best practices . For best practice reference refer to [AWS cost management documentation](https://docs.aws.amazon.com/cost-management/latest/userguide/what-is-costmanagement.html)
#### Acceptance Criteria
1. Successful configuration of financial reporting.
## Task 2: Subtask 2: Enable Billing Alerts
#### Description
1. Validate if AWS Billing alerts are configured.

2. Create and enable AWS Billing alerts if not created during Mobilize Phase to obtain early billing alarms  and ensure the AWS migrations are being executed within expected spend/budget. For best practices, refer to [AWS cost monitoring](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html).

3. Leverage the [create a billing alarm user guide](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/monitor_estimated_charges_with_cloudwatch.html).

4. Ensure the delivery team is part of the team that will be alerted when there is a pricing spike.  
#### Acceptance Criteria
1. Successful enabling of AWS Billing alerts to ensure migration are executed within the expected spend/budget.
## Task 3: Application Wave Group Planning, Migration and Modernization
#### Description
1. Plan the migration of the identified wave group application workloads during the detail discovery and planning workstream.

2. Execute the migration of the identified wave group application workloads.

3. Wave group application workload documentation.

4. Wave group application workload knowledge transfer and handover.

5. Wave group application workload sign off and acceptance.
#### Acceptance Criteria
1. Successful wave group application discovery validation, application architecture design and application backlog definition.
2. Successful wave group application migration strategy alignment and tooling definition

#### Acceptance Criteria
3. Successful wave group application cutover and rollback plan definition.
4. Successful wave group application networking, operating model, security and compliance requirements setup.
5. Successful wave group application build or migration.
#### Acceptance Criteria
6. Successful wave group application integration and validation.
7. Successful wave group application MAP tagging.
8. Successful Well Architected Review completion of wave group application.
#### Acceptance Criteria
9. Successful wave group application implementation and runbook documentation.
10. Successful wave group application migration sign-off and acceptance documentation.
## Task 3: Subtask 1: Wave Group Application Discovery Validation
#### Description
1. Conduct validation workshop with the below customer stakeholders teams that manages the defined wave group application :-
*  Infrastructure team
*  Application/Developer Team
*  QA Team
*  Operations Team
*  Security and Compliance Team
*  Product Manager

    These team is also known and reffered to as the Application Migration Team.

2. Leverage the validation workshop to validate the below data collected during the detail discovery and portfolio assessment workstream :-
*  Application roadmap
*  Application criticality and impact
*  Application/infrastructure specifications
*  Application inter-dependencies
*  Application security and compliance requirements
*  Application testing requirements
*  Operational requirements - monitoring, logging, backup, deployment, patch management, configuration management, service management and alerting.
*  Migration timelines

   This is to ensure there are no critical updates or changes to the plan or requirements on the application from the point of previous discovery.

3. Evaluate the wave group application requirements and current state for the need to introduce AWS accelerators. There are two accelerators that can be leveraged in the Migrate and Modernize Phase :-
* Migration Experience-Based Acceleration (EBA) for migration
* Modernization (ModAx) Experience-Based Acceleration (EBA) for modernization

	The Experience-Based Acceleration (EBA) can help accelerate the planning, migration and modernization execution and validation of the wave group application workloads.  The Experience-Based Acceleration (EBA) should be executed on a selected application workload wave group to build repetitive mechanism for migration and modernization acceleration of all remaining wave group applications. 

4. Update the data collected above into the data collection sheet.These data will be used to refine the wave group application design.
#### Acceptance Criteria
1. Successful data collection validation of wave group application specification and requirement.
## Task 3: Subtask 2: Wave Group Application Design
#### Description
1. Re-design is only required if there are changes to the wave group application data collection.
 
2. Leverage the updated data collection sheet to refine the wave group application target architecture on AWS with reference to the design baseline standards.

3. Ensure the below areas are taken in to consideration when refining the  target state design  :-
*  Application roadmap requirements
*  Application drivers
*  Application infrastructure and performance requirements
*  Application connectivity, dependency and integration requirements
*  Application security and compliance requirements
*  AWS Service usage and availability

4. Leverage [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) as AWS Best Practice reference when designing the target architecture .  

5. Confirm wave group application architecture design with the Application Migration Team.

6. Document the refined wave group application target architecture diagram in the implementation documentation.

#### Tools
AWS Well-Architected Framework
#### Acceptance Criteria
1. Successful refinement of wave group application target architecture.
2. Successful confirmation of the refined wave group target architecture diagram with the Application Migration Team.
## Task 3: Subtask 3: Wave Group Application Backlog Definition
#### Description
1. Work with the Application Migration Team to define the steps/backlog to successfully migrate the wave group application to AWS.

2. The migration steps should cover :-
*  **Pre-migration requirements** - steps required to make the changes to wave group application and support the wave group application functionality in the cloud.
*  **Migration/modernization requirements** - steps required to migrate / modernize the wave group application inclusive tooling deployment, tooling configuration, validation, cutover plan and rollback.
*  **Post Migration requirements** - steps required during post migrations to ensure wave group application integration, validation and documentation.

3. Common Pre-Migration requirements task are as below :-
*  Change request approval 
*  Resource allocation
*  Account requirement setup
*  Network requirements setup and throughput testing
*  Security port opening
*  DNS Configuration - TTL changes

4. Common Migration/Modernization requirements task :-
* Tool installation and configuration
* Replication configuration
* Replication execution and monitoring
* Pre-cutover testing/validation
* Cutover Plan - must include critical task to cutover including people requirement
* Rollback Plan - must include task to rollback in case of cutover failure

5. Common Post Migration requirements task are as below :-
*  Wave group application / server configuration
*  Wave group application integration / re-pointing
*  Security and compliance configuration and integration
*  Operating model component configuration and integration
*  Post migration test/validation
*  Wave group application documentation

#### Acceptance Criteria
1. Successful documentation of wave group application backlog covering pre-migration, migration and post-migration requirements.
2. Successful buy-in of task requirements and resource allocation from Application Migration Team.
## Task 3: Subtask 4: Wave Group Application Migration Strategy and Tooling Definition
#### Description
1. Re-evaluate or re-align the AWS 7R migration strategy defined in the Detail Application Assessment and Portfolio Analysis workstream for the wave group application component or tier taking into consideration the below areas :-
*  Changes in the wave group application business and technical requirements
*  Application roadmap and driver
*  Selected AWS services for hosting the wave group application component in the target architecture design. 

2. Leverage the [Application Portfolio Assessment guide for AWS Cloud Migration](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/iterating-7-rs-migration-strategy-selection.html) and [Migration Pattern by Workload](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/migration-migration-patterns-by-workload-pattern-list.html) prescriptive guidance as best practice reference when executing migration strategy alignment to the respective pilot application component/tier.

3. It is recommended to leverage the below general approach and services in most migration scenarios unless there are specific requirements identified during the discovery :-
*   Application Rehost onto AWS  - AWS Application Migration Service (MGN) applications.
*   Database Rehost onto AWS -  Database Native Tool or AWS Database Migration Service (DMS).
*   Homogeneous Database Replatform onto AWS -  Database Native Tool or AWS Database Migration Service (DMS).
*   Heterogeneous Database Replatform onto AWS -  AWS Schema Conversion Tool, AWS Database Migration Service (DMS).
*   Large Data migration - AWS Datasync.

	*Note : Introduce AWS Partner Tooling which can be obtained from the [AWS Marketplace](https://aws.amazon.com/marketplace) when AWS Services or Native tools are unable to meet complex or specific requirements.*

4. Align migration tools to the selected application migration strategy to allow migration or modernisation execution. 
#### Acceptance Criteria
1. Wave group application components assigned and aligned with an AWS Migration Strategy. 
2. Selected migration strategy has a defined tool/service assigned to execute the migration or modernization.
## Task 3: Subtask 5: Wave Group Application Migration Cutover Plan Definition
#### Description
1.  Define cutover plan for the wave group application workloads.

2.  The defined cutover plan must include a rollback plan in case the cutover is not successful. The rollback plan needs to be documented in the migration plan and timelines.

3.  Validate the cutover plan with Application Migration Team. 

4.  Ensure the cutover plan activities are documented as part of the migration plan and timelines.

5.  Leverage the [AWS Cutover Prescriptive Guidance](https://docs.aws.amazon.com/prescriptive-guidance/latest/best-practices-migration-cutover/overview-cutover-phase.html) as reference when building the cutover plan. 
#### Acceptance Criteria
1. Successful definition and documentation wave group migration cutover plan.
2. Successful definition and documentation wave group migration rollback plan.
3. Successful alignment of wave group migration cutover plan with Migration Application Team.
## Task 3: Subtask 6: Implement Wave Group Application Network Requirements
#### Description
1. Leverage the wave group application design documentation to implement the network requirements to support the migration and operations on AWS.

2. Ensure the network requirements implementation covers the below areas :- 
*  Segregation/Isolation Requirements
*  VPC Requirement
*  Subnet Requirements
*  IP Requirements
*  Network Encryption
*  Network Bandwidth and Throughput
*  Connection within AWS and External requirement
*  Connection Type

3. Leverage the [establishing your cloud foundation on aws](https://docs.aws.amazon.com/whitepapers/latest/establishing-your-cloud-foundation-on-aws/network-connectivity-capability.html) prescriptive guidance as guidance and best practices when implementing the network requirements.

4. Validate the network configuration, throughput and bandwidth requirements. Leverage the [AWS Network Access Analyzer](https://docs.aws.amazon.com/vpc/latest/network-access-analyzer/what-is-network-access-analyzer.html), [perform ssl connectivity and bandwidth test](https://docs.aws.amazon.com/drs/latest/userguide/perform-connectivity-bandwidth-test.html) prescriptive guidance and/or similar partner tooling to automate network validation.

5. Document the wave group application network requirement changes as part of the implementation/system documentation if there are changes during the implementation phase.
#### Tools
Network Access Analyzer
#### Acceptance Criteria
1. Successful implementation of wave group application network requirements
2. Successful completion of network validation.
3. Successful documentation of wave group application network requirements during implementation phase.
## Task 3: Subtask 7: Implement Wave Group Application Operating Model Requirements
#### Description
1. Leverage the wave group application design documentation to implement the cloud operating model requirements to support the migration and operations on AWS.

2. Ensure the cloud operating model requirements implementation covers the below areas for the wave group application based on the defined strategy under the operating model workstream :-

* Monitoring & Event Management
* Patch Management
* Logging
* Backup / Continuity Management
* Deployment - CI/CD
* AMI Management
* Tag Management
* Automation
* Inventory Management
* Service / Incident Management
* Service Catalogue
* Financial Management
* Configuration Management
* Change Management
* Account and User Management
* License Management

   This task will mainly involve the leverage of the defined operating model processes and AWS Services/partner tooling during the Mobilize Phase Operating Model Workstream with exception to the additional requirement of the application.

3. Document the wave group application cloud operating model requirement changes as part of the implementation/system documentation if there are changes during the implementation phase.
#### Acceptance Criteria
1. Successful implementation of wave group application cloud operating model requirements.
2. Successful documentation of wave group application cloud operating model requirements during implementation phase.
## Task 3: Subtask 8: Implement Wave Group Application Security and Compliance Requirements
#### Description
1. Leverage the wave group application design documentation to implement the security and compliance requirements to support the migration and operations on AWS.

2. Ensure the security and compliance requirements implementation covers the below areas for the wave group application's AWS services, operating system and application/database based on the defined cloud security strategy under the security, risk and compliance workstream :-

* Infrastructure Protection
* Data Protection
* Incident Detection and Response
* Identity Access and Management
* Security Controls
* Workload Specific Requirements

   This task will mainly involve the leverage of the defined security and compliance processes, policies, controls and AWS Services/partner tooling during the Mobilize Phase Security and Compliance Workstream with exception to the additional requirement of the application.

3. Leverage the Migration Security Requirements (MSR) checks as guidance when implementing the security. 

4. Security validation will be conducted as part of the validation step.

5. Document the wave group application security and compliance requirement changes as part of the implementation/system documentation if there are changes during the implementation phase.
#### Acceptance Criteria
1. Successful implementation of wave group application security and compliance requirements
2. Successful documentation of wave group application security and compliance requirements during implementation phase.
## Task 3: Subtask 9: Migrate or Build Wave Group Application
#### Description
1. Execute the wave group application migration leveraging the migration strategy and application backlog defined as per the wave group application migration timelines.

2. Leverage the defined migration tools as per the migration strategy to accelerate the wave group application migration.

3. It is recommended to leverage Infrastructure as Code (IaC) to standardize the build of the application requirements from AWS Service, networking, security and operating model standpoint.
#### Tools
AWS Database Migration Service (DMS)
#### Tools
AWS Datasync
#### Tools
AWS Application Migration Service (MGN)
#### Acceptance Criteria
1. Successful build or migration of the wave group application workload as per the defined migration strategy.
## Task 3: Subtask 10: Wave Group Application MAP Tagging
#### Description
1. Leverage the MAP Tagging Process defined in the Planning and Governance Workstream to tag all wave group application workload that had successfully been migrated to AWS.
 
2. Ensure all wave group application workload services that are part of the MAP 2.0 program included services list are tagged.  A list of MAP 2.0 included services can be obtained [here](https://s3-us-west-2.amazonaws.com/map-2.0-customer-documentation/included-services/MAP_Included_Services_List.pdf).

3. Ensure to only tag migrated workloads that are part of the MAP 2.0 program scope. 

#### Tools
MAP Tagging Documentation
#### Acceptance Criteria
1. Successful MAP tagging of migrated wave group application workload onto AWS.
## Task 3: Subtask 11: Wave Group Application Dependencies Integration
#### Description
1. Leverage the wave group application AWS architecture design/implementation documentation as a guide to perform application integration.

2. The wave group application will need to be integrated with the below 4 dependencies to ensure successful functionality and operations on AWS :-
*  **Intra application integration** - integration within components/tier of the application.
* **Inter application integration** - integration with other internal or external applications.
*  **Operating Model integration** - integration with operating model services such as monitoring, logging, patch management, authentication, deployment, service management, alerting, configuration management, backup, domain name services.
*  **Security and Compliance integration** - integration with security and compliance services to ensure application level security and platform level security.

3. Raise change management request to execute the above integration or integration change requirements.

4. Executed integration should be validated under the wave group application migration validation activity for the below area :- 
*  Connectivity
*  Functionality
*  Performance

5. All changes to the integration requirements must be documented under the architecture/implementation documentation.
#### Acceptance Criteria
1. Successful wave group application integration execution.
2. Successful documentation of wave group application integration requirement changes.
## Task 3: Subtask 12: Wave Group Application Validation
#### Description
1. Wave group application migration validation should include the below validation areas :-
*   Functional and non functional validation.
*   Integration validation.
*   Performance validation.
*   Pen-test / vulnerability assessment / security validation.

2. UAT and SIT must cover the functional validation, integration validation and Performance Validation.

3. Post UAT and SIT a security validation is highly recommended to ensure pilot application is configured following security best practices on AWS Cloud.

4. All validation should follow the below process :-
* Wave group application test script definition based on the required test cases per application.
* Wave group application test schedule , resource/people requirements, and tooling requirements definition.
* Wave group application testing tooling selection and implementation.
* Pilot migration workload testing execution following the defined schedule , people and test script.
* Wave group application test result documentation into the implementation documentation. 

5.  Leverage the [AWS Development and Test](https://docs.aws.amazon.com/whitepapers/latest/development-and-test-on-aws/testing-phase.html), [load testing application ](https://docs.aws.amazon.com/prescriptive-guidance/latest/load-testing/welcome.html), [functional and non-functional testing ](https://docs.aws.amazon.com/wellarchitected/latest/devops-guidance/functional-testing.html) and [security testing](https://docs.aws.amazon.com/wellarchitected/latest/devops-guidance/security-testing.html) prescriptive guidance and documetation as reference when executing the validation.

6.   The wave group application testing execution will repeat if requirements unmet post configuration changes until all configuration are met.
#### Tools
Prowler
#### Tools
AWS Distributed Load Testing
#### Tools
Service Screener
#### Tools
AWS Self-Service Security Assessment
#### Tools
AWS Trusted Advisor
#### Acceptance Criteria
1. Successful validation of the migrated wave group application workloads.
2. Successful documentation of the migrated wave group application workloads test results into the implementation document.
## Task 3: Subtask 13: Wave Group Application Well Architected Review
#### Description
1. It is highly recommended to execute the Well Architected Framework Review for all wave group applications migrate onto AWS.

2. Leverage the [AWS Well-Architected documentation](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) and  [How to perform Well-Architected Framework Review](https://aws.amazon.com/blogs/mt/how-to-perform-a-well-architected-framework-review-part1/) as requirements and process reference when executing the Well Architected Framework Review.

3. Execute the Well Architected Review leveraging the [Well Architected Review Tool](https://aws.amazon.com/well-architected-tool/) through a workshop.

4. Review the Well Architected Review findings and build a remediation plan. Ensure the findings and remediation plan is documented under the wave group application implementation documentation.

5. Present the remediation plan to the wave group application migration team.

6. Work with the wave group application migration team to remediate the findings from the Well Architected Review.

7. Ensure all findings are addressed before handing over the application to the customer for sign-off and operations.

8. In a scenario the wave group application migration team chooses not to address the findings, the risk will need to be accepted by the stakeholders through a risk acceptance sign-off.  Do not handover unless this process is met.
#### Tools
AWS Well-Architected Framework
#### Acceptance Criteria
1. Successful completion of the well architected review and remediation for selected wave group application migration workload.
## Task 3: Subtask 14: Wave Group Application Implementation and Runbook Documentation
#### Description

**Implementation Documentation**

1. Document the wave group application implementation areas below into the implementation documentation.
*  Application specification
*  infrastructure specification
*  Architecture design
*  AWS service and application configuration
*  Network requirements and implementation details
*  Security and compliance requirements and implementation details
*  Operating model service requirement and implementation details
*  Service level agreement (SLA) and Operational level agreement (OLA)
*  Resiliency and Business continuity
*  Licensing
*  Application deployment and update details
*  Well Architected Review report and remediation updates.

2. Leverage the Migration Portfolio Assessment (MPA) data collection template input metrics to provide guidance to the details required for the application, infrastructure and database specification documentation.

**Operational Runbook**

1. Document the operational runbook for the wave group application to outline process, steps and guidance on the management of the below operational areas :- 

* Monitoring & Event Management
* Patch Management
* Logging
* Backup / Continuity Management
* Deployment - CI/CD
* AMI Management
* Tag Management
* Automation
* Inventory Management
* Service / Incident Management
* Service Catalogue
* Financial Management
* Configuration Management
* Change Management
* Account and User Management
* License Management

2. This operational runbook will be leveraged by the operations team to execute and govern the operations on AWS. 

3. The operational runbook should be handed over to the operation team during the knowledge transfer and operational training sessions. It is also recommended to provide continuous operational support as per defined in the warranty period agreement to ensure operational governance and success.
#### Acceptance Criteria
1. Successful definition and documentation of implementation documentation and operational runbook for wave group application workloads.
## Task 3: Subtask 15: Wave Group Migration Sign off and Acceptance Document
#### Description
1. Obtain customer acceptance and sign off for each wave group migration completion as per the defined milestones using standardize defined templates or an email template. 

2. Ensure customer is aware of the implementation areas, risk acceptance and post migration or modernisation support prior to sign-off.

3. For Partners, ensure to submit the AWS APN Customer Feedback to the customer to obtain their feedback on the engagement.
#### Acceptance Criteria
1. Successful customer sign-off and acceptance of wave group application migration completion by milestone.
2. Obtained and documented customer feedback.
## Task 3: Subtask 16: Wave Group Application - Migration or Modernization (ModAx) Experience-Based Acceleration
#### Description
1. Evaluate the requirements to execute a Migration or Modernization (ModAx) Experience Based Acceleration (EBA) to accelerate the assessment, design, execution, validation and integration of the pilot application workloads. 
2. Leverage the [Experience-based acceleration engagement delivery kit](https://apg-library.amazonaws.com/content/c33bd17e-da06-4701-8bd4-30e174c551a0) when evaluating, planning and executing the Platform EBA.
3. Leverage the AWS Customer Solution Manager (CSM) and AWS Solution Architect support during the planning and executing of the EBA.
#### Tools
Experience-Based Acceleration Engagement Delivery Kit
#### Acceptance Criteria
1. Successful Migration or Modernization (ModAx) Experience Based Acceleration (EBA) planning and execution.
2. Accelerated completion of the wave group application migration and modernization in the Migrate and Modernize Phase.