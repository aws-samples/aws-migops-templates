
# Module: Review Existing AWS Infrastructure Design
## Task 1: Review Classless Inter-Domain Routing (CIDR)
#### Description
In traditional on-premises networking you assign Classless Inter Domain Routing (CIDR) ranges to your LAN for private communication. Similarly, when creating networks in your cloud environment you also need to assign non-overlapping CIDR ranges to your network. Non-overlapping IP spaces allow you to build optimal routing that helps enhance your network performance and avoids intermittent connectivity issues and communication failures. There are cases were overlapping IP ranges cannot be avoided and it is important to design network routes or translation devices to ensure the communication between these networks performs as expected. When planning your network CIDR range, we recommend that you leverage a contiguous CIDR range for geographic regions, locations, or even services. By grouping your CIDRs you can classify or categorize them to help administrators easily identify and appropriately create routes.
#### Tools
Designing CIDR Block
#### Acceptance Criteria
- The CIDR block doesn't overlap with any existing CIDR block.

#### Acceptance Criteria
- Validated that it is not required to increase or decrease the size of an existing CIDR block.
#### Acceptance Criteria
- You have a quota on the number of CIDR blocks you can use with VPC.
## Task 2: Review IP Address Utilization
#### Description
An important aspect of planning and designing your network is to ensure the risk of IP address exhaustion is mitigated. IP exhaustion happens when the number of IP addresses you need in a given network is greater than the IP addresses available. This is a big risk in the cloud environments due to the elasticity the cloud provides. As your workloads scale up and down, they consume more IP addresses in the given network. If there are no IPs available in your network, scaling will fail and you are at risk of having service impairment. When planning, you need to ensure that the IP range is large enough to accommodate networking and non-networking resources in your cloud environment. Addressing the size of the CIDR for current and future uses should be considered in planning.
#### Tools
Best Practices for sizing subnets
#### Acceptance Criteria
Referred to the network documentation to find out about static IP assignments, subnets, and other network-related information. Cross-check the documentation with the actual network to ensure accuracy.
## Task 3: Review Virtual networks
#### Description
Virtual networks allow you to isolate resources from one another based on your operational requirements. Leveraging virtual networks enables your team to define a strict network boundary between resources, which can ensure network isolation and mitigate risk of resources in one virtual network from access resources in another virtual network. For example, developers can have separate networks to create and develop resources isolated from production workloads. Issues or risky activity developers are taking within one virtual network will not impact network resources within another virtual network. At this stage, you should gauge short- and long-term projects that might affect network topologies such as merging of organizations, large data center migrations, and adoption of new vendors or technologies. Network admins and leadership should be ready to define virtual networks and restructure sub-networks and routing, and switching and physical layer networking modifications to establish communication across their network.
#### Tools
Understanding VPC (Virtual Private Cloud)
#### Acceptance Criteria
Reviewed existing VPCs and collected information such as the VPC ID, name, IPv4 CIDR block, and other relevant details for each VPC.
#### Acceptance Criteria
Checked associated resources such as EC2 instances, load balancers, NAT gateways, Internet gateways, VPN connections, and any other resources that rely on the VPC for network connectivity.
## Task 4: Review Network configuration and management
#### Description
The network is the backbone of any IT infrastructure. Whether its post deployment operational issues or troubleshooting, you often need to make changes to individual components in the network, resulting in changes to the overall topology. These changes include modifications of route tables, allocation of new private and public IP addresses, and troubleshooting (connectivity, packet loss, throughput, bandwidth consumption, or latency issues) within and outside each team’s resources and your organization. A robust network architecture reduces the needs to make major changes to your network topology when any of these scenarios are encountered. You can use AWS Cli to retrieve existing network configuration in AWS. 
#### Tools
Retrieve details about the route tables in your VPCs
#### Tools
Retrieves information about VPN connections in your AWS account
#### Tools
Gather details about the network access control lists (NACLs)
#### Tools
Lists the security groups in your AWS account
#### Tools
Retrieves information about the subnets in your VPCs
#### Tools
Lists all the VPCs in your AWS account
#### Tools
Obtain details about the internet gateways in your VPCs
#### Tools
Collect information about NAT gateways in your AWS account
#### Acceptance Criteria
Existing network configuration and settings are discovered and documented.
## Task 5: Planning for Hybrid Network Setup
#### Description
As customers build their cloud environment it is common to have workloads on-premises and across different cloud providers. You might have connectivity requirements that you need to satisfy, so your workloads can communicate across different networks and environments. Regardless of the type of connectivity options you choose between your on-premises environment and your cloud environments, ensure high availability and redundancy for your communication channel. Routing maintenance, upgrades, other unexpected network, electrical incidences, and natural events can disrupt your primary connection. In these scenarios, a secondary (or fail over) connection might be required to avoid outages.
#### Acceptance Criteria
Conducted thorough testing to ensure that network connectivity and data transfer between your on-premises network and AWS resources function as expected.
#### Acceptance Criteria
Considered implementing redundancy, failover mechanisms, and backup strategies to ensure high availability and business continuity.
#### Acceptance Criteria
Considered to implement network monitoring and management.
#### Acceptance Criteria
Managed IP address ranges to ensure there is no IP address range overlap between your on-premises network and the AWS VPC to avoid conflicts. Consider using VPC peering or AWS-provided IP address space for seamless integration.
#### Acceptance Criteria
Decided what to implement for network security such as Network ACLs, Security Group and VPN and Direct Connect Encryption.
#### Acceptance Criteria
Decided on network connectivity options: Direct Connect or VPN (Virtual Private Network).
## Task 6: Workload discovery on AWS
#### Description
Monitoring your Amazon Web Services (AWS) Cloud workloads is key to maintaining operational health and efficiency. However, keeping track of the AWS resources and the relationships between them can be a challenge. Workload Discovery on AWS is a visualization tool that automatically generates architecture diagrams of AWS Cloud workloads. You can use the solution to build, customize, and share detailed workload visualizations based on live data from AWS.
#### Tools
Workload Discovery on AWS
#### Acceptance Criteria
You have visibility into the dependencies between different components of applications, which helps understand the relationships and data flows.
#### Acceptance Criteria
You have a comprehensive view of existing infrastructure and workloads which identify and catalog the applications, services and dependencies.