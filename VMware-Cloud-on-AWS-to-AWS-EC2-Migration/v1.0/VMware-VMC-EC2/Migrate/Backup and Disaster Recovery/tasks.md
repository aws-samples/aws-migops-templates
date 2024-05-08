
# Module: Backup and Disaster Recovery
## Task 1: Setup AWS Backup Service
#### Description
 AWS Backup service can be used to backup on-premise VMware virtual machines and restore them to EC2. While this is still not a continuous replication it does provide a pathway to migrate these virtual machines onto the EC2 platform. We recommend using AWS MGN Service to migrate on-premises servers to AWS. You need to configure AWS Backup Storage Gateway https://docs.aws.amazon.com/aws-backup/latest/devguide/vm-backups.html
## Task 1: Subtask 1:  If MGN is not supported or if you have AWS Backup or other solutions already stood up and configured.
#### Description
https://www.veeam.com/vm-backup-recovery-replication-software.html &  https://www.veeam.com/kb2414#:~:text=For%20VMware%20Cloud%20on%20AWS,to%20write%20data%20to%20S3
## Task 2: Setup Disaster Recovery
#### Description
Instructions: https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/disaster-recovery-options-in-the-cloud.html
## Task 2: Subtask 1:  Use a third party DR took, e.g. , Veeam, and perform a DR failover into EC2.
#### Description
