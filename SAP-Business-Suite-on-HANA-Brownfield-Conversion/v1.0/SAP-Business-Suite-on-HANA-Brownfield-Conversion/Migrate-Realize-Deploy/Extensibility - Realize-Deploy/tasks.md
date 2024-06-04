
# Module: Extensibility - Realize-Deploy
## Task 1: Solution Extension Development
#### Description
The purpose of this deliverable is the setup of extensions in the development landscape and the development of setup guides if needed. The following topics are covered within the deliverable

Development and setup of the extension in the development landscape.
Document all actions to plan and test the extension in quality assurance and the deployment to the productive landscape.
#### Acceptance Criteria
• Prepare the  implementation environment 
## Task 1: Subtask 1: Setup and Develop Key-User Extensions
#### Description
The purpose of the task is to develop and setup key-user extensions

Prerequisite

Detail design of extension and sign off in Explore Phase.
Procedure

Develop and setup the key-user extension in the Q System.
Refer the help documentation available via the [Help - Key User](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/3ccb50e724b045508fea8b2cf1774b2b.html) Extensibility accelerator
## Task 1: Subtask 2: Setup and Develop Classic Extension in the DEV Landscape
#### Description
The purpose of the task is to develop and set up a classic extension in the Development landscape.

Prerequisite

Detail design of the extension and sign-off in Explore.


Procedure

1. Develop the classic extension in the DEV landscape and the QA landscape.
2. Transport the content to the QA Landscape to test the extended scenario.
## Task 1: Subtask 3: Setup and Develop Side-by-Side Extensions
#### Description
The purpose of the task is to develop and set up a side-by-side extensions

Prerequisite

Detail design of the extension and sign-off in Explore.
Procedure

