
# Module: Designing Active Directory in AWS
## Task 1: AWS Applications to leveraged with Active Directory
#### Description
You can enable multiple AWS applications and services such as [AWS Client VPN](https://aws.amazon.com/vpn/), [AWS Management Console](https://aws.amazon.com/console/), [AWS IAM Identity Center (successor to AWS Single Sign-On)](https://aws.amazon.com/iam/identity-center/), [Amazon Chime](https://aws.amazon.com/chime/), [Amazon Connect](https://aws.amazon.com/connect/), [Amazon FSx](https://aws.amazon.com/fsx/windows/), [Amazon QuickSight](https://aws.amazon.com/quicksight/), [Amazon RDS for SQL Server(Only Applicable for AWS Managed Active Directory)](https://aws.amazon.com/rds/sqlserver/), [Amazon WorkDocs](https://aws.amazon.com/workdocs/), [Amazon WorkMail](https://aws.amazon.com/workmail/), and [WorkSpaces](https://aws.amazon.com/workspaces/) to use your AWS Managed Microsoft AD directory. When you enable an AWS application or service in your directory, your users can access the application or service with their AD credentials. Using familiar AD administration tools, you can apply AD group policy objects (GPOs) to centrally manage your Amazon EC2 for Windows or Linux instances by [joining your instances to your AWS Managed Microsoft AD domain](https://docs.aws.amazon.com/en_us/directoryservice/latest/admin-guide/ms_ad_join_instance.html).
## Task 2: Use Active Directory with Console Logons
#### Description
AWS Directory Service allows you to grant members of your directory access to the AWS Management Console. By default, your directory members do not have access to any AWS resources. You assign IAM roles to your directory members to give them access to the various AWS services and resources. The IAM role defines the services, resources, and level of access that your directory members have.
#### Tools
Access the AWS Management Console Using AWS Microsoft AD
#### Tools
Active Directory Sync with IAM Identity Center
## Task 3: Design Active Directory Sites and Services
#### Description
Sites and services are critical components for the correct function of AD DS. Site topology controls AD replication between domain controllers within the same site and across site boundaries. Defining the correct site topology ensures client affinity, meaning that clients use their preferred local domain controller. Refer to this [document](https://docs.aws.amazon.com/whitepapers/latest/best-practices-deploying-amazon-workspaces/design-considerations.html) to understand how to define AD Sites and Services.
## Task 4: Using AD connector to proxy authentication to on-premises Active Directory Service
#### Description
This is for customers who don’t want to extend their on-premises AD service into AWS, or where a new deployment of AD DS is not an option. [In this scenario](https://https://docs.aws.amazon.com/whitepapers/latest/best-practices-deploying-amazon-workspaces/scenario-1-using-ad-connector-to-proxy-authentication-to-on-premises-active-directory-service.html), AWS Directory Service (AD Connector) is used for all user or MFA authentication that is proxied through the AD Connector to the customer on-premises AD DS.

## Task 5: Extending on-premises Active Directory into AWS (replica)
#### Description
[In this Scenario](https://https://docs.aws.amazon.com/whitepapers/latest/best-practices-deploying-amazon-workspaces/scenario-2-extending-on-premises-ad-ds-into-aws-replica.html), a replica of the customer AD DS is deployed on AWS in combination with AD Connector. This reduces latency of authentication or query requests to AD DS running on Amazon Elastic Compute Cloud (Amazon EC2).
## Task 6: Standalone isolated deployment using AWS Directory Service in the AWS Cloud
#### Description
[In this scenario](https://https://docs.aws.amazon.com/whitepapers/latest/best-practices-deploying-amazon-workspaces/scenario-3-standalone-isolated-deployment-using-aws-directory-service-in-the-aws-cloud.html), Active Directory is deployed in the AWS Cloud in a standalone isolated environment. AWS Directory Service is used exclusively in this scenario. Instead of fully managing AD DS, customers can rely on AWS Directory Service for tasks such as building a highly available directory topology, monitoring domain controllers, and configuring backups and snapshots.
## Task 7: AWS Managed Microsoft AD and a two-way transitive trust to on-premises
#### Description
[In this scenario](https://https://docs.aws.amazon.com/whitepapers/latest/best-practices-deploying-amazon-workspaces/scenario-4-aws-microsoft-ad-and-a-two-way-transitive-trust-to-on-premises.html), AWS Managed AD is deployed in the AWS Cloud, which has a two-way transitive trust to the customer on-premises AD. Users and WorkSpaces are created in the Managed AD, with the AD trust enabling resources to be accessed in the on-premises environment.
## Task 8: AWS managed Microsoft AD using a shared services Virtual Private Cloud (VPC)
#### Description
[In this scenario](https://https://docs.aws.amazon.com/whitepapers/latest/best-practices-deploying-amazon-workspaces/scenario-5-aws-microsoft-ad-using-a-shared-services-virtual-private-cloud-vpc.html), an AWS Managed AD is deployed in the AWS Cloud, providing authentication services for workloads that are either already hosted in AWS or are planned to be as part of a broader migration. The best practice recommendation is to have Amazon WorkSpaces in a dedicated VPC. Customers should also create a specific AD OU to organize the WorkSpaces computer objects.
## Task 9: AWS managed Microsoft AD, shared services VPC, and a one-way trust to on-premises
#### Description
[In this scenario](https://https://docs.aws.amazon.com/whitepapers/latest/best-practices-deploying-amazon-workspaces/scenario-6-aws-microsoft-ad-shared-services-vpc-and-a-one-way-trust-to-on-premises.html), we use an existing on-premises Active Directory for users, and introduces a separate Managed Active Directory in AWS Cloud to host the computer objects associated with the WorkSpaces. This scenario allows the computer objects and Active Directory group policies to be managed independently from the corporate Active Directory.

This scenario is useful when a third party wants to manage Windows WorkSpaces on a customer’s behalf as it allows the third party to define and control the WorkSpaces and policies associated with them, without a need to grant the third-party access to the customer AD. In this scenario, a specific Active Directory organizational unit (OU) is created to organize the WorkSpaces computer objects in the Shared Services AD.