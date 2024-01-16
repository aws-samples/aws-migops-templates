
# Module: MGN - Perform migration wave 1
## Task 1: Verify replication status
#### Description
Verify replication status of each of the source servers.
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
• Verified replication status
## Task 2: Export inventory for offline review
#### Description
Export your inventory of servers, applications, and waves to a CSV file that is saved in your local disk or an S3 bucket.
#### Tools
AWS Application Migration Service
#### Tools
Exporting your data inventory
#### Acceptance Criteria
• Export inventory data.
## Task 3: Launch test instances
#### Description
Prior to launching your instances, you must ensure that your environment is set up properly to ensure successful launches.
#### Tools
Launch test instances
#### Acceptance Criteria
• Verify test instances.
## Task 4: Run through series of tests on each test instance
#### Description
Run through series of tests on each test instance to verfy if everything looks as per the expectation.
#### Tools
Launching test instances
#### Acceptance Criteria
• Successful tests on each test instance.
## Task 5: Mark as ready for cutover
#### Description
Once you have finalized the testing of all of your source servers, mark them ready for cutover.
#### Tools
AWS Application Migration Service
#### Tools
Launching cutover instances
#### Acceptance Criteria
• Mark source server for cutover.
## Task 6: Shutdown source during cutover window
#### Description
Shutdown source servers and applications during cutover window.
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
• Source servers and applications are shut down.
## Task 7: Launch Cutover instances
#### Description
Once you have finalized the testing of all of your source servers, you are ready for cutover. You should perform the cutover at a set date and time. The cutover will migrate your source servers to the cutover instances on AWS. 
#### Tools
AWS Application Migration Service
#### Tools
Launching cutover instances
#### Acceptance Criteria
• Launch Cutover instances
## Task 8: Initiate DNS cutover
#### Description
Initiate the DNS cutover so that all network traffic will be pointed to the new instances.
#### Tools
AWS Application Migration Service
#### Acceptance Criteria
• Initiate DNS cutover
## Task 9: Test wave workload performance and correctness
#### Description
Test wave workload performance and correctness
#### Tools
AWS Application Migration Service
#### Tools
Launching cutover instances
#### Acceptance Criteria
• Wave workload test complete.
## Task 10: Finalizing a cutover
#### Description
Once you have launched your cutover instances, log into your cutover instances in order to ensure that they function correctly. Validate connectivity and perform acceptance tests for your application. f you encounter any issues and want to launch new cutover instances, you can revert the cutover.
#### Tools
AWS Application Migration Service
#### Tools
Finalize cutover instances
#### Acceptance Criteria
• Cutover finalized