1. Develop and set up the side-by-side extension in the Q System based on requirements collected in the Collect Details for Extensions task
2. Refer the [SAP Extensibility Explorer](https://extexplorerui-ad68458d8.dispatcher.hana.ondemand.com/webapp/index.html) and [Extend SAP S/4HANA in the cloud and on premise with ABAP based extensions](https://api.sap.com/) accelerators for additional guidance on development of extensions using the side by side scenario.
## Task 1: Subtask 4: Deploy Key-user Extensions to the PROD Landscape
#### Description
The purpose of this task is the setup of key-user extensions in the Productive Landscape

Prerequisite

Successfull testing of extended scenario with key user extension

Procedure

Deploy key-user extension into PROD landscape.
## Task 1: Subtask 5: Development and Setup of Side-by-Side Extension in the PROD Landscape
#### Description
The purpose of this task is the setup of side-by-side extensions in the Productive landscape.

Prerequisite

Successful testing of extended business scenario

Procedure

Deploy and setup of side-by-side extension in the PROD landscape.
## Task 1: Subtask 6: Deploy Classic Extension to the PROD Landscape
#### Description
The purpose of this task is thedeployment of classic extensions into the Productive Landscape.

Prerequisite

Successful testing of extended business scenario.

Procedure

Deploy the classic extension into the PROD landscape.
## Task 1: Subtask 7: Production Cutover - Deploy
#### Description
Production Cutover
The purpose of this deliverable is to execute the cutover plan and ready the business and system for productive use. The cutover plan contains both business process tasks as well as system tasks. It is executed in the days prior to the go-live date.

Examples of potential tasks in the cutover list are as follows. Based on the solution, not all may be applicable.

* Setting up and initializing the production system
* Setting up and verifying interface connections
* Migration or creation of master data
* Migration of order objects (i.e. purchase orders, sales orders, etc)
* User creation/access
* Go/no go decision points
* Closing the legacy systems
* Notification of impacted 3rd parties
* Completing all required documentation for regulatory purposes
## Task 2: Product Enhancements
#### Description
The purpose of this deliverable is to enhance your solution and develop custom code to close the gaps identified during the Fit-to-Standard workshops in the Explore phase. It also covers the adjustment of already existing custom code identified in the activity Custom Code Impact Analysis. SAP recommends to explore the options for the agile creation of customer innovations using the SAP Extension Suite of the SAP Business Technology Platform(SAP BTP). SAP BTP is the platform for the Intelligent Enterprise. Customers can achieve agility, business value, and continual innovation through integration, data to value, and extensibility of all SAP and third-party applications and data assets.
#### Acceptance Criteria
•  Automate and implement the migration process.
## Task 2: Subtask 1: Adjust Affected Existing Custom Code
#### Description
The purpose of this task is to adjust the custom code, and make it ready for SAP S/4HANA.

Prerequisite:

This activity is relevant in case own code needs to be made ready for SAP S/4HANA (e.g. the system conversion case). In case of a new implementation, or a landscape transformation, some custom code from an old SAP ERP system might be in scope to be used in the new SAP S/4HANA system.
The custom code work list of affected objects has been created. Refer to the Custom Code Impact Analysis Task.
The development system has been converted to SAP S/4HANA.

Procedure:

To adjust custom code that is affected by the conversion to SAP S/4HANA project, proceed as follows:

1. Make sure your developers have the required skill set to adjust your custom code for SAP S/4HANA. There are multiple options for developer training (e-learnings, classroom). Please see accelerator section for more information.
2. Make sure you have the prioritized list of custom objects requiring adjustment. Refer to the Custom Code Impact Analysis task for details.
3. Wait until your DEV system has been converted to SAP S/4HANA.
4. Adjust custom code objects in the converted DEV system according to the prioritized custom object list. Log all changes in transport requests.
5. Transport your changes to QAS, once it has been converted to SAP S/4HANA. Test your changes in QAS. In case corrections are required, perform the corrections in DEV and transport to QAS again.
6. All transport requests should then be populated in the PRD buffer, ready for import during the Go-Live.
7. Please note: In case of a system conversion, the old DEV system will stay for production support of PRD as long as PRD is not converted. Take care to properly retrofit changes performed in the production support landscape to the new DEV system to ensure the latest business requirements are accounted for within the project landscape.

Results

All custom code is adjusted to function properly with SAP S/4HANA.


## Task 2: Subtask 2: Development of Clean Core Compliant Extensions
#### Description
The purpose of this task is to develop extensions within the defined project scope and specified from a functional perspective during the Explore phase while ensuring compliance to the Clean Core Strategy

Procedure:

All extensions should follow the 3-Tier Extensibility Model explained in [Extend SAP S/4HANA in the cloud and on premise with ABAP based extensions](https://www.sap.com/documents/2022/10/52e0cd9b-497e-0010-bca6-c68f7e60039b.html)

1. **Tier 1 – Cloud development**: default choice for all new extensions following the SAP S/4HANA Cloud extensibility model.
2. **Tier 2 – Cloud API enablement**: mitigation of missing local public APIs or extension points. Here, custom wrappers for non-released SAP objects are built and released for cloud development so that they can be used in tier 1. Once SAP provides a public local API, the custom wrapper can be removed. In this sense, tier 2 serves as an extension to tier 1 which will follow the same ABAP Cloud development model besides the usage of the wrapped non-released SAP object.
3. **Tier 3 – Legacy Development**: classic extensibility based on classic ABAP custom code that is not supported in the ABAP Cloud development model. The goal is to avoid developments in this tier and follow the ABAP Cloud development model as much as possible (governed via ATC) to minimize the risk of upgrade issues.

Development Approach is as outlined below

1. **Specify technical design**.Based on the functional requirements described in the delta design document, the purpose of this task is to specify the development object from a technical perspective. A detailed technical specification will be provided. This comprises in case of ABAP development details like entry point in the system, enhancement logic, process flow diagram, data model and required authorizations. For each enhancement, the appropriate test case(s) will be defined and documented within SAP Cloud ALM.
2. **Create Development Objects.** The developer is in charge to realize the requirement, which includes the development itself but for sure also documentation and unit testing.
3. **Unit test all developed objects**. The purpose of this task is to perform a unit test of the developments. The objective is to resolve any issues identified during the development object(s) test. It is crucial that the issues are solved, and re-tested by users that reported them (or designated re-testers) and that they are confirmed. Additionally, during this task, a final code review of the development objects will be performed and readiness for transport into QAS has to be confirmed.
## Task 2: Subtask 3: Enhancement and Development of User Interface
#### Description
Enhancement and Development of User Interface
The purpose of this task is to provide user interface enhancements within the defined project scope and specified from a functional perspective during the Explore phase.

Procedure

1. Configure and develop customer-specific user interfaces, such as SAP Fiori UX or Screen Personas.
2. Review the SAP Blog “SAP S/4HANA – [How to Create and Generate Back-end Security Authorizations for SAP Fiori 2.0](https://blogs.sap.com/2017/03/09/sap-s4hana-1610-how-to-create-and-generate-backend-security-authorizations-for-sap-fiori-2.0/)” which provides a step-by-step instruction on how to create and generate SAP Back-end authorizations for a SAP S/4HANA system based on SAP Fiori 2.0 Front-end Server Catalog information.
3. **Specify technical design**.Based on the functional requirements described in the delta design document, the purpose of this task is to specify the SAP Development Object from a technical perspective. A detailed technical specification will be provided. This comprises in case of ABAP developments development details like entry point in the system, enhancement logic, process flow diagram, data model and required authorizations. Development objects are new objects or objects to be adjusted, identified during the explore phase, e.g. a requirement for a new workflow or form identified. All information will be documented in a technical specification document (see Accelerator’s section for details). For each enhancement, the appropriate test case(s) will be defined and documented. The final documents will be stored within the 'Documents' App in SAP Cloud ALM for shared access.
4. **Create Development Objects**. The developer is in charge to realize the requirement, which includes the development itself but for sure also documentation and unit testing.
5. **Unit test all developed objects**. The purpose of this task is to perform a unit test of the developments. The objective is to resolve any issues identified during the Development Object(s) test. It is crucial that the issues are solved, and re-tested by users that reported them (or designated re-testers) and that they are confirmed. Additionally, during this task, a final code review of the development objects will be performed and readiness for transport into QAS has to be confirmed.
## Task 2: Subtask 4: Custom Development
#### Description
The purpose of this task is to create and manage custom development. For development requirements exceeding a certain threshold (which is project specific) or considering those as critical for the project, it is recommended to manage those as custom developments.

Procedure:

1. **Specify technical design**.Based on the functional requirements described in the delta design document, the purpose of this task is to specify the SAP Development Objects from a technical perspective. A detailed technical specification will be provided. This comprises in case of ABAP developments development details like entry point in the system, enhancement logic, process flow diagram, data model and required authorizations. Development objects are new objects or objects to be adjusted, identified during the explore phase, e.g. a requirement for a new workflow or form identified. All information will be documented in a technical specification document (see Accelerator’s section for details). For each enhancement, the appropriate test case(s) will be defined and documented. The final documents will be stored within the 'Documents' App in SAP Cloud ALM for shared access.
2. **Create Development objects**. The developer is in charge to realize the requirement, which includes the development itself but for sure also documentation and unit testing.
3. **Unit test all developed objects**. The purpose of this task is to perform a unit test of the developments. The objective is to resolve any issues identified during the development object(s) test. It is crucial that the issues are solved, and re-tested by users that reported them (or designated re-testers) and that they are confirmed. Additionally, during this task, a final code review of the development objects will be performed and readiness for transport into QAS has to be confirmed.
4. Document the information in a technical specification document. See accelerators for details. For each enhancement, the appropriate test case(s) will be defined and documented. The final documents will be stored in a central repository.
## Task 3: Refactor or Rearchitect - Post Migration
#### Description
Post-migration tasks usually include optimizing the performance for the target  instances as well as cleanup activities of resources used during the  migration process.

#### Tools
AWS Schema  Conversion Tool (AWS SCT)
#### Tools
AWS CloudFormation
#### Tools
AWS Database Migration Service (AWS DMS)
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
• Clean up and decommission resources used during the migration process
#### Acceptance Criteria
•  Optimize the performance of the server instances 