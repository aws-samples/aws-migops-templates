
# Module: Using AD connector to proxy authentication to on-premises Active Directory
## Task 1: Create DHCP Option Set
#### Description
Creation of an Amazon VPC DHCP Options Set. This allows customer-specified domain name and domain name servers (DNS) (on-premises services) to be defined. 
## Task 2: Setup Amazon Virtual Private Gateway
#### Description
Enable communication with your own network over an IPsec VPN tunnel or an AWS Direct Connect connection.
## Task 3: Setup AD Connector
#### Description
AD Connector is a directory gateway with which you can redirect directory requests to your on-premises Microsoft Active Directory without caching any information in the cloud. AD Connector comes in two sizes, small and large. You can spread application loads across multiple AD Connectors to scale to your performance needs. There are no enforced user or connection limits. Administration Guide can be found [here](https://docs.aws.amazon.com/directoryservice/latest/admin-guide/directory_ad_connector.html). 