
# Module: Create plan and operate migration factory for rehost and replatform migrations
## Task 1: Import virtual machine images to AWS
#### Description
use the Import virtual machine images to AWS template to convert existing images of Open Virtual Appliance (OVA) or VMware Virtual Machine Disk (VMDK) to Amazon Machine Image (AMI) for Amazon EC2 using Migration Hub Orchestrator.
#### Tools
Migration Hub Orchestrator
## Task 2: Rehost  and replatform - Pre-migration 
#### Description
In the pre-migration task, the migration team is responsible for preparing the implementation environment. This includes the following:   
1) Deploying Cloud Migration Factory  
2) Building a migration execution server  
3) Setting up a migration account.For more information, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-factory-cloudendure/workflow.html.) 
#### Tools
AWS Cloud Migration Factory
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
• Prepare the  implementation environment
## Task 3: Rehost and replatform - Migration implementation
#### Description
During this task, the migration team is responsible for running predefined tasks that automate the migration process. These tasks can include the following:  
1) Verifying prerequisites  
2) Pushing the replication agent to the source machines for a given wave  
3) Verifying replication status  
4) Launching servers for boot-up testing 
5) Scheduling a window for application cutoverMigration tasks are scheduled in waves. Each wave consists of a group of applications and servers that have the same cutover date. For more information on the Cloud Migration Factory workflow, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-factory-cloudendure/workflow.html.)
#### Tools
AWS Cloud Migration Factory
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
•  Automate and implement the migration process in multiple iterations (waves) until all the applications are migrated
## Task 4: Rehost and replatform - Post-migration
#### Description
Post-migration tasks usually include optimizing the performance for the target instances as well as the cleanup of resources used during the migration process.For more information on the Cloud Migration Factory workflow, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-factory-cloudendure/workflow.html.)
#### Tools
AWS Application Migration Service
#### Tools
AWS Cloud Migration Factory
#### Acceptance Criteria
• Clean up and decommission the resources used during the migration process.
#### Acceptance Criteria
• Optimize the performance of the server instances 