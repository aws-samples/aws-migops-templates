
# Module: MGN setup
## Task 1: Initialize MGN
#### Description
AWS Application Migration Service (MGN) is a highly automated lift-and-shift (rehost) solution that simplifies, expedites, and reduces the cost of migrating applications to AWS. It allows companies to lift-and-shift a large number of physical, virtual, or cloud servers without compatibility issues, performance disruption, or long cutover windows
## Task 2: Import inventory into MGN
#### Description
Import your inventory of source servers, applications and waves, from local file.
## Task 3: Create IAM roles for MGN
#### Description
Create the following roles as pre-requisite for installing MGN Connector. 

1. MGNConnectorInstallerRole
2. AWSApplicationMigrationConnectorManagementRole
3. AWSApplicationMigrationConnectorSharingRole_Account-ID

For more details, see [Create permissions for MGN Connector.](https://docs.aws.amazon.com/mgn/latest/ug/mgn-connector-permissions.html#create-permissions-manually)
## Task 4: Install MGN connector
#### Description
After all IAM roles are created as pre-requisites in the previous task, add MGN connector using the following steps: 

1. Obtain the SSM hybrid activation parameters
2. Temporary IAM credentials of the MGNConnectorInstallerRole
3. Download the MGN connector software 

For more details, see [Add connector.](https://docs.aws.amazon.com/mgn/latest/ug/add-connector.html)