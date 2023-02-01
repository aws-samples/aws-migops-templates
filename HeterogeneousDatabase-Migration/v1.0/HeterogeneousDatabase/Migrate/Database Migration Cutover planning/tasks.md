
# Module: Database Migration Cutover planning
## Task 1: Database migration cutover planning 
#### Description
The database cutover strategy is tightly coupled with the downtime requirements for the application. Strategies that you can use for the database cutover include the following:

1) Offline migration
2) Flash-cut migration
3) Active/active database configuration
4) Incremental migration

For more information, see [here](https://docs.aws.amazon.com/prescriptive-guidance/latest/strategy-database-migration/cut-over.html).
#### Tools
AWS Database Migration Service (AWS DMS)
#### Acceptance Criteria
• Complete database migration cutover to new databases
## Task 2: Database migration rollback planning
#### Description
When migrating a database, it is important to have a rollback strategy in case the migration doesn't go as expected. There are four basic strategies for rolling back from a migration: 

1) Basic fallback
2) Fall forward
3) Dual write
4) Bidirectional replication

For more information, see [here](https://aws.amazon.com/blogs/database/rolling-back-from-a-migration-with-aws-dms).

#### Tools
AWS Database Migration Service (AWS DMS)
#### Acceptance Criteria
• Successfully rolled back the migration