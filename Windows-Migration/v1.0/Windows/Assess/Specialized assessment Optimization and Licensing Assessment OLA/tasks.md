
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
4) Identift the application dependencies
#### Acceptance Criteria
• Provisioned the data collector tool with the desired migrating environment infrastructure
#### Acceptance Criteria
• Used the Migration Evaluator collector tool to collect utilization data for the migrating environment
## Task 3: Collect Actual Consumption Data of Windows Servers using Migration Evaluator
#### Description
To evaluate the current migrating environment to AWS, you need to collect the inventory and performance data of the environment that needs to be migrated. To collect this data, you set up and run the Migration Evaluator collector tool. The collector tool accumulates data with a high level of accuracy, which helps to analyze and suggest the appropriate approach for migration.

For information about the tool, see [Agentless collector overview](https://https://https//d1.awsstatic.com/migration-evaluator-resources/agentless_collector_overview.pdf.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
A document (PDF or spreadsheet) with current inventory data and performance data
## Task 3: Subtask 1: Migration Evaluator Collector tool overview
#### Description
Migration Evaluator collector tool document outlines the flow of data while using the tool, in which the customer chooses to acquire provisioning and utilization patterns via the on-premises agentless Migration Evaluator Collector.
More details regarding the tool can be found here: [Agentless collector overview](https://https://chrome-extension//efaidnbmnnnibpcajpcglclefindmkaj/https://d1.awsstatic.com/migration-evaluator-resources/agentless_collector_overview.pdf)
#### Tools
Migration Evaluator collector tool
## Task 3: Subtask 2: Review Pre-Installation Checklist
#### Description
After you gain a clear understanding of the Migration Evaluator collector tool, run through a checklist of items before you install the tool. The following document highlights the [checklist](https://https://https//d1.awsstatic.com/migration-evaluator-resources/collector_install-guide.pdf.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
Run through the checklist and ensure that all prerequisites are satisfied. 
## Task 3: Subtask 3: Install the Migration Evaluator collector tool
#### Description
After you ensure that the items in the pre-installation checklist are satisfied, install the tool. See [here.](https://https://https//d1.awsstatic.com/migration-evaluator-resources/collector_install-guide.pdf.)
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
• Installed the Migration Evaluator collector
• Installed the Migration Evaluator Bootstrapper 

## Task 3: Subtask 4: Start Data collection
#### Description
Once installation is complete and all servers are included in Assessment Scope and in a COLLECTING DATA state, you’re ready to click Start Assessment and select your Regions and Date Ranges.
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
Throught Migration Evaluator Agentless collector, collected data started to see in Migration Evaluator dashboard. 
If existing data is importing using data collection template to Migration Evaluator, systems information can be seen in the dashboard.
## Task 3: Subtask 5: Validate the collected data
#### Description
After you successfully configure the Migration Evaluator collector tool, validate the collected data and document any missing details and dependencies.
## Task 3: Subtask 6: Configure the Migration Evaluator collector tool
#### Description
After successfully installing the Migration Evaluator collector tool, it needs to be configured to collect the desired inventory data. This depends on the type of resources that needs to be migrated to AWS. There could be different types of resources in a migrating environment such as VMWare, SQL Servers, Bare metal servers, Hyper V servers etc.
#### Tools
Migration Evaluator collector tool
#### Acceptance Criteria
•  Configured the tool for the desired resources in the environment
## Task 3: Subtask 7: Review OLA Result
#### Description
Once data collection is completed, you should be able to review and vaildate the OLA result. If an AWS partner is helping you with the OLA discovery, you will come out with a report which covers TCO, licensing recommendation and migration waves etc.
#### Acceptance Criteria
Following are deliverables after data collection is completed.
- Executive summary
- Scope of Work
- Key Recommendations
- Microsoft Licensing Summary
- Licensing Optimization
- DH and SQL optimization
- TCO and next steps 
## Task 4: Collect Actual Consumption Data of Windows Servers using Cloudamize
#### Description
To evaluate the current migrating environment to AWS, you need to collect the inventory and performance data of the environment that needs to be migrated. To collect this data, you set up and run the Cloudamize tool. The collector tool accumulates data with a high level of accuracy, which helps to analyze and suggest the appropriate approach for migration.

For information about the tool, you can refer [here](https://https://www.cloudamize.com/).
#### Tools
Cloudamize
## Task 4: Subtask 1: Cloudamize data collector tool overview
#### Description
- [Review Installation and Data Collection Guide](https://support.cloudamize.com/kb/installation-and-data-collection)
- [Understand the Data collected by Agents](https://support.cloudamize.com/kb/data-collected-by-agents)
#### Tools
Cloudamize
#### Acceptance Criteria
Understand the various deployment options of data collector tool
## Task 4: Subtask 2: Understand Prerequisties of Cloudamize data collection tool
#### Description
Review the [installation and prerequisties](https://support.cloudamize.com/kb/installation-prerequisites) of Cloudamize data collection tool

- [Agentless Installation Prerequisties](https://support.cloudamize.com/kb/agentless-installation-prerequisites)
- [Agent Installation Prerequisties ](https://support.cloudamize.com/kb/agent-installation-prerequisites)
- [Hyper-V installation Prerequisties](https://support.cloudamize.com/kb/agent-installation-prerequisites)
- [Supported Operating Systems and Chipsets](https://support.cloudamize.com/kb/supported-operating-systems-and-chipsets)
#### Tools
Cloudamize
#### Acceptance Criteria
Understand the prerequisties of Cloudamize data collection tool
## Task 4: Subtask 3: Deployment of Agent/Agentless discovery
#### Description
Based on your decision about data collection methods, start the preparation for data collection. 
- [Windows Agent Installation](https://support.cloudamize.com/kb/windows-agent-installation-instructions)
- [Windows Agent Installation with GPO](https://https://support.cloudamize.com/kb/windows-agent-deploy-with-group-policy-object-and-)
- [Agentless Collection](https://https://support.cloudamize.com/kb/setup-instructions-and-troubleshooting)
- [Data Collection from Hypver-V Host](https://https://support.cloudamize.com/kb/hyper-v-installation-instructions)
- [Data Collection from vCenter](https://https://support.cloudamize.com/kb/hyper-v-installation-instructions)
#### Tools
Cloudamize
#### Acceptance Criteria
On-premise environment is ready for data collection
## Task 4: Subtask 4: Review Inventory Settings
#### Description
Review the [inventory setting](https://https://support.cloudamize.com/kb/about-inventory-settings) in Cloudamize portal. 
#### Tools
Cloudamize
#### Acceptance Criteria
Review and understand inventory settings in the Cloudamize portal 
## Task 4: Subtask 5: Reviewing the discovery result
#### Description
Review the collected data. 
- [BYOL](https://support.cloudamize.com/kb/aws-bring-your-own-license)
- [Dedicated Host](https://support.cloudamize.com/kb/design-dedicated-host-view)
- [Application Migration Service (MGN)](https://support.cloudamize.com/kb/migrate-with-cloudendure)
- [Estimated TCO](https://support.cloudamize.com/kb/estimated-decarbonization-report)
#### Tools
Cloudamize
## Task 5: Engage licensing assessment partner
#### Description
Engage Licensing Partners (Optimus/Evolve) during OLA assessment to analyze the the output through a licensing lens, and determine ways to further reduce the total spend by decreasing Microsoft licensing costs as long as the following either one of the thresholds is met. 
- Over 50 Windows Servers
- Over 10 SQL Servers
#### Tools
Evolve Cloud Services
#### Tools
Optimus Group
#### Acceptance Criteria
Reviewed of existing Microsoft Licensing Agreements and a detailed review of how recent Microsoft licensing use right changes can impact existing and future workloads
## Task 5: Subtask 1: Engage Licensing Assessment Partner
#### Description
Understand how our licensing partners can help to conduct an assessment. More information can be found in following:
- [Evolve -AWS Funded Microsoft OLA](https://evolvecloudservices.com/aws-funded-microsoft-ola)
- [Optimus Group](https://www.optimusgroupintl.com/aws-funded-assessments)
## Task 6: OLA  Document results
#### Description
After you use the Migration Evaluator collector tool to collect the data, do the following:

1) Prepare the final output presentation based on the collected data
2) Move to the next steps to integrate with partners and Proserve teams
#### Acceptance Criteria
•  Generated the OLA report using the collected data