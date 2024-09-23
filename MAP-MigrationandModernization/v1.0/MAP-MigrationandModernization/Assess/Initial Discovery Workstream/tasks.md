
# Module: Initial Discovery Workstream
## Task 1: Discovery Data Collection Methodology Selection
#### Description
1. Present options and decide data collection methodology with the customer :-

	**Manual** : Leverage customers existing toolset or reporting capability example Application Performance Monitoring System, Hypervisor Reports and Configuration Management Database (CMDB).

	**Tool Based** : Leverage either - AWS Services ( [AWS Migration Evaluator](https://aws.amazon.com/migration-evaluator/), [AWS Application Discovery Service](https://aws.amazon.com/application-discovery/)) or [AWS Partner Discovery Tools](https://aws.amazon.com/prescriptive-guidance/migration-tools/migration-discovery-tools/)

2. Data Collection Methodology is selected by first understanding the requirements and constraints.  

* **Requirements**
     * Performance & Utilization Metrics 
     * Application Dependency discovery and mapping. 
     * Operating Systems of the servers.
     * Application Analysis Vs Infrastructure analysis
     * Visualization and reporting capability
     * TCO/Cost analysis Capability

* **Constrains**
    * Agent-base vs Agentless
    * Data Residency
    * Data Sovereignty
    * Customers  Resource Expertise – support requirements
    * Customers Access Permissions
    * Tooling Cost

3. Ensure data collection methodology provides the required information by the data collection sheet template to allow effective analysis

#### Tools
Discovery, Planning, and Recommendation Migration Tools
#### Acceptance Criteria
1. Successful decision on data collection methodology.
## Task 2: Collection Period Definition
#### Description
1. Decide on the collection period especially for tool based collection. 

2. Recommended to collect for at least 2 weeks ( 1st week and last week of the month)  or 4 weeks (1 application cycle).

3. Data collection is structured to obtained the peak CPU, Memory, Disk IO, and Bandwidth utilization to allow right sizing of the instances in the cloud.
#### Acceptance Criteria
1. Successful decision on discovery data collection period.
## Task 3: Data Collection
#### Description
1. Collection of data as per the selected data collection methodology.
#### Acceptance Criteria
1. Successful preparation and readiness execution to enable data collection.
2. Successful selection of programs to accelerate data collection.
3. Successful completion of data collection leveraging the selected methodology.
## Task 3: Subtask 1: Tool installation and Configuration
#### Description
1. Present tooling / data capture requirements to the customer. This can be done through a tooling kickoff call.

2. Address stakeholder queries on the tool requirements and configuration. 

3. Work with the stakeholders to install and configure the discovery tool.

4. Leverage AWS Service Documentation or Partner Tooling installation guides as reference when installing and configuring the discovery tool. 
#### Tools
AWS Migration Evaluator
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
1. Tool Based : Tool successful installed and configured.
2. Manual Data Collection : Data extraction process defined and is able to be collected by the customer.
## Task 3: Subtask 2: Data collection or Capture Execution
#### Description
1. Carry out data collection or data capture execution as per the defined data collection period.

2. Monitor the data collection for errors related to data capture or configuration.
#### Acceptance Criteria
1. Successful data collection or capture execution as per the defined data collection period.
2. Successful data capture of all information required for the inventory analysis.
## Task 3: Subtask 3: Migration and Modernization Environmental/ESG Impact Analysis [Recommended]
#### Description
1. Assess the sustainability benefits the customer will have by migrating and modernizing to AWS. 

2. The assessment should evaluate the below areas :-
*  Carbon footprint reduction estimation
*  Power usage effectiveness (PUE)
*  Utilization optimization opportunities
*  Adoption of new hardware and software offerings
*  Managed services used in the solution

3. Leverage [AWS Carbon Footprint Tool](https://aws.amazon.com/aws-cost-management/aws-customer-carbon-footprint-tool/) or [AWS Sustainability Partner tooling/guidance](https://aws.amazon.com/solutions/sustainability/esg-reporting-disclosures/) to carry out the assessment.
#### Tools
AWS Carbon Footprint Tool
#### Tools
AWS Sustainability Partner Tooling
#### Acceptance Criteria
1. Successful sustainability requirements and data collection.
## Task 3: Subtask 4: Optimized and Licensing Assessment (OLA)
#### Description
1. Leverage the AWS OLA Program when there are license optimization requirements for Microsoft Workloads  (Operating System and Microsoft SQL).

2. AWS Partners can leverage the [Optimization and Licensing Assessments: Partner Funding Program User Guide](https://partnercentral.awspartner.com/partnercentral2/s/resources?Id=0698W00000setuPQAQ) as guidance to apply for the OLA program.

3. AWS Customers can request an Optimization and Licensing Assessments through the request an AWS OLA link [here.](https://aws.amazon.com/optimization-and-licensing-assessment/)

4. Ensure OLA Assessment is conducted in the Assess Phase or during the Detailed Discovery Workstream in the Mobilize Phase.
#### Acceptance Criteria
1. Successful leverage the Optimized Licensing Assessment (OLA) program to optimize current Microsoft Windows operating system and database licenses usage on AWS.
## Task 4: Inventory Data Analysis and Reporting
#### Description
1. Input the data collected into the data collection sheet. It is recommended to have a standardize data collection sheet template.

2. Leverage AWS Migration Portfolio Assessment (MPA) or equivalent partner discovery tooling to perform data analysis. For reference on data analysis best practices leveraging MPA leverage [Training Video](https://youtu.be/MxY55AnF3M0) and [Business Case Game Day](https://bit.ly/AWS-BCID).

3. Analyse the data collected or captured during the data collection task to build and define high-level optimized target state architecture, high-level migration plan and strategy (AWS 7R Strategy).

4. Perform AWS service and features mapping - selection of AWS services and features based on optimized target architecture.

5. Perform AWS service right-sizing - right-size the AWS services based on peak utilization or optimized configuration.

6. Define the high-level AWS migration strategy and plan based on the target architecture designed.

7. Include Analysis from the sustainability analysis and Optimized Licensing Assessment (OLA)

8. Build the Inventory analysis report that outlines the below areas :- 

* Current state specification, configuration and high-level design
* Future state specification, configuration and high-level design
* High-level migration strategy (AWS 7R Strategy)
* High-level migration plan - timelines and effort
* Sustainability analysis
* Licensing optimization analysis
#### Tools
Migration Portfolio Assessment (MPA)
#### Acceptance Criteria
1. Successful inventory data analysis.
2. Successful AWS service mapping, right-sizing and optimization.
3. Successful high-level AWS migration strategy definition.
4. Sustainability improvement recommendations [Recommended].