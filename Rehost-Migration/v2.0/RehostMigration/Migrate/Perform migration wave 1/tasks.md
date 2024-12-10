
# Module: Perform migration wave 1
## Task 1: Install MGN Replication Agent
#### Description
This is an automated task which can executed using AWS-MGN-InstallReplicationAgent automation unit. This uses MGN Connector to install MGN replication agents on source servers. 

List of actions performed by this automated task is: 

1. Registering source servers with MGN Connector 
2. Register credentials with source servers 
3. Creating required IAM roles 
4. Verifying the prerequisites to install the MGN replication agent on the source servers 
5. Installing the AWS MGN replication agents on the source servers.
## Task 2: Verify replication status
#### Description
This is an automated task which can executed using AWS-MGN-VerifyReplicationHealth automation unit.

After you install the replication agent on the source machines, you monitor the status of data replication and resolve issues like permissions or network performance. This managed unit retries every 10 minutes until the status of every server in the wave changes to Continuous Data Replication.
## Task 3: Configure launch template
#### Description
The Launch template allows you to control the way AWS Application Migration Service launches instances in AWS. The default configuration defined in the template will be automatically applied to every newly added server. 
## Task 4: Validate launch template
#### Description
The Launch template allows you to control the way AWS Application Migration Service launches instances in AWS. The default configuration defined in the template will be automatically applied to every newly added server
## Task 5: Launch test instances
#### Description
This is an automated task which can executed using AWS-MGN-LaunchTestInstances automation unit.

After you add all of your source servers and configure their launch settings, you are ready to launch a test instance. To verify that your applications can function properly within the AWS environment, it is crucial that you test the migration of your source servers to AWS before you initiate a cutover.
## Task 6: Mark as ready for cutover
#### Description
This is an automated task which can executed using AWS-MGN-MarkReadyForCutover automation unit.

After you launch your test instances, go to the Amazon EC2 console and use SSH or RDP to connect to your test instances and ensure that the instances are functioning correctly. If you are done with your testing and are ready for cutover, you can finalize the test. This will change your migration lifecycle status of your source servers to Ready for cutover, indicating that all testing is complete and that these servers are now ready for cutover.
## Task 7: Launch Cutover instances
#### Description
This is an automated task which can executed using AWS-MGN-LaunchCutoverInstances automation unit.

After you finalize the testing of all of your source servers, you are ready for cutover. The cutover will migrate your source servers to the cutover instances on AWS.
## Task 8: Shutdown source during cutover window
#### Description
Shutdown source servers and applications during cutover window.
## Task 9: Test wave workload performance and correctness
#### Description
Test wave workload performance and correctness
## Task 10: Finalizing a cutover
#### Description
This is an automated task which can executed using AWS-MGN-FinalizeCutover automation unit.

After you perform a successful cutover and complete the migration, this automation unit changes the migration lifecycle status of your source servers to Cutover complete. This status indicates that the migration was successful. This unit also stops data replication and causes all replicated data to be discarded. All AWS resources used for data replication will be terminated.
## Task 11: MGN server archive/disconnect
#### Description
This is an automated task which can executed using AWS-MGN-ArchiveSourceServers automation unit.

This automation unit archives source servers by removing them from the main AWS MGN source servers page. Archiving allows you to focus on source servers that haven't yet been cutover.
## Task 12: DNS cutover
#### Description
Initiate the DNS cutover so that all network traffic will be pointed to the new instances.
## Task 13: Auto scaling
#### Description
