
# Module: Build and Test
## Task 1: Migrate data
#### Description
Migrating data from Mainframe environments to AWS involves the following: 

1) Database migration schema conversion. This step must be performed on the entire database infrastructure. 
2) Database migration code transformation. This step can be performed on the entire database infrastructure. 
3) Load data from source database to target database. Ensure that the replication instance is set up and endpoints for both source and target are available before you run the AWS Database Migration Service.


#### Acceptance Criteria
• Converted to the target schema.
#### Acceptance Criteria
• A target database with loaded data.
## Task 2: Set up a CICD pipeline
#### Description
AWS Mainframe Modernization provides the ability to set up builds and continuous integration/continuous delivery (CI/CD) pipelines for migrated applications. These builds and pipelines use AWS CodeBuild, AWS CodeCommit, and AWS CodePipeline to provide these capabilities. 
AWS CodeBuild is a fully managed build service that compiles your source code, runs unit tests, and produces artifacts that are ready to deploy. 
AWS CodeCommit is a version control service that enables private storage and management of Git repositories in the AWS Cloud. 
AWS CodePipeline is a continuous delivery service that enables you to model, visualize, and automate the steps required to release your software.
#### Acceptance Criteria
• Set up build and CI/CD pipelines in the migrating environments
## Task 3: Migrate app programs
#### Description
Mainframe migrations to AWS usually follow two different strategies: 

1) Refactor
2) Replatform

This task must be done iteratively until all mainframe application workloads are migrated to AWS runtime environments. For more information on mainframe applications, see [here](https://docs.aws.amazon.com/m2/latest/userguide/applications-m2.html).

#### Acceptance Criteria
• Completed mainframe app migration to AWS for POC.
## Task 3: Subtask 1: Scale environments up or down
#### Description
Depending on the size of mainframe application workloads to be migrated to AWS, runtime and database environments can be scaled up or down. For more information, see [here](https://docs.aws.amazon.com/m2/latest/userguide/create-environments-m2.html).
#### Acceptance Criteria
• Finalized runtime environments for the migration
## Task 3: Subtask 2: Modernize work package
#### Description
Do the following to modernize the mainframe work packages:   
� Migrate source code  
� Migrate data schema  
� Generate packaging and deployment scripts  
#### Acceptance Criteria
• Created work packages for the migration
## Task 3: Subtask 3: Perform code sanity checks
#### Description
Perform code sanity checks to ensure that test results match the expected results. 
#### Acceptance Criteria
• Completed code sanity checks.
## Task 3: Subtask 4: Resynch with source code
#### Description
Resynchronize with the mainframe source code and ensure that the application functionalities are the same. 
#### Acceptance Criteria
• Completed code sync. 
## Task 4: Test and verify
#### Description
After all the selected apps are migrated to AWS, verify that the source and target test results match each other. Perform the following steps: 

1)	Collect initial data
2)	Stage environment, application, and data
3)	Record test scenarios on the mainframe
4)	Build test scenario automation 
5)	Run test scenarios on the cloud
6)	Compare source and target test results
7)	Generate KPIs and reports
#### Acceptance Criteria
• Tested and validated selected mainframe applications in AWS
## Task 5: Integrate
#### Description
Once the migration of application components is done in AWS, integrate all the components such as applications, databases etc. and ensure communication between components is successful. 

In case additional components are required, develop them in a custom approach or using AWS tools. In addition to communication, ensure the data handshake between components is secure. 
#### Acceptance Criteria
• Completed integration of application components.
## Task 6: Validate
#### Description
Now that the migrated environments are completed, validate the environments and applications. Perform the following steps to ensure that validation is complete. 
1)	Run integration and system testing
2)	Run performance testing
3)	Run user acceptance testing
4)	Run HA/DR testing
#### Acceptance Criteria
• Completed successful validation