
# Module: Review Existing On-premises Active Directory Design
## Task 1: Review on-premises Domain Controllers utilization data
#### Description
Leverage the Optimization and Licensing Assessment (OLA) to review the existing Domain Controllers utilization and resource consumption.
#### Tools
Assessment Central [for AWS Internal use only]
#### Tools
Request an OLA [for customer/external use]
#### Acceptance Criteria
You have collected and analyzed various metrics and logs related to their performance and resource usage.
## Task 2: Reviewing existing AD Sites-and-Services configuration
#### Description
A directory service site topology is a logical representation of your existing physical network. It is crucial to understand how your current Active Directory site topology was designed. Analyzing current AD sites and-services  involves planning for domain controller placement and designing sites, subnets, site links, and site link bridges to ensure efficient routing of query and replication traffic. Designing a site topology helps you efficiently route client queries and Active Directory replication traffic.
#### Tools
Designing the Site Topology
## Task 3: Verify the health of existing Active Directory infrastructure
#### Description
Domain controllers are critical to the success of a migration or the addition of new domain controllers to an existing domain. As a result, knowing how to check on their status is critical. Native Microsoft tools can be used to run a health check on Active Directory domain controllers.
#### Tools
Ntdsutil to identify issues with Active Directory Database
#### Tools
Ddiagc a command-line tool to identify abnormal behavior in the system
#### Tools
Repadmin to identify the replication problems
#### Acceptance Criteria
You have leveraged the built-in tools and utilities provided by Microsoft for managing and monitoring Active Directory, such as Event Viewer, Active Directory Users and Computers, Active Directory Sites and Services, and PowerShell cmdlets.
## Task 4: Name Resolution and DNS Design
#### Description
You must construct a Domain Name System (DNS) infrastructure to support your Active Directory logical structure after you have created your Active Directory forest and domain designs. DNS allows users to connect to computers and other resources on IP networks by using friendly names that are easy to remember. Whether your environment already has an existing DNS Server service or is deploying a new DNS Server service, the procedure for developing DNS to support AD DS differs.
#### Tools
Integrating AD DS into an Existing DNS Infrastructure
#### Tools
Deploying Domain Name System (DNS)
#### Acceptance Criteria
Validated that the DNS infrastructure is correctly configured to support AD services and name resolution.
## Task 5: Consider Active Directory Implementation Options
#### Description
AWS provides a comprehensive set of services and tools for deploying Microsoft Windows workloads on its reliable and secure cloud infrastructure. AWS Active Directory Connector (AD Connector) and AWS Managed Microsoft AD are fully managed services that allow you to connect AWS applications to an existing Active Directory or host a new Active Directory in the cloud. Together, with the ability to deploy self-managed Active Directory in Amazon EC2 instances, these services cover all cloud and hybrid scenarios for enterprise identity services.
**Note:** If you are thinking of migrating on-premises Active Directory to AWS Managed AD, an important consideration is the importance of Security Identifier (SID) History. SID History is not transferred over during the migration. If supporting SID History is a critical need, then consider using self-managed Active Directory on Amazon EC2 instead so that you can maintain SID History.
#### Tools
Directory services options in AWS
#### Acceptance Criteria
You have considered factors such as the complexity of your AD requirements, the level of control and management you desire, and your budget.
#### Acceptance Criteria
You have assessed your specific needs and evaluated the features and limitations of each option to make the right choice.