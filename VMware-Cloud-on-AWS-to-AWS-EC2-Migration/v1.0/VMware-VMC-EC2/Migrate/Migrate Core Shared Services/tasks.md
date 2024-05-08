
# Module: Migrate Core Shared Services
## Task 1: Migrate Core Shared Services
#### Description
Migrate shared services such as file shares, shared databases, shared apps, shared tools
## Task 1: Subtask 1: Migrate  File Servers to AWS.
#### Description
Windows File Server migration to AWS. Identify the AWS storage service that best meets your needs. The choice of storage service typically depends on your use case, application needs, familiarity, performance profiles, and data management capabilities. On AWS, the optimal choice could be to move it to Amazon FSx to get the same performance you had for your file server, while removing the undifferentiated heavy lifting of administering the file server and backend storage. Depending on the protocol/OS, customers will use either FSx or EFS. This gives customers the managed service experience for their file servers. You can use AWS Data Sync https://aws.amazon.com/datasync/  & Rsync https://en.wikipedia.org/wiki/Rsync or any third party solutions to migrate data on AWS. 
## Task 2: Storage - Vendor based solutions
#### Description
Amazon FSx/EFS OR Vendor solutions on marketplace
## Task 2: Subtask 1: Amazon FSx lets you choose between four widely-used file systems: NetApp ONTAP, OpenZFS, Windows File Server, and Lustre.
#### Description
Fully managed shared storage built on NetApps popular ONTAP file system https://aws.amazon.com/fsx/netapp-ontap/  & https://aws.amazon.com/fsx/