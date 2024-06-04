
# Module: Operations-Support - Operate
## Task 1: IT Service Management
#### Description
Management of end-to-end delivery of IT services. Including all activities involved in designing, creating, delivering, supporting and managing the lifecycle of IT Services.

## Task 1: Subtask 1: Establish Service Management Framework
#### Description

The purpose of this task is to understand all components within the overall service management framework, post go live, and to establish a process to cover all the following areas with clear understanding where SAP and/or Partner can play a role to support.

Procedure:

1. Review details of different areas of service management:
* Monitoring - Monitor systems and processes and observe to detect changes over time. This includes business applications, processes, KPIs, technical platform, objects, events, and tickets. Reference task Monitor the New System and Operate the New Solution for more details.
* Incident Management - Manage unplanned event or service interruption by restoring the service to its operational state and minimizing effects on end users. Reference Incident Management task for more details.
* Change Management - Seek to minimize the risk associated with Changes, including changes to the IT infrastructure, processes, documents, supplier interfaces, etc. Customers will drive the change however in some cases SAP may execute against the change request as part of the service delivery model. Reference OCM Continuous Change Management Activities and task Establish Change Request Management Process for details.
* Problem Management – Reference Manage Problem task for more details.
* Service Catalogue & Service Requests - The Service catalogue is a centralized database of information about active IT service offerings. Managing Service requests supports an agreed quality of services, by way of handling user-initiated requests in an efficient and user-friendly manner. Reference task Access SAP Support Service task when creating request to SAP.
* Service Delivery Management - Ensures that services are being seamlessly delivered. This includes managing holistic oversight of overall solution on behalf of the business, rectifying reliability issues, monitoring progress, tracking KPIs, and managing budgets. Reference tasks in Identify Innovation and Growth Opportunities for more details on planning the delivery of new or updated features to business users.
* Test Management - Reference task on Periodically Update your SAP System and Initiate a New Innovation Cycle on more details regards regression testing and testing of new improvements.
* Security & Compliance - SAP informs Customer of critical security notes and changes that are required within the SAP application and from the operating system down. The customer is responsible for then raising the ticket to get the change applied within their agreed slot.
* Release and Deployment Management - Plan, schedule and control the movement of minor or major releases through the landscape to live environments. Reference Upgrade your SAP system and Initiate a New Innovation Cycle task for more details.
2. Form operation team to establish processes as described in the referenced tasks.
## Task 1: Subtask 2: Access SAP Support Service
#### Description
The purpose of the task is to find support and services provided by SAP when there is a need.

SAP for Me is the starting point to find support and services that are available. The Services and Support Dashboard has various apps that allow customer search for Knowledge Based Articles and Notes (KBAs) before logging a case to contact SAP including Expert Chat or creating service request. In the More Resources tab there is My Trust Center that consolidates a customer's view of security and privacy measure, and compliance checks from [SAP Trust Center](https://www.sap.com/about/cloud-trust-center.html).

Under Systems and Provisioning Dashboard, customer can see their system(s) status and availability, and subscribe notifications to receive timely updates and remain informed. From Finance and Legal dashboard, customer can access agreement documents (i.e. SLA, Service Level Agreement).

Customer can also check out SAP Support Offerings and Programs to engage experts from SAP to run the solution and support end users.

Procedure:

Access SAP for Me.
Search Support Knowledge.
Go to various different Dashboards for Legal, Service, Support, Systems related customer specific information.
Log Case using Get Support app.
## Task 2: Enterprise Support
#### Description
SAP Enterprise Support, cloud editions offering is a foundational success plan included with any cloud subscription from SAP. It supports successful cloud adoption across the Customer enterprise. Enterprise Support is a service that provides proactive support in addition to all features of SAP Standard Support services. These proactive support services encompass tools, processes, and services that enable continuous improvement, holistic application lifecycle management for continuous innovation, business and operational process improvements, and levers to address the total cost of operation TCO.

