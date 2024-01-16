
# Module: Identify SQL Server database migration strategies
## Task 1: Homogeneous database migration for SQL Server
#### Description
AWS offers you the ability to run SQL Server databases in a cloud environment. For developers and database administrators, running SQL Server database in the AWS Cloud is very similar to running SQL Server database in a data center. You have below options for running SQL Server on AWS. Visit the below links to learn more.
* **[SQL Server on Amazon RDS](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-sql-server/rds-sql.html)** - Managed service, provides easy provisioning and licensing, cost-effective, easy to set up, manage, and maintain.
* **[SQL Server on Amazon RDS Custom](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-sql-server/rds-custom-sql.html)** - Managed service, but you retain administrative rights to the database and the underlying operating system.
* **[SQL Server on Amazon EC2](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-sql-server/ec2-sql.html)** - Self-managed, provides full control and flexibility.
* **[SQL Server on VMware Cloud on AWS](https://docs.aws.amazon.com/prescriptive-guidance/latest/migration-sql-server/vmware-sql.html)** - Set up, scale, and operate your SQL Server workloads on VMware Cloud on AWS 
## Task 2: Heterogeneous database migration for SQL Server
#### Description
Because of the innovations and improvements in open-source databases and cloud computing platforms like AWS, many organizations are moving from proprietary (online transaction processing or OLTP) database engines such as SQL Server to open-source engines. SQL Server databases are mission-critical systems for any organization, but being locked into a particular vendor is a risky and costly situation. Low operating cost and no licensing fees are compelling reasons to consider switching the underlying database technology to open-source or AWS Cloud-native databases.

Other reasons for migrating off SQL Server are vendor lock-in periods, licensing audits, expensive licensing, and cost. For this reason, many organizations choose to migrate their SQL Server databases to either open-source databases (such as PostgreSQL, MySQL, or MariaDB) or AWS Cloud-native databases (such as Amazon Aurora or Amazon DynamoDB) when they migrate to AWS.

You can also migrate your SQL Server data warehouse database to Amazon Redshift, which is a fast, fully managed cloud data warehouse. Amazon Redshift is integrated with your data lake, offers up to three times faster performance than any other data warehouse, and costs up to 75 percent less than any other cloud data warehouse. You can find various tools from AWS which can helps you with heterogeneous migration.
#### Tools
Babelfish
#### Tools
AWS DMS
#### Tools
AWS SCT
## Task 2: Subtask 1: Explore the AWS Purpose Built databases
#### Description
AWS offers 15+ purpose-built engines to support diverse data models, including relational, key-value, document, in-memory, graph, time series, wide column, and ledger databases. In this Migration Journey we will focus on **Relational databases** for heterogeneous target.

**Relational** 	Traditional applications, ecommerce, OLTP transactions 	

    Amazon Aurora - MySQL and PostgreSQL compatible
    Amazon RDS - SQL Server, MySQL, PostgreSQL and MariaDB
    Babelfish for Aurora PostgreSQL  :  Babelfish for Aurora PostgreSQL is a new capability for Amazon Aurora PostgreSQL-Compatible Edition that enables Aurora to understand commands from applications written for Microsoft SQL Server.
		
**Key-value **	High-traffic web applications, ecommerce systems, gaming applications, financial trading 	

    Amazon DynamoDB
    Amazon Keyspaces

**Document** 	Content management, catalogs, user profiles 	

    Amazon DocumentDB

**OLAP** 	Traditional data warehousing, multi-tenant BI applications 	

    Amazon Athena
    Amazon Redshift

**In-memory** 	Caching, session management, gaming leaderboards, geospatial applications 	

    Amazon Elasticache
    Amazon MemoryDB for Redis

**Search** 	Consolidated logging, personalized search 	

    Amazon OpenSearch

**Graph** 	Fraud detection, social Networking, user profiles 	

    Amazon Neptune

**Ledger** 	Systems of record, supply chain, registrations, banking transactions 	

    Amazon QLDB

**Time series** 	IoT, DevOps, industrial telemetry 	

    Amazon Timestream


#### Tools
AWS Purpose Built Databases
#### Acceptance Criteria
Understand the different open source relational database engine.