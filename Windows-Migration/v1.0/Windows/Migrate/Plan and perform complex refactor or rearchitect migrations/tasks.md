
# Module: Plan and perform complex refactor or rearchitect migrations
## Task 1: Refactor  or Rearchitect - Pre-migration 
#### Description
In the pre-migration task, the migration team is responsible for preparing the  implementation environment. This includes the following:   
1) Identifying the resources to migrate to AWS   
2) Setting up migration accounts
#### Tools
AWS Database Migration Service (AWS DMS)
#### Tools
AWS Schema  Conversion Tool (AWS SCT)
#### Tools
AWS CloudFormation
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
• Prepare the  implementation environment 
## Task 2: Refactor or Rearchitect -   Migration implementation
#### Description
The  migration team is responsible for running predefined tasks that automate the  migration process. These tasks can include the following:  
1) Verifying prerequisites  
2) Pushing the replication agent to the source machines for a given wave  
3) Verifying replication status  
4) Launching servers for boot-up testing  
5) Scheduling a window for application cutover

#### Tools
AWS CloudFormation
#### Tools
AWS Application Migration Service
#### Tools
AWS Database Migration Service (AWS DMS)
#### Tools
AWS Schema  Conversion Tool (AWS SCT)
#### Acceptance Criteria
•  Automate and implement the migration process.
## Task 3: Refactor or Rearchitect - Post Migration
#### Description
Post-migration tasks usually include optimizing the performance for the target  instances as well as cleanup activities of resources used during the  migration process.

#### Tools
AWS Application Migration Service
#### Tools
AWS Database Migration Service (AWS DMS)
#### Tools
AWS Schema  Conversion Tool (AWS SCT)
#### Tools
AWS CloudFormation
#### Acceptance Criteria
• Clean up and decommission resources used during the migration process
#### Acceptance Criteria
•  Optimize the performance of the server instances 