## Task 3: Ongoing System Operations
#### Description

The purpose of this deliverable is to perform routine actions to ensure that the system is running as expected by leveraging the established support and operation processes.
## Task 3: Subtask 1: Operate the New Solution
#### Description
The purpose of the task is to monitor and track business processes running in the newly implemented Cloud ERP solution to ensure that customer is operating per the target state defined by the project.

Procedure:

1. Setup business process analytics and mining capability for the new solution.
2. Align monitoring cadence with stakeholders.
3. Review, analyze and compare data, ie. number of documents, lead times, automation rates, and other Process Performance Indicators on regular basis.
4. Analyze on conformance to defined business processes based on business process data.
5. Communicate results and findings to stakeholders and business process owners on regular basis.
## Task 3: Subtask 2: Verify User Authorizations / Classification in Production Systems
#### Description
Verify User Authorizations / Classification in Production Systems
The purpose of this task is to verify and update user authorizations, roles, and user classifications to ensure compliant use.

Prerequisite:

All SAP users are setup in all productive systems with the related roles and authorizations.
Delete users or change validity dates for users no longer in scope.
Apps Used:

System Measurement Program (Transaction USMM)
System Measurement Details in SAP for Me
SAP for Me – Private Cloud Consumption
Procedure:

**For SAP S/4 HANA Cloud Core productive systems**

1. Select correct pricelist in the system measurement program (transaction USMM) to activate the correct user types for classification.
Example:
06 - SAP S/4HANA Private Cloud Edition or
07 - SAP ERP Private Cloud Edition
2. Implement 3113382 - Authorization-based SAP S/4HANA User Simulation / FUE Projection in your core systems.
3. Run the report SLIM_USER_CLF_HELP with the most recent PCE / RISE ruleset attached to the note. The ruleset determines based on authorization objects of the core, the resulting use types for SAP Private Cloud editions.
4. Understand which roles and authorizations drive the resulting classification.
5. Please note: If there are users in your SAP S/4HANA Cloud core systems that only use engines and no further core functionality, please classify them manually as SAP S/4HANA Cloud Technical Engine Use.
6. Review results and adjust role and authorization concept where required.

**For Engine-Only / Extra Stack productive systems (if applicable)**

Assign all engine users manually to the following use type:
SAP S/4HANA Cloud Technical Engine Use.

## Task 3: Subtask 3: Monitor the New System
#### Description
The purpose of the task is to monitor the S/4HANA system and clean up non-business data to ensure optimal system performance. Following are a few examples:

* Critical batch jobs where job execution fails, job runs too long, scheduled job does not run, or there is a delay of start.
* IDocs in ERROR or BACKLOG status, integration exceptions, or interface response time.
* URL & certificate availability.
* Short dumps (i.e. ST22), system logs (i.e. SM21), backups and queues.
* Housekeep technical logs that are no longer required.
* Event notifications received and follow up actions.
* Manage business data growth by archiving.

SAP execute standard, optional and additional monitoring services related to Technical Platform as per Roles & Responsibilities service catalogue, for example, monitoring database for technical issues, monitor table growth to proactively prevent operational issues. Partner executes all technical monitoring in clients other than 000.

SAP trigger event notification to customer/partner in form of an email and also update the customer support portal (SAP for Me) in case of any Technical Platform (e.g. Infrastructure, Database, NetWeaver) related events.

Enterprise Cloud Support (ECS) offers standard 24/7 monitoring of Production systems and Customers have access to infrastructure Monitoring dashboards to see system health and alerts.

