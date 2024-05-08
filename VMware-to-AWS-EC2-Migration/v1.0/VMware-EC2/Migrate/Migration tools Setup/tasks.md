
# Module: Migration tools Setup 
## Task 1: Setup AWS Application Migration Service (MGN) 
#### Description
Setup AWS MGN service for Lift and Shift
https://docs.aws.amazon.com/mgn/latest/ug/what-is-application-migration-service.html
## Task 1: Subtask 1: AWS MGN Agent base migration :  AWS Application Migration Service
#### Description
This pattern outlines the steps for migrating a supported virtual machine (VM) to an Amazon EC2 instance on the AWS Cloud by using AWS Application Migration Service. You can use the approach in this pattern to migrate one or multiple virtual machines manually, one by one, or automatically by creating appropriate automation scripts based on the outlined steps.  (https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/migrate-an-on-premises-vm-to-amazon-ec2-by-using-aws-application-migration-service.html)
## Task 1: Subtask 2: AWS MGN Agentless migration: AWS MGN Agent less  migration
#### Description
AWS MGN Agentless approach currently only supports vCenter as a source environment. AWS MGN Agentless uses a process called snapshot shipping, not block-level replication, which is a long running process responsible for taking periodic VMWare snapshots from the discovered source VMs and sending them to AWS. The first snapshot will include the entire disk content, and following snapshots will only sync the disk changes. After the process completes, it creates a group of EBS volumes in your target AWS account that you can later use to launch your Test or Cutover instances. The AWS MGN vCenter client must be installed on a dedicated VM running in your vCenter environment. (https://docs.aws.amazon.com/mgn/latest/ug/agentless-mgn.html)
## Task 2: Setup AWS Application Migration Service (MGN) Factory
#### Description
Setup AWS MGN Factory solution for Lift and Shift in a factory based model

https://aws.amazon.com/solutions/implementations/cloud-migration-factory-on-aws/
## Task 3: Setup AWS Database migration service (DMS)
#### Description
Setup AWS DMS for migrating Databases
https://docs.aws.amazon.com/dms/
## Task 4: Setup AWS Data Sync
#### Description
AWS DataSync is a secure, online service that automates and accelerates moving data between on premises and AWS Storage services.  https://aws.amazon.com/datasync/getting-started/?pg=ln&cp=bn
## Task 5: Using AWS Migration Hub with AWS MGN
#### Description
AWS Migration Hub (Migration Hub) provides a single place to discover your existing servers, plan migrations, and track the status of each application migration. You need to validate you have applications created in Migration Hub.  ]https://docs.aws.amazon.com/migrationhub/latest/ug/whatishub.html
## Task 6: Configure Migration Hub Orchestrator plugin to simplifies and automates the migration of servers and enterprise applications to AWS.
#### Description
Tool : AWS Migration Hub Orchestrator : It simplifies and automates the migration of servers and enterprise applications to AWS. You can get started quickly through the predefined workflow templates which are built leveraging the migration experience of AWS which also adhere to best practices. You can also use Migration Hub Orchestrator to automate the error-prone manual tasks involved in the migration process and orchestrate the related migration tools from start to finish in the Migration Hub Orchestrator console Migration Hub Orchestrator offers templates to create a migration workflow that can be customized to fit your unique migration requirements. (https://docs.aws.amazon.com/migrationhub-orchestrator/latest/userguide/what-is-migrationhub-orchestrator.html)
## Task 7: Setup other migration tools 
#### Description
Setup other migration tools as needed.