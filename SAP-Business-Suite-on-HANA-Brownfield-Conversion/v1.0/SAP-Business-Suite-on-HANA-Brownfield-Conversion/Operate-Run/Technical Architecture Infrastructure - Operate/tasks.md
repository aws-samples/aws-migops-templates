
# Module: Technical Architecture Infrastructure - Operate
## Task 1: AWS: Enhance observability
#### Description
Identify critical observability patterns in SAP landscape and create plan to implement observability solutions. 

## Task 2: AWS: Review solution guidance for SAP BTP and JRA
#### Description
Review recommendations for leveraging SAP BTP platform and AWS services with baseline solution guidance provided by Joint Reference Architectures Source

#### Tools
SAP Discovery Center
## Task 3: System Availability
#### Description
SAP SLA`s are 99.7% and SAP monitor the systems to meet this SLA.

## Task 4: Technical Performance
#### Description
SAP provides dashboards enabling partners and customers to analyse system performance. When further assistance is needed a ticket could be raised with SAP to perform further investigation.

## Task 5: System Uplifts
#### Description
There may be times when a system uplift is required and the customer can raise this request with SAP and the CDM will manage the commercials and change.

## Task 6: Ongoing System Operations
#### Description
The purpose of this deliverable is to perform routine actions to ensure that the system is running as expected by leveraging the established support and operation processes.
## Task 6: Subtask 1: Operate the New Solution
#### Description
The purpose of the task is to monitor and track business processes running in the newly implemented Cloud ERP solution to ensure that customer is operating per the target state defined by the project.

Procedure:
1. Setup business process analytics and mining capability for the new solution.
2. Align monitoring cadence with stakeholders.
3. Review, analyze and compare data, ie. number of documents, lead times, automation rates, and other Process Performance Indicators on regular basis.
4. Analyze on conformance to defined business processes based on business process data.
5. Communicate results and findings to stakeholders and business process owners on regular basis.
## Task 6: Subtask 2: Review Upcoming Legal Changes
#### Description
The purpose of this task is to review upcoming legal changes, determine the business impact, and plan the next steps to ensure compliance. The legal changes are available in the SAP for Me via the ‘Legal Change Notification’ app. This app should be checked monthly or periodically based on the change frequency of the required countries. Email notifications are also possible.

Procedure:

Review the upcoming legal changes. See the SAP Note 2382863 - How to use the Announcement of Legal Changes application accelerator for additional details.

## Task 6: Subtask 3: Perform Technical Assessment
#### Description

The purpose of this task is to conduct a technical performance review to ensure system performance is not degrading over time due to potential data growth on system's technical performance, availability and request uplifts when needed.

With the collaboration of SAP and SAP's partners, customers have the opportunity to monitor SLAs and system availability throughout the different data centers and retrieve reporting on system availability and performance.

Procedure:

View cloud product availability and maintenance window in [Cloud Availability Center](https://support.sap.com/en/my-support/systems-installations/cac.html) accelerator when applicable.
Access dashboards to analyze system performance. When further assistance is needed a ticket could be raised by the Customer, with SAP to perform further investigation.
Raise system uplift request when needed.
## Task 6: Subtask 4: Continuously Optimize IT Operations
#### Description
The purpose of this task is to continuously improve IT operations (e.g. via automation, or switching from a re-active to a pro-active operations approach). Customer COE and CIO Guides in Customer Center of Expertise portal has more details on improvement options.

One approach to improve IT operations is to set up an Advanced Customer COE. The advanced certification for Customer COEs covers the full spectrum of SAP solution operations. Based on the SAP standards for solution operations and the SAP Activate methodology, a team with advanced certification has integrated quality management in place, bringing transparency to the challenges and issues faced by the organization as a whole. This is paramount for mission critical operations. Visibility, alignment, and a common understanding of those top issues are enabled through the center's ability to maintain a single source of truth - one central area where everything is tracked and from which all information flows.

Procedure:
1. Review **[What a Customer COE Should Know About Incident Managent](https://help.sap.com/doc/76658138f2954be4b357fef61ebab8a4/2017:1/en-US/index.html)** accelerator to also get an overview of various SAP support channels that are available.
2. Continuously improve IT operations for maximum efficiency by leverage support and services provided by SAP. Reference task Access SAP Support Service for details.
3. Access **[SAP Enterprise Support Report Reporting Cockpit](https://launchpad.support.sap.com/#/customerinsight360)** to refine indicators, improve and optimize the overall system landscape.
4. Use **[Early Watch Alert ](https://support.sap.com/support-programs-services/services/earlywatch-alert.html)**workspace tool to prevent errors and problems.
5. Leverage service from **[Incident Quality](https://launchpad.support.sap.com/#/incidentquality)** dashboard to check the quality of incidents to optimize the process.

## Task 7: Identify Innovation and Growth Opportunities
#### Description
The purpose of this deliverable is to improve and simplify your new solution to realize maximum benefit. On the one hand, this requires the periodic update, by implementing feature and support packs, to bring the latest innovations from SAP into your solution. On the other hand, a new planning cycle needs to be initiated together with your peers from the business units, to identify innovations which are mostly required.

SAP supports customer post Go-Live towards the Intelligent Enterprise. Customer is notified of potential capacity issues and should engage SAP Customer Success Partner to determine demands, understand risks and plan for future projects together with SAP in continuous transformation journey.
## Task 7: Subtask 1: Periodically Update your SAP System
#### Description
The purpose of this task is to evaluate new features, plan and execute frequent updates to keep SAP S/4HANA system current in order to support continuous business innovation.

SAP delivers one major release and two minor ones each year. Minor releases are the first two support package stacks, known as Feature Package Stack (i.e FPS01 FPS02). Support Package Stacks three and onwards (ie. SPS03, SP04, etc) are corrections only for mainstream maintenance and will last for five years for the respective major release.

Release upgrade should be planned and executed by customer. There are two approaches in upgrade: Technical and Functional. Technical approach focusing on updating software with minimum mandatory updates in configuration and custom code. Functional approach not only includes the technical aspect but more importantly deploys new business functionality as well, which involves more testing and user adoption efforts.

It is recommended for customer to take advantage of the once-a-year entitlement of the software upgrade offered by SAP and do the minimum changes required in Technical upgrade approach. This helps customer stay current as dictated by the SAP S/4HANA maintenance schedule, and with corrections and improvements that stabilize the system, improve performance, ensure the security of the system.

SAP perform the technical execution of all upgrades and patching to client 000. Customer or Partner performs the functional upgrade and patching activities on the application layer, ie. custom code remediation, notes implementation, simplification as per simplification lists etc.

While SAP have accountability in execution of certain changes, Customer owns the overall release management for all activities. SAP should be informed and involved to understand all customer releases and to initiate the approval process with Customer for any SAP releases.

Procedure:
1. Check [**Schedule for Release and Maintenance**](https://support.sap.com/en/release-upgrade-maintenance.html) accelerator from support portal for timeline on new releases, feature packages and support packages.
2. Use **[SAP S/4HANA What’s New Viewer](https://help.sap.com/doc/474a13c5e9964c849c3a14d6c04339b5/100/en-US/8880de6dbfb94ea3b0de1f26b40816dc.html)** to evaluate new features for the selected release(s) and feature package(s).
3. Reference the **[Upgrading SAP S/4HANA - How, Why, and Best Practice](https://www.sap.com/documents/2020/06/94ca0995-9d7d-0010-87a3-c30de2ffd8ff.html)** accelerator to determine the desirable upgrade path and choose between a minimum Technical approach or Functional approach of an improvement project.
4. Reference the SAP S/4HANA Upgrade and Product Integration Roadmap in Roadmap Viewer to plan and execute the upgrade project.
5. Create Service Request in [**SAP for Me**](https://me.sap.com/) in Services & Support dashboard to request the software update of the selected release and feature package as needed.

## Task 7: Subtask 2: Revise SAP Fiori apps
#### Description
The purpose of this task is to find deprecated SAP Fiori apps resulting from an SAP S/4HANA upgrade. Some SAP Fiori apps will be deprecated and some replaced by new apps. The retired apps will not work with your new S/4HANA release, so it is important to review the retired apps after each release and make the necessary changes as soon as possible. You can find more information in the SAP Fiori Apps Reference Library accelerator.

Procedure:

1. Watch the openSAP Microlearning video, to understand how to find available SAP Fiori apps. Refer to the [Open SAP - Finding Available SAP Fiori Apps](https://microlearning.opensap.com/media/1_pgjj89f6) accelerator.
2. Review the [Blog - SAP Fiori for SAP S/4HANA - Finding the Delta of New Apps between SAP S/4HANA Releases](https://blogs.sap.com/2019/01/08/fiori-for-s4hana-finding-the-delta-of-new-apps-between-sap-s4hana-versions/) accelerator, for step-by-step procedures.
3. Accelerator(s)
## Task 7: Subtask 3: Initiate a New Improvement and Innovation Project
#### Description
The purpose of this task is to initiate a new project to continue the improvement and innovation cycle.

Improvements and innovations are not a one-step-process, but a continuous journey. After the initial go-live, business requirements may have changed, and company may have gained experience on what is possible with the new solutions from SAP. It is time to continue improve the business process efficiencies through expanded use of the SAP solutions.

SAP continuously inform the customer of new innovations in its solutions. New organization model like Customer Center of Expertise can be leveraged to check for continuous improvement potential of the SAP solutions to realize the entire value of company's investment. Customer Center of Expertise can also provide transparency and efficiency in the implementation of these improvements and innovations to meet business objectives and goals. Partner can also play a role in driving these improvements through project implementations.

Procedure:

1. Review the innovation and implementation strategy created initially.
2. Consolidate feedback and data from business process measures, monitoring, and analysis.
3. Deep dive into data collected regarding value realization, process conformance, etc and capture learnings.
4. Outline improvements and innovations in the content of Business Capabilities.
5. Use [SAP Roadmap Explorer - Business Technology Platform](https://roadmaps.sap.com/board?range=FIRST-LAST&sap-outbound-id=855486676BA0B23A27A161E146BEA8626BFAE4BD&sap-outbound-id=F84338300454061B469DD99EFA855784D1EE0293&PRODUCT=42F2E964FAAF1EDA9FF753E17F3000E5&smc_campaign_id=0000034720&source=email-smc#Q1%202022) accelerator to review the product roadmap of new innovations from SAP.
6. Also refer to accelerator [What's New - SAP Business Technology Platform](https://help.sap.com/whats-new/cf0cb2cb149647329b5d02aa96303f56?locale=en-US) to review what feature have been rolled out recently.
7. Adjust your innovation strategy accordingly.
8. Create plans for future projects.
## Task 7: Subtask 4: Run the User Experience Business Benefits Workshop
#### Description
The purpose of this task is to run a workshop to review the User Experience business benefits and understand what has been achieved so far and the lessons learned. It is during this workshop that the UX/UI strategy and UX adoption roadmap can be adjusted based on the decisions made in the workshop.

Prerequisites:

Review the target business roles and prioritized value goals.
Review the UX/UI Strategy and UX Adoption Roadmap.
Prepare and send out survey(s) to gain feedback from business users.
Set up site visits or virtual sessions with business users to gain feedback.
Gather statistics on app usage, user behaviors and process execution.
Review process execution and identify areas of potential improvement.
Provide an evaluation of the captured metrics against the baseline UX metrics.
Collate and prepare insights on survey results from business users.
Review the accelerators Fiori launchpad best practice verification checklist and SAP Help – Fiori launchpad to check your options to adjust the experience.

Procedure:
1. Understand how the UX Adoption Roadmap is progressing including the perceptions and opinions of the new user experience by the impacted business roles.
2. Discuss survey results, feedback from sites and any additional feedback to capture lessons learned and areas for improvement as updates to your UX/UI Strategy.
3. Review statistics on app usage and user behaviors.
4. Propose and decide on adjustments needed for the business roles that are live. Proposed adjustments may include:
* Launchpad settings
* Launchpad content
* Launchpad layout
* Device OS / Web Browser settings
* Network / bandwidth / patching and other performance related settings
5. Review and adjust the UX Adoption Roadmap for future business roles as required.
6. Evaluate the captured metrics against the baseline UX metrics to understand realized value.
## Task 8: ISV Partner Spotlight:SNP
#### Description
Once you are live on your new SAP S/4HANA system, post go live, SNP has solutions to further optimize your landscape. You can decide to take on archiving projects in the early stages of your migration journey or post migration with SNPs [Data Volume Management](https://www.snpgroup.com/en/solutions/data-governance-and-compliance/smart-data-and-document-archiving/) solution. With [Application Retirement](https://www.snpgroup.com/en/solutions/data-governance-and-compliance/application-retirement/) Solution, customers can sunset applications without losing access to their legacy data