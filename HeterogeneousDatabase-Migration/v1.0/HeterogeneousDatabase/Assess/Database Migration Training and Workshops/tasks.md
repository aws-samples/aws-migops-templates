
# Module: Database Migration Training and Workshops
## Task 1: Understand the database services that are available in AWS
#### Description
Database migration workshops are designed to introduce users to the available cloud-native database services and capabilities that AWS offers. In addition, the workshop provides a deeper dive on Amazon Aurora PostgreSQL. The workshop also draws a parallel between the source and target databases in terms of features and architecture, which is important from a heterogenous-database-migration standpoint.  

For a complete list of source and target databases that the AWS Database Migration service supports, see the following resources: 

1) [Sources for data migration](https://docs.aws.amazon.com/dms/latest/userguide/CHAP_Source.html)
2) [Targets for data migration](https://docs.aws.amazon.com/dms/latest/userguide/CHAP_Target.html)
#### Acceptance Criteria
• Understood the different types of cloud-native databases offered by AWS
## Task 1: Subtask 1: Introduction to Amazon Aurora
#### Description
Amazon Aurora is a fully managed relational database engine that's compatible with both MySQL and PostgreSQL. 

[Immersion day � Introduction to Amazon Aurora](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/Introduction_to_Amazon_Aurora.pdf)

[Amazon Aurora User Guide](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html)

#### Acceptance Criteria
• Understood the features, capabilities< and architecture of Amazon Aurora
#### Acceptance Criteria
• Understood the primary use cases for Amazon Aurora 
## Task 1: Subtask 2: Understand Amazon Aurora monitoring and Performance Insights.
#### Description
Amazon Aurora monitoring and Performance Insights provide additional and more granular information about the database load and performance characteristics. 

For more information, see [here](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/Monitoring%20and%20Performance%20Insights_final.pdf).
#### Acceptance Criteria
• Understood the features and capabilities offered with Amazon Aurora monitoring and Performance Insights
## Task 1: Subtask 3: Explore the similarities and differences between Oracle PL SQL and PostgreSQL PL pgSQL.
#### Description
Most users migrating from Oracle prefer a PostgreSQL-based target like AWS Aurora for PostgreSQL because of the similarities between the Oracle PL/SQL and PostgreSQL PL/pgSQL procedural languages. Migrating from Oracle to PostgreSQL is often easier when compared to other target database engines. This task helps users learn about the similarities and differences in SQL syntax between PostgreSQL and Oracle.

For more information, see [Training PostgreSQL for Oracle Users](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/PostgreSQL%20for%20Oracle%20Users.pdf).
#### Acceptance Criteria
• Understood the similarities and differences between Oracle and PostgreSQL SQL syntax
## Task 1: Subtask 4: Learn about Oracle PostgreSQL PL pgSQL
#### Description
Most users migrating from Oracle prefer a PostgreSQL-based target like AWS Aurora for PostgreSQL because of the similarities between the Oracle PL/SQL and PostgreSQL PL/pgSQL procedural languages. Migrating from Oracle to PostgreSQL is often easier when compared to other target database engines. This task helps users learn about PL/pgSQL and the similarities and differences with Oracle�s PL/SQL. 

For more information, see [Training-PLpgSQL](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/PLpgSQL.pdf).

#### Acceptance Criteria
• Understood the similarities and differences between the syntaxes of Oracle and PostgreSQL PL/pgSQL
## Task 1: Subtask 5: Learn about PostgreSQL performance
#### Description
Performance tuning is an important task for any database migration project, especially in heterogenous migrations when switching between database engines. In this task, you learn about the performance capabilities of PostgreSQL and study examples of PostgreSQL database tuning.

For more information, see [Immersion Day - PostgreSQL Performance](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/performanceaupgid.pdf).
#### Acceptance Criteria
• Understood PostgreSQL Query Planner statistics
#### Acceptance Criteria
• Understood PostgreSQL indexes
#### Acceptance Criteria
• Understood the PostgreSQL Query Optimizer
## Task 1: Subtask 6: Learn about partitioning in PostgreSQL
#### Description
Table partitioning is a key feature of the PostgreSQL database that allows enhanced performance and availability advantages when dealing with very large volumes of data. In this task, you learn about table partitioning in PostgreSQL, its benefits, features, and capabilities.

[Immersion Day � Partitioning in PostgreSQL](https://github.com/aws-samples/aws-migops-guidance/blob/main/HeterogeneousDatabase-Migration/v1.0/DatabaseMigration/.attachments/DatabaseMigration/partitioning_postgress.pdf).
#### Acceptance Criteria
• Understanding the benefits of table partitioning
#### Acceptance Criteria
• Understanding how partitioning works in a PostgreSQL database
#### Acceptance Criteria
• Understanding the various PostgreSQL-specific table partitioning features and capabilities 
## Task 2: Learn about AWS migration tools
#### Description
AWS offers several tools to accelerate the migration of databases into cloud-native database technologies. Amazon Database Migration Service (DMS) and Amazon Schema Conversion Tool (SCT) both offer automation around heterogenous real-time data replication and conversion of database schema and artifacts between different database engines. In this task you learn how to get started with Amazon DMS and SCT and learn about the different features and capabilities of each.

#### Acceptance Criteria
• Understood the role of Amazon Schema Tool (SCT) in a database migration project 
#### Acceptance Criteria
• Understood the features and capabilities of SCT
#### Acceptance Criteria
• Understood how to use SCT to convert a source database schema to the target database dialect
#### Acceptance Criteria
• Understood the role of Amazon Database Migration Service (DMS) in a database migration project 
#### Acceptance Criteria
• Understood the features and capabilities of Amazon DMS
#### Acceptance Criteria
• Understood how to use DMS to replicate data in a heterogenous database environment 