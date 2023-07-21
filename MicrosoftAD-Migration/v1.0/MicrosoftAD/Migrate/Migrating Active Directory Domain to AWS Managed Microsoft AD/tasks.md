
# Module: Migrating Active Directory Domain to AWS Managed Microsoft AD
## Task 1: Users, Groups and computer objects migration
#### Description
ADMT can be used to migrate users from self-managed AD into AWS Managed AD. one caveat for customers is timeline of migration and importance of SID history. SID History is not transferred over during the migration. If this is a critical need, it may be a good option to consider self-managed Active Directory on EC2 instead so you can maintain this information. 
#### Tools
Active Directory Migration Tool (ADMT)
## Task 2: User Password Migration from on-premises to AWS Managed Microsoft AD
#### Description
Microsoft Password Server can be used to migrate passwords into but not out of AWS Managed Active Directory, you can review how to migrate users and password from your directory [here](https://aws.amazon.com/blogs/security/how-to-migrate-your-on-premises-domain-to-aws-managed-microsoft-ad-using-admt/).
#### Tools
Password Export Server
## Task 3: Extending AWS Managed Microsoft AD Schema
#### Description
You can use LDIF (LDAP Data Interchange Format) which is a file format used to extend the schema of an AWS Managed Microsoft AD directory. LDIF files contain the necessary information to add new objects and attributes to the directory. The file must meet the LDAP standards for syntax and must contain valid object definitions for each object it adds. Once the LDIF file is created, it must be uploaded to the directory to extend its schema. For more information on using LDIF files to extend the schema of an AWS Managed Microsoft AD directory, you can refer [here](https://docs.aws.amazon.com/directoryservice/latest/admin-guide/ms_ad_schema_extensions.html). 
## Task 4: Export and Import AD Users with CSVDE
#### Description
In some cases, you may need to export and import users to a directory without creating a trust and leveraging the Active Directory Migration tool. While not the ideal situation, [CSVDE](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/cc732101(v=ws.11)) is a command-line tool that can be used to migrate Active Directory users from one domain to another. To use CSVDE, you will need to create a CSV file containing the user information, such as usernames, passwords, and group membership. Then, you can use the csvde command to import the users into the new domain. You can also use the csvde command to export existing users from the source domain as well. This may be helpful if you’re migrating from another directory source, such as SAMBA Domain Services to Microsoft Active Directory. 