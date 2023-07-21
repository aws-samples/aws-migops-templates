
# Module: Extend On-premises Domain to AWS with AWS Managed Microsoft AD
## Task 1: Create DHCP Option Set
#### Description
Creation of an Amazon VPC DHCP options set. This allows the customer to define a specified domain name and DNSs (AD DS local).
## Task 2: Setup Amazon Virtual Private Gateway
#### Description
Enable communication with a customer-owned network over an IPsec VPN tunnel or AWS Direct Connect connection
## Task 3: Setup AWS Managed Active Directory in AWS
#### Description
Setup the AWS Managed Active Directory in AWS using [Launch Wizard](https://aws-quickstart.github.io/quickstart-microsoft-activedirectory/).
#### Tools
Active Directory Domain Services on the AWS Cloud—Quick Start
## Task 4: Establish a one-way trust
#### Description
Establish a one-way transitive trust between the AWS Managed Microsoft AD and the on-premises AD. A forest trust is used per Microsoft recommendation to ensure that Kerberos authentication is used whenever possible. You can refer to this [document](https://docs.aws.amazon.com/directoryservice/latest/admin-guide/ms_ad_setup_trust.html) for details steps.
## Task 5: Establish two-way forest Trust
#### Description
Two-way trusts are bidirectional trusts that allow authentication referrals from either side of the trust to give users access resources in either domain or forest. A two-way trust is required for AWS Enterprise Apps such as Amazon Chime, Amazon Connect, Amazon QuickSight, AWS IAM Identity Center (successor to AWS Single Sign-On), Amazon WorkDocs, Amazon WorkMail, Amazon WorkSpaces, and the AWS Management Console. AWS Managed Microsoft AD must be able to query the users and groups in your self-managed AD.