
# Module: Migration and Modernization Experience Workstream
## Task 1: Pilot Migration and Modernization Planning and Execution
#### Description
1. Plan the migration of the identified pilot application workloads during the detail discovery and planning workstream.

2. Execute the migration of the identified pilot application workloads.

3. Pilot application workload documentation.

4. Pilot application workload knowledge transfer and handover.

5. Pilot application workload sign off and acceptance.
#### Acceptance Criteria
1. Successful pilot application discovery validation, architecture design, backlog definition.
2. Successful pilot application migration strategy alignment and tooling definition.
3. Successful pilot application cutover and rollback plan definition.
#### Acceptance Criteria
4. Successful pilot application networking, operating model, security and compliance requirements setup.
5. Successful pilot application build or migration, integration and validation.
6. Successful pilot application MAP tagging.
#### Acceptance Criteria
7. Successful completion of the Well Architected Review for at least 1 application. 
8. Successful pilot application implementation and runbook documentation.
9. Successful pilot application migration sign-off and acceptance documentation.
## Task 1: Subtask 1: Pilot Application Discovery Validation
#### Description
1. Conduct validation workshop with the below customer stakeholders teams that manages the selected pilot application :-
*  Infrastructure team
*  Application/Developer Team
*  QA Team
*  Operations Team
*  Security and Compliance Team
*  Product Manager
    This team is also known or reffered to as the Application Migration Team.

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


3. Evaluate the pilot application requirements and current state for the need to introduce AWS accelerators.  There are two accelerators that can be leveraged in the Migration and Modernization Experience Phase :-
* Migration Experience-Based Acceleration (EBA) for migration
* Modernization (ModAx) Experience-Based Acceleration (EBA) for modernization

	The Experience-Based Acceleration (EBA) can help accelerate the planning, migration and modernization execution and validation of the pilot application workloads. The Experience-Based Acceleration (EBA) must include definition and building repetitive mechanism that should be leveraged to accelerate application wave group migration in the Migrate and Modernize Phase. 


4. Update the data collected above into the data collection sheet.  These data will be used to refine the pilot application design.
#### Acceptance Criteria
1. Successful data collection validation of pilot application specification and requirement.
## Task 1: Subtask 2: Pilot Application Design
#### Description
1. Re-design is only required if there are changes to the pilot application data collection.
 
2. Leverage the updated data collection sheet to refine the pilot application target architecture on AWS with reference to the design baseline standards.

3. Ensure the below areas are taken in to consideration when refining the  target state design  :-
*  Application roadmap requirements
*  Application drivers
*  Application infrastructure and performance requirements
*  Application connectivity, dependency and integration requirements
*  Application security and compliance requirements
*  AWS Service usage and availability

4. Leverage [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) as AWS Best Practice reference when designing the target architecture .  

5. Confirm pilot application architecture design with the Application Migration Team.

6. Document the refined pilot application target architecture diagram in the implementation documentation.

#### Tools
AWS Well-Architected Framework
#### Acceptance Criteria
1. Successful refinement of Pilot Application target architecture.
2. Successful confirmation of the refined Pilot Application target architecture diagram with the Application Migration Team.
## Task 1: Subtask 3: Pilot Application Backlog Definition
#### Description
1. Work with the Application Migration Team to define the steps/backlog to successfully migrate the pilot application to AWS.

2. The migration steps should cover 
*  **Pre-migration requirements** - steps required to make the changes to pilot application and support the pilot application functionality in the cloud.
*  **Migration/modernization requirements** - steps required to migrate / modernize the pilot application inclusive tooling deployment, tooling configuration, validation, cutover plan and rollback.
*  **Post Migration requirements** - steps required during post migrations to ensure pilot application integration, validation and documentation.

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
*  Pilot application / server configuration
*  Pilot spplication integration / re-pointing
*  Security and compliance configuration and integration
*  Operating model component configuration and integration
*  Post migration test/validation
*  Pilot Application documentation

#### Acceptance Criteria
1. Successful documentation of pilot application backlog covering pre-migration, migration and post-migration requirements.
2. Successful buy-in of task requirements and resource allocation from Application Migration Team.
## Task 1: Subtask 4: Pilot Application Migration Strategy and Tooling Definition
#### Description
1. Re-evaluate or re-align the AWS 7R migration strategy defined in the Detail Application Assessment and Portfolio Analysis workstream for the pilot application component or tier taking into consideration the below areas :-
*  Changes in the pilot application business and technical requirements
*  Application roadmap and driver
*  Selected AWS services for hosting the pilot application component in the target architecture design. 