SAP Cloud Delivery Manager (CDM) attend service management, service review meetings regularly and share reports on SLA, capacity utilization, system availability, etc.
## Task 3: Subtask 4: Continuously Optimize IT Operations
#### Description
The purpose of this task is to continuously improve IT operations (e.g. via automation, or switching from a re-active to a pro-active operations approach). [Customer COE and CIO Guides](https://support.sap.com/en/offerings-programs/ccoe/cio-customer-coe-guides.html) in [Customer Center of Expertise](https://support.sap.com/support-programs-services/ccoe.html) portal has more details on improvement options.

One approach to improve IT operations is to set up an Advanced Customer COE. The advanced certification for Customer COEs covers the full spectrum of SAP solution operations. Based on the SAP standards for solution operations and the SAP Activate methodology, a team with advanced certification has integrated quality management in place, bringing transparency to the challenges and issues faced by the organization as a whole. This is paramount for mission critical operations. Visibility, alignment, and a common understanding of those top issues are enabled through the center's ability to maintain a single source of truth - one central area where everything is tracked and from which all information flows.

Procedure:

1. Review [What a Customer COE Should Know About Incident Managent](https://support.sap.com/en/offerings-programs/ccoe/cio-customer-coe-guides.html) accelerator to also get an overview of various SAP support channels that are available.
2. Continuously improve IT operations for maximum efficiency by leverage support and services provided by SAP. Reference task Access SAP Support Service for details.
3. Access [SAP Enterprise Support Report Reporting](https://launchpad.support.sap.com/#/customerinsight360) Cockpit to refine indicators, improve and optimize the overall system landscape.
4. Use [Early Watch Alert](https://support.sap.com/support-programs-services/services/earlywatch-alert.html) workspace tool to prevent errors and problems.
5. Leverage service from [Incident Quality](https://launchpad.support.sap.com/#/incidentquality) dashboard to check the quality of incidents to optimize the process.
## Task 4: Incident and Problem Management
#### Description
The purpose of this deliverable is to enable a centralized and common incident and issue message processing for multiple organization levels. The process offers a communication channel with all relevant stakeholders of an incident, including business users, customer-side SAP experts, SAP Service & Support, and Partner Support employees.
## Task 4: Subtask 1: Manage Incident
#### Description
This task aims to establish a process to manage incidents to restore service, including but not limited to issue detection, incident creation, prioritization/classification, investigation and analysis, remediation, remediation verification, incident closure, and postmortem analysis.

Procedure:

1. Create a single point of contact to capture demand for incidents for end users in the organization.
2. Perform initial categorization (SAP vs. Non-SAP) and prioritization
3. Analyze the problem and try to resolve it. If unresolved, then route the incident to the correct team within SAP. Note: Functional knowledge is needed for this activity.
4. Create a case (Incident) - Log the case on the SAP for Me with all required information.
5. SAP and the customer work together to understand the issue and identify possible workarounds and permanent fixes. If the incident is on the Technical Platform, then SAP (ECS) will resolve it. If it is a Product related issue (standard code), then SAP product support can get involved.
6. Critical Incident Resolution - This is the process that is followed for P1 critical incidents. SAP and the customer work together to understand the issue, and identify possible workarounds and permanent fixes. If the incident is on the Technical Platform, then SAP (ECS) will resolve it. If it is a Product related issue (standard code), then SAP product support can get involved.
7. Close the ticket.
## Task 4: Subtask 2: Manage Problem
#### Description
The purpose of the task it to identify problem and resolve in timely manner.

Procedure:

1. Identify problem - Identify and agree on a problem statement on the basis of recurring issues.
2. Create Problem Ticket - Administrative function to physically log the problem ticket.
3. Problem Resolution - SAP and customer work together to identify the root cause, identify possible workarounds or a solution.
4. Application Layer - Partner to investigate and resolve any problems related to the application layer.
5. Technical Platform - If the problem is on the Technical Platform then SAP (ECS) will investigate and resolve. If it’s a Product related problem (standard code) then SAP product support can get involved.
6. Close the problem ticket.

## Task 5: Identify Innovation and Growth Opportunities
#### Description
The purpose of this deliverable is to improve and simplify your new solution to realize maximum benefit. On the one hand, this requires the periodic update, by implementing feature and support packs, to bring the latest innovations from SAP into your solution. On the other hand, a new planning cycle needs to be initiated together with your peers from the business units, to identify innovations which are mostly required.

SAP supports customer post Go-Live towards the Intelligent Enterprise. Customer is notified of potential capacity issues and should engage SAP Customer Success Partner to determine demands, understand risks and plan for future projects together with SAP in continuous transformation journey.
## Task 5: Subtask 1: Periodically Update your SAP System
#### Description
The purpose of this task is to evaluate new features, plan and execute frequent updates to keep SAP S/4HANA system current in order to support continuous business innovation.

SAP delivers one major release and two minor ones each year. Minor releases are the first two support package stacks, known as Feature Package Stack (i.e FPS01 FPS02). Support Package Stacks three and onwards (ie. SPS03, SP04, etc) are corrections only for mainstream maintenance and will last for five years for the respective major release.

Release upgrade should be planned and executed by customer. There are two approaches in upgrade: Technical and Functional. Technical approach focusing on updating software with minimum mandatory updates in configuration and custom code. Functional approach not only includes the technical aspect but more importantly deploys new business functionality as well, which involves more testing and user adoption efforts.

It is recommended for customer to take advantage of the once-a-year entitlement of the software upgrade offered by SAP and do the minimum changes required in Technical upgrade approach. This helps customer stay current as dictated by the SAP S/4HANA maintenance schedule, and with corrections and improvements that stabilize the system, improve performance, ensure the security of the system.

SAP perform the technical execution of all upgrades and patching to client 000. Customer or Partner performs the functional upgrade and patching activities on the application layer, ie. custom code remediation, notes implementation, simplification as per simplification lists etc.

While SAP have accountability in execution of certain changes, Customer owns the overall release management for all activities. SAP should be informed and involved to understand all customer releases and to initiate the approval process with Customer for any SAP releases.

Procedure:

1. Check [Schedule for Release and Maintenance ](https://support.sap.com/en/release-upgrade-maintenance.html)accelerator from support portal for timeline on new releases, feature packages and support packages.
2. Use [SAP S/4HANA What’s New Viewer](https://help.sap.com/doc/474a13c5e9964c849c3a14d6c04339b5/100/en-US/8880de6dbfb94ea3b0de1f26b40816dc.html) to evaluate new features for the selected release(s) and feature package(s).
3. Reference the [Upgrading SAP S/4HANA - How, Why, and Best Practice](https://www.sap.com/documents/2020/06/94ca0995-9d7d-0010-87a3-c30de2ffd8ff.html) accelerator to determine the desirable upgrade path and choose between a minimum Technical approach or Functional approach of an improvement project.
4. Reference the SAP S/4HANA Upgrade and Product Integration Roadmap in Roadmap Viewer to plan and execute the upgrade project.
5. Create Service Request in SAP for Me in Services & Support dashboard to request the software update of the selected release and feature package as needed.

## Task 6: ISV Spotlight: Ktern.AI
#### Description
Leverage KTern.AI data-driven analysis of SAP S/4HANA systems and determine the indicative to-be S/4HANA process hierarchy (L1 - LoB, L2 - Process group, L3 - Scope item, L4 - Scope item variant, L5 - Process step) with respective benefits, process model, Fiori apps, relevancy score & top business users based on AS-IS usage. Take advantage of clean core insights from KTern.AI to understand on how to redefine the process with industry standard scope items with a clean core transition approach.

Leverage KTern.AI autonomous enterprise release impact mining to drive continuous SAP S/4HANA releases with complete visibility on process, technical changes with usage, root cause, top impacted users and orchestrate controlled, risk-aware releases. Connect to the DevOps tools, understand the right testing portfolio, drive intelligent regression and run proactive test scoping. This helps reduce business disruptions with digitalized simulation of release impact with test fits and gaps, leading to streamlined OCM and faster DevOps.
