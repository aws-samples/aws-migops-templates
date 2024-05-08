
# Module: Migrate Core Shared Services
## Task 1: Migrate Core Shared Services
#### Description
Migrate shared services such as file shares, shared databases, shared apps, shared tools
## Task 1: Subtask 1: Migrate  File Servers to AWS.
#### Description
Windows File Server migration to AWS. Identify the AWS storage service that best meets your needs. The choice of storage service typically depends on your use case, application needs, familiarity, performance profiles, and data management capabilities. On AWS, the optimal choice could be to move it to Amazon FSx to get the same performance you had for your file server, while removing the undifferentiated heavy lifting of administering the file server and backend storage.
## Task 1: Subtask 2: Setup AWS Migration Hub and other tools
#### Description
Leverage AWS Migration Hub to orchestrate your migrations to AWS. Setup a home region for the service to store your data.
## Task 1: Subtask 3: Active Directory domain controllers options on AWS
#### Description
Active Directory is a typical identity and access management solution for many corporate environments. The coupling of DNS, user, and machine management makes Active Directory an ideal choice for both Microsoft and Linux workloads for centralized user authentication. When you're planning your journey to the cloud or to AWS, you're faced with the choice of extending Active Directory into AWS or using a managed service to offload the management of the directory service infrastructure. We recommend that you understand the risks and benefits of each option when deciding the right approach for your organization.
#### Tools
Migrating Active Directory on AWS options