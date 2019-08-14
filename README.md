---
page_type: sample
languages:
- java
products:
- azure
services: Sql
platforms: java
author: yaohaizh
---

## Getting Started with Sql - Getting Sql Server Metrics - in Java ##


  Azure SQL sample for getting SQL Server and Databases metrics
   - Create a primary SQL Server with a sample database.
   - Run some queries on the sample database.
   - Create a new table and insert some values into the database.
   - List the SQL subscription usage metrics, the database usage metrics and the other database metrics
   - Use the Monitor Service Fluent APIs to list the SQL Server metrics and the SQL Database metrics
   - Delete Sql Server
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/sql-database-java-get-sql-metrics.git

    cd sql-database-java-get-sql-metrics

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.