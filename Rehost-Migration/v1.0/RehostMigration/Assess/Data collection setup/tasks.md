
# Module: Data collection setup
## Task 1: Collect data using appropriate data collection tool
#### Description
To evaluate the current migrating environment to AWS, you need to collect the inventory data of the  environment that needs to be migrated. To collect this data, you can use AWS Application Discovery Service (ADS) or manually import inventory data.
#### Tools
AWS Application Discovery Service
#### Acceptance Criteria
• A document (csv) with current inventory data
## Task 2: Import inventory data (AWS MGN)
#### Description
Use the import template and Amazon S3 to upload data about servers and applications (group of servers) from your existing data sources.
#### Acceptance Criteria
• Gathered provisioning, software, and utilization data for the existing environment
## Task 3: Upload existing collector tool data - import template (AWS Migration Hub)
#### Description
If a complete list of servers with their provisioning, software, and utilization is already available, AWS MGN supports uploading the existing environment data.

Use the data-import template to upload the data. See [Data Import](https://docs.aws.amazon.com/mgn/latest/ug/import-main.html).
#### Tools
AWS ADS Import template
#### Acceptance Criteria
• Gathered provisioning, software, and utilization data for the existing environment
## Task 4: Upload existing collector tool data - ADS Agentless Collector (AWS Migration Hub)
#### Description
Deploy an Agentless Collector to monitor servers and databases without deploying software on each of your VMs or physical servers.
#### Tools
Application Discovery Service Agentless Collector
#### Acceptance Criteria
• Gathered provisioning, software, and utilization data for the existing environment