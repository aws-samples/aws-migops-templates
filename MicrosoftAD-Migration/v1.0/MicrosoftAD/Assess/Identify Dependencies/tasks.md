
# Module: Identify Dependencies
## Task 1: Requirements for Access
#### Description
The requirements for access to control Active Directory will stipulate the right migration path for you. If you require full access to the Active Directory domain controllers to install any type of agents for compliance regulations. The AWS Managed Active Directory may not be a good match and instead you should investigated and extension of Active Directory from your domain controllers to EC2.
## Task 2: Migration Timelines
#### Description
If you have an extended timeline for migration and are unsure of completion assure you have contingencies in place for administration of instances in the cloud, and on-premises. Authentication is a key component to be in place for Windows workloads to avoid administration issues. Plan to move Active Directory early in your migration.
## Task 3: Backup Strategies
#### Description
If you use an existing Windows Backup for capturing Active Directory Domain Controllers systems state, you can leverage those still in AWS. Additionally there are couple additional technologies available in AWS to backup your instances. Each of three items below are all successfully used for backing up Active Directory domain controllers. It’s best to not rely on restoration of Active Directory in case of issues, but build a resilient architecture, but there may occasions where recovery is needed, so it’s critical to have some sort of backup method in place.
#### Tools
AWS Backup
#### Tools
AWS Elastic Disaster Recovery
#### Tools
Amazon Data Lifecycle Manager