2. Leverage the [Application Portfolio Assessment guide for AWS Cloud Migration](https://docs.aws.amazon.com/prescriptive-guidance/latest/application-portfolio-assessment-guide/iterating-7-rs-migration-strategy-selection.html) and [Migration Pattern by Workload](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/migration-migration-patterns-by-workload-pattern-list.html) prescriptive guidance as best practice reference when executing migration strategy alignment to the respective pilot application component/tier.

3. It is recommended to leverage the below general approach and services in most migration scenarios unless there are specific requirements identified during the discovery :-
*   Application Rehost onto AWS  - AWS Application Migration Service (MGN) applications.
*   Database Rehost onto AWS -  Database Native Tool or AWS Database Migration Service (DMS).
*   Homogeneous Database Replatform onto AWS -  Database Native Tool or AWS Database Migration Service (DMS).
*   Heterogeneous Database Replatform onto AWS -  AWS Schema Conversion Tool, AWS Database Migration Service (DMS).
*   Large Data migration - AWS Datasync.

	*Note : Introduce AWS Partner Tooling which can be obtained from the [AWS Marketplace](https://aws.amazon.com/marketplace) when AWS Services or Native tools are unable to meet complex or specific requirements.*

4. Align migration tool to the selected application migration strategy to allow migration or modernisation execution. 
#### Acceptance Criteria
1. Pilot application components assigned and aligned with an AWS Migration Strategy. 
2. Selected migration strategy has a defined tool/service assigned to execute the migration or modernization.
## Task 1: Subtask 5: Pilot Migration Cutover Plan Definition
#### Description
1.  Define cutover plan for the pilot application workloads.

2.  The defined cutover plan must include a rollback plan in case the cutover is not successful. The rollback plan needs to be documented in the migration plan and timelines.

3.  Validate the cutover plan with Application Migration Team. 

4.  Ensure the cutover plan activities are documented as part of the migration plan and timelines.

5.  Leverage the [AWS Cutover Prescriptive Guidance](https://docs.aws.amazon.com/prescriptive-guidance/latest/best-practices-migration-cutover/overview-cutover-phase.html) as reference when building the cutover plan. 
#### Acceptance Criteria
1. Successful definition and documentation Pilot Migration cutover plan.
2. Successful definition and documentation Pilot Migration rollback plan.
3. Successful alignment of Pilot Migration cutover plan with Migration Application Team.
## Task 1: Subtask 6: Implement Pilot Application Network Requirements
#### Description
1. Leverage the pilot application design documentation to implement the network requirements to support the migration and operations on AWS.

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

5. Document the pilot application network requirement changes as part of the implementation/system documentation if there are changes during the implementation phase.
#### Tools
Network Access Analyzer
#### Acceptance Criteria
1. Successful implementation of pilot application network requirements.
2. Successful completion of network validation.
3. Successful documentation of pilot application network requirements during implementation phase.
## Task 1: Subtask 7: Implement Pilot Application Operating Model Requirements
#### Description
1. Leverage the pilot application design documentation to implement the cloud operating model requirements to support the migration and operations on AWS.

2. Ensure the cloud operating model requirements implementation covers the below areas for the pilot application based on the defined strategy under the operating model workstream :-

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
   
   This task will mainly involve the leverage of the defined operating model processes and AWS Services/partner tooling during the Operating Model Workstream with exception to the additional requirement of the application.

3. Document the pilot application cloud operating model requirement changes as part of the implementation/system documentation if there are changes during the implementation phase.
#### Acceptance Criteria
1. Successful implementation of pilot application cloud operating model requirements.
2. Successful documentation of pilot application cloud operating model requirements during implementation phase.
## Task 1: Subtask 8: Implement Pilot Application Security and Compliance Requirements
#### Description
1. Leverage the pilot application design documentation to implement the security and compliance requirements to support the migration and operations on AWS.

2. Ensure the security and compliance requirements implementation covers the below areas for the pilot application's AWS services, operating system and application/database based on the defined cloud security strategy under the security, risk and compliance workstream :-

* Infrastructure Protection
* Data Protection
* Incident Detection and Response
* Identity Access and Management
* Security Controls
* Workload Specific Requirements

   This task will mainly involve the leverage of the defined security and compliance processes, policies, controls and AWS Services/partner tooling during the Security and Compliance Workstream with exception to the additional requirement of the application.

3. Leverage the Migration Security Requirements (MSR) checks as guidance when implementing the security. 

4. Security validation will be conducted as part of the validation step.

5. Document the pilot application security and compliance requirement changes as part of the implementation/system documentation if there are changes during the implementation phase.
#### Acceptance Criteria
1. Successful implementation of pilot application security and compliance requirements
2. Successful documentation of pilot application security and compliance requirements during implementation phase.
## Task 1: Subtask 9: Migrate or Build Pilot Application
#### Description
1. Execute the pilot migration leveraging the migration strategy and application backlog defined as per the pilot migration timelines.

2. Leverage the defined migration tools as per the migration strategy to accelerate the pilot application migration.

3. It is recommended to leverage Infrastructure as Code (IaC) to standardize the build of the application requirements from AWS Service, networking, security and operating model standpoint.
#### Tools
AWS Datasync
#### Tools
AWS Application Migration Service (MGN)
#### Tools
AWS Database Migration Service (DMS)
#### Acceptance Criteria
1. Successful build or migration of the pilot application workload as per the defined migration strategy.
## Task 1: Subtask 10: Pilot Application MAP Tagging
#### Description
1. Leverage the MAP Tagging Process defined in the Planning and Governance Workstream to tag all pilot application workload that had successfully been migrated to AWS. 

2. Ensure all pilot application workload services that are part of the MAP 2.0 program included services list are tagged.  A list of MAP 2.0 included services can be obtained [here](https://s3-us-west-2.amazonaws.com/map-2.0-customer-documentation/included-services/MAP_Included_Services_List.pdf).

3. Ensure to only tag migrated workloads that are part of the MAP 2.0 program scope. 

#### Tools
MAP Tagging Documentation
#### Acceptance Criteria
1. Successful deployment of MAP tagging for migrated pilot application workload on AWS.
## Task 1: Subtask 11:  Pilot Application Dependencies Integration
#### Description
1. Leverage the pilot application AWS architecture design/implementation documentation as a guide to perform application integration.

2. The pilot application will need to be integrated with the below 4 dependencies to ensure successful functionality and operations on AWS :-
*  **Intra application integration** - integration within components/tier of the application.
*  **Inter application integration** - integration with other internal or external applications.
*  **Operating Model integration** - integration with operating model services such as monitoring, logging, patch management, authentication, deployment, service management, alerting, configuration management, backup, domain name services.
*  **Security and Compliance integration** - integration with security and compliance services to ensure application level security and platform level security.

3. Raise change management request to execute the above integration or integration change requirements.

4. Executed integration should be validated under the pilot application migration validation activity for the below areas :- 
*  Connectivity
*  Functionality
*  Performance

5. All changes to the integration requirements must be documented under the architecture/implementation documentation.
#### Acceptance Criteria
1. Successful pilot application integration execution.
2. Successful documentation of pilot application integration requirement changes.
## Task 1: Subtask 12: Pilot Application Validation
#### Description
1. Pilot application migration validation should include the below validation areas :-
*   Functional and non functional validation.
*   Integration validation.
*   Performance validation.
*   Pen-test / vulnerability assessment / security validation.

2. UAT and SIT must cover the Functional Validation, Integration Validation and Performance Validation.

3. Post UAT and SIT a Security Validation is highly recommended to ensure pilot application is configured following security best practices on AWS Cloud.

4. All validation should follow the below process :-
* Pilot migration workload test script definition based on the required test cases per application.
* Pilot application test schedule , resource/people requirements, and tooling requirements definition.
* Pilot application testing tooling selection and implementation.
* Pilot application testing execution following the defined schedule , people and test script.
* Pilot application test result documentation into the implementation documentation. 

5.  Leverage the [AWS Development and Test](https://docs.aws.amazon.com/whitepapers/latest/development-and-test-on-aws/testing-phase.html), [load testing application ](https://docs.aws.amazon.com/prescriptive-guidance/latest/load-testing/welcome.html), [functional and non-functional testing ](https://docs.aws.amazon.com/wellarchitected/latest/devops-guidance/functional-testing.html) and [security testing](https://docs.aws.amazon.com/wellarchitected/latest/devops-guidance/security-testing.html) prescriptive guidance and documetation as reference when executing the validation.

6.   The Pilot migration workload testing execution will repeat if requirements unmet post configuration changes until all configuration are met.
#### Tools
Service Screener
#### Tools
Prowler
#### Tools
AWS Trusted Advisor
#### Tools
AWS Self-Service Security Assessment
#### Tools
AWS Distributed Load Testing
#### Acceptance Criteria
1. Successful validation of the pilot migrated workloads.
2. Successful documentation of the pilot migrated workloads test results into the implementation document.
## Task 1: Subtask 13: Pilot Application Well Architected Review
#### Description
1. Select at least 1 pilot migration workload to execute the Well Architected Framework Review. It is highly recommended to execute the Well Architected Framework Review for all applications migrate onto AWS.

2. Leverage the [AWS Well-Architected documentation](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) and  [How to perform Well-Architected Framework Review](https://aws.amazon.com/blogs/mt/how-to-perform-a-well-architected-framework-review-part1/) as requirements and process reference when executing the Well Architected Framework Review.

3. Execute the Well Architected Review leveraging the [Well Architected Review Tool](https://aws.amazon.com/well-architected-tool/) through a workshop.

4. Review the Well Architected Review findings and build a remediation plan. Ensure the finding and remediation plan is documented under the pilot application implementation documentation.

5. Present the remediation plan to the pilot application migration stakeholders.

6. Work with the pilot application migration team to remediate the findings from the Well Architected Review.

7. Ensure all findings are addressed before handing over the application to the customer for sign-off and operations.

8. In a scenario the pilot application migration team chooses not to address the findings, the risk will need to be accepted by the stakeholders through a risk acceptance sign-off.  Do not handover unless this process is met.
#### Tools
AWS Well-Architected Framework
#### Acceptance Criteria
1. Successful documentation of the well architected review details into the pilot application migration  implementation documentation.
2. Customer stakeholder sign-off on the well architected review results.
## Task 1: Subtask 14: Pilot Application Implementation and Runbook Documentation
#### Description

**Implementation Documentation**

1. Document the pilot migration implementation areas below into the implementation documentation.
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

1. Document the operational runbook for the pilot application to outline process, steps and guidance on the management of the below operational areas :- 

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
1. Successful definition and documentation of implementation documentation and operational runbook for pilot application workloads.
## Task 1: Subtask 15: Pilot Migration Sign off and Acceptance Documentation [Partners Only]
#### Description
1. The MAP for Distribution Customer Sign-Off Template consists of two sections :-
* **Section 1:** Project Deliverables & Partner Acknowledgment (All fields required)
* **Section 2:** Customer Acknowledgment (Signature Required) & Satisfaction Survey

2. Partner will complete section 1 and send the MAP Distribution Customer Sign-Off form to the customer. 

3. Customer will acknowledge and confirm the details provided by the Partner and complete section
 
4. Customer will send the MAP Distribution Customer Sign-Off form to the partner. 

5. Partner will leverage the form for MAP fund claim. 
#### Acceptance Criteria
1. Customer acknowledgment of pilot migration and mobilize delivery completion.
2. Successful customer sign-off and acceptance of pilot migration and mobilize delivery.
## Task 1: Subtask 16: Pilot - Migration or Modernization (ModAx) Experience-Based Acceleration
#### Description
1. Evaluate the requirements to execute a Migration or Modernization (ModAx) Experience Based Acceleration (EBA) to accelerate the assessment, design, execution, validation and integration of the pilot application workloads. 
2. Leverage the [Experience-based acceleration engagement delivery kit](https://apg-library.amazonaws.com/content/c33bd17e-da06-4701-8bd4-30e174c551a0) when evaluating, planning and executing the Platform EBA. Work with AWS or AWS Partners to access the EBA engagement delivery kit.
3. Leverage the AWS Customer Solution Manager (CSM) and AWS Solution Architect support during the planning and executing of the EBA.
#### Tools
Experience-Based Acceleration Engagement Delivery Kit
#### Acceptance Criteria
1. Successful Migration or Modernization (ModAx) Experience Based Acceleration (EBA) planning and execution.
2. Accelerated completion of the Migration and Modernization Experience Workstream.