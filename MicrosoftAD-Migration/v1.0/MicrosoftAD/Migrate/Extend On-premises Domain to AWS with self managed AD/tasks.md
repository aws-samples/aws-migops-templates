
# Module: Extend On-premises Domain to AWS with self managed AD
## Task 1: Create DHCP Option Set
#### Description
Creation of an Amazon VPC DHCP options set. This allows the customer to define a specified domain name and DNSs (AD DS local). 
## Task 2: Setup Amazon Virtual Private Gateway
#### Description
Enable communication with a customer-owned network over an IPsec VPN tunnel or AWS Direct Connect connection
## Task 3: Deploy Domain Controller on Amazon EC2
#### Description
Deploy Active Directory on EC2 instances in multiple Regions with multiple virtual private clouds (VPCs). Best practices can be found [here](https://aws.amazon.com/blogs/security/securely-extend-and-access-on-premises-active-directory-domain-controllers-in-aws/).
## Task 4: Set up Active Directory Sites and services
#### Description
Sites and services are critical components for the correct function of AD DS. Site topology controls AD replication between domain controllers within the same site and across site boundaries. Defining the correct site topology ensures client affinity. Best Practices to design sites and services can be found [here](https://docs.aws.amazon.com/whitepapers/latest/best-practices-deploying-amazon-workspaces/design-considerations.html#active-directory-sites-and-services). 