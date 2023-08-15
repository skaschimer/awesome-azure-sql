# Awesome Azure SQL resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated awesome list of resources for taking advantage of everything Azure SQL has to offer, useful for the beginners and the veterans.

Please note that the readme file is autogenerated. Check out [here](CONTRIBUTE.md) to learn how to contribute (hint: it's super easy!).

- [Getting Started](#getting-started)
- [Labs & Workshops](#labs--workshops)
- [Microsoft Learn](#microsoft-learn)
- [Best Practices](#best-practices)
- [Shows](#shows)
- [Community](#community)
- [Code Samples](#code-samples)
  - [Generic](#generic)
  - [Big Data](#big-data)
  - [Change Stream](#change-stream)
  - [Data Loading](#data-loading)
  - [DevOps](#devops)
  - [Dynamic Schema](#dynamic-schema)
  - [Full Stack](#full-stack)
  - [Geospatial](#geospatial)
  - [Graph](#graph)
  - [GraphQL](#graphql)
  - [Jamstack](#jamstack)
  - [REST](#rest)
  - [ScriptDOM](#scriptdom)
  - [Streaming](#streaming)
- [Articles](#articles)
- [Scripts](#scripts)
- [Tools](#tools)
- [Libraries](#libraries)
  - [.NET](#.net)
  - [Node](#node)
  - [Python](#python)
- [DevOps](#devops)
- [Administration](#administration)
- [Migration](#migration)
- [Security](#security)
- [Videos](#videos)
  - [Azure Friday](#azure-friday)
  - [Microsoft Build 2023](#microsoft-build-2023)
- [Conferences](#conferences)
- [Books](#books)
- [Blogs](#blogs)
  - [Official](#official)
- [Social Media](#social-media)

---

## Getting Started

- :tv: [A Full Stack Application with Azure SQL & Prisma for Beginners](https://www.youtube.com/playlist?app=desktop&list=PLlrxD0HtieHiQEYJ-8SyKDAFJDVCII1fB): A series of 37 videos to learn how to build a full-stack application with Typescript, Node, Prisma and Azure SQL

- :tv: [Azure SQL for Beginners](https://aka.ms/azuresql4beginners): 61 small videos to learn everything to get started

- :tv: [Azure SQL Performance Troubleshooting](https://www.youtube.com/playlist?list=PLlrxD0HtieHgDkZ84FfCSDLBcJmUn8ktU): 7 videos dedicated to performance troubleshooting

- :tv: [Jamstack/Fullstack solution from zero to hero](https://github.com/Azure-Samples/azure-sql-db-fullstack-serverless-kickstart): Fullstack/Jamstack solution with Vue.js, Azure Functions, Azure Static Web apps and Azure SQL

- :tv: [Programming Databases with T-SQL for Beginners](https://www.youtube.com/playlist?list=PLlrxD0HtieHj551_lUtce08JUnTMY-y-R): 8 videos to learn T-SQL 

## Labs & Workshops

- :closed_lock_with_key: [Security Workshop](https://github.com/David-Seis/SecureYourAzureData): Workshop: SQL Server Security Ground to Cloud

- :bar_chart: [SQL Workshops](https://aka.ms/sqlworkshops): labs and workshops on Azure SQL (and more)

## Microsoft Learn

-  [Azure SQL fundamentals](https://aka.ms/azuresqlfundamentals): Learn how to translate your existing SQL Server expertise to Azure SQL including Azure SQL Database and Azure SQL managed instance.

-  [Azure SQL Modules @ Microsoft Learn](https://docs.microsoft.com/en-us/learn/browse/?expanded=azure&products=azure-sql-database): all the Microsoft Learn modules related to Azure SQL. From security to development, from performances to maintenance.

-  [Build Serverless Full Stack Apps on Azure](https://docs.microsoft.com/en-us/learn/paths/build-serverless-full-stack-apps-azure/): learn how to create, build, and deploy modern full stack applications in Azure by using the language of your choice (Python, Node.js, or .NET) and with a Vue.js frontend. Topics covered include modern database capabilities, CI/CD and DevOps, backend API development, REST, and more.

-  [Data replication on Azure SQL Databases](https://learn.microsoft.com/en-us/training/modules/azure-sql-replication/): learn about logical data replication solutions (Change data capture (CDC), SQL Data Sync, and Change tracking) for data tracking, loading, replicating, and streaming that you can use to synchronize data changes from your Azure SQL Database to other destinations.

-  [Deploy IoT solutions with Azure SQL Database](https://docs.microsoft.com/en-us/learn/modules/deploy-iot-solution-azure-sql-database/): learn how Azure SQL Database provides a price-performant backend for IoT applications. You'll also deploy a template that includes Azure SQL Database, Azure VMs, Azure Functions, and Power BI which simplifies deploying and configuring IoT solutions.

## Best Practices

-  [Azure SQL DB Samples and Best Practices](https://github.com/yorek/azure-sql-db-samples): samples and Best practices to use Azure SQL DB to build modern, mission critical applications, with ease and confidence

-  [Azure SQL Tips](https://aka.ms/sqldbtips): get tips to improve database design, health, and performance right from the Azure SQL product group

- :tv: [Data Loading Best Practices on Azure SQL DB](https://www.youtube.com/watch?v=WP-bqtVdJg4): 20 minutes video dedicate on the explanation on the best practices to load data into Azure SQL as fast as possible

-  [To-Do List sample deployment with AZ Developer Tool (AZD)](https://github.com/azure-samples/todo-csharp-sql): a complete sample To Do application that demonstrates how to build an Azure solution using C#, Azure SQL for storage, and Azure Monitor for monitoring and logging, that uses AZD for completely automated deployment

## Shows

- :tv: [Data Exposed Live](https://aka.ms/learntv): Data Exposed Live, Wednesdays 9AM PT

## Community

-  [Azure Data Community](https://www.microsoft.com/en-us/sql-server/community): list of user groups and community resources like events, recordings, blogs and so on.

## Code Samples

### Generic

-  [Azure SQL Database Hyperscale Named Replicas OLTP Scale-Out Samples](https://github.com/azure-samples/azure-sql-db-named-replica-oltp-scaleout): sample of a massively scalable OLTP backed taking advantage of database secondary replicas to offload read-only workload

-  [Azure SQL DB Samples and Best Practices](https://github.com/yorek/azure-sql-db-samples): samples and Best practices to use Azure SQL DB to build modern, mission critical applications, with ease and confidence

-  [Azure SQL Hyperscale Autoscaler](https://github.com/azure-samples/azure-sql-db-hyperscale-autoscaler): how to create a serverless solution to automatically scale Azure SQL Hyperscale, based on detected workload

### Big Data

-  [Fast Data Loading in Azure SQL DB using Azure Databricks](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-databricks/azure-sql-db-databricks/): samples and best practices on how use Azure SQL with Azure Databricks

### Change Stream

-  [Azure SQL Change Stream with Debezium](https://github.com/Azure-Samples/azure-sql-db-change-stream-debezium): set up a change stream from Azure SQL using the open source tool [Debezium](https://debezium.io/)

### Data Loading

-  [Azure SQL DB Import Data Samples](https://github.com/Azure-Samples/azure-sql-db-import-data): samples on how to import data (JSON, CSV, Flat-Files, etc) into Azure SQL

-  [Fast Data Loading in Azure SQL DB using Azure Databricks](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-databricks/azure-sql-db-databricks/): samples and best practices on how use Azure SQL with Azure Databricks

### DevOps

-  [Azure SQL Database CI/CD Pipeline with GitHub Actions](https://github.com/Azure-Samples/azure-sql-db-ci-cd): a sample on how to deploy Azure SQL using the open source [DbUp](http://dbup.github.io/) and running test using [NUnit](https://nunit.org/)

### Dynamic Schema

-  [Dynamic Schema Management With Azure SQL](https://github.com/azure-samples/azure-sql-db-todo-backend-dotnet): samples on how efficiently to handle dynamic schemas in Azure SQL

### Full Stack

-  [Build serverless, full stack applications in Azure](https://github.com/Azure-Samples/serverless-full-stack-apps-azure-sql): full stack solution using Vue.js, Azure Static Web Apps, Azure Function, Azure SQL Database and a microservice architecture to monitor in real-time public transportation data, create a geofence and send notification when geofence is activated

- :tv: [Jamstack/Fullstack solution from zero to hero](https://github.com/Azure-Samples/azure-sql-db-fullstack-serverless-kickstart): Fullstack/Jamstack solution with Vue.js, Azure Functions, Azure Static Web apps and Azure SQL

-  [REST & GraphQL TodoMVC Sample App Full Stack Implementation with Directus](https://github.com/azure-samples/azure-sql-db-rest-graphql-directus): full Stack TodoMVC Sample app, with REST and GraphQL support, using Directus, Azure Web Apps, Vue.Js and Azure SQL

-  [REST & GraphQL TodoMVC Sample App Full Stack Implementation with Prisma](https://github.com/Azure-Samples/azure-sql-db-prisma): full-stack end-to-end implementation - both with REST and GraphQL support - with Azure SQL and Prisma.io of the well-known To-do list sample

-  [To-Do List sample deployment with AZ Developer Tool (AZD)](https://github.com/azure-samples/todo-csharp-sql): a complete sample To Do application that demonstrates how to build an Azure solution using C#, Azure SQL for storage, and Azure Monitor for monitoring and logging, that uses AZD for completely automated deployment

-  [TodoMVC Sample App Full Stack Implementation](https://github.com/azure-samples/azure-sql-db-todo-mvc): Full-Stack implementation of the famous ToDoMVC: Vue.js, .NET Core REST API, Azure SQL

### Geospatial

-  [Monitor GeoFences in real-time using Azure SQL and Stream Analytics](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-serverless-geospatial-stream-analytics/azure-sql-db-serverless-geospatial-stream-analytics/): end-to-end solution to processing incoming public transportation data using Azure SQL, Azure Functions, Events Hubs and Stream Analytics

-  [Real-Time Serverless GeoSpatial Public Transportation GeoFencing Solution](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-serverless-geospatial/azure-sql-db-serverless-geospatial/): end-to-end solution to processing incoming public transportation data using Azure SQL and Azure Functions

### Graph

-  [Million Song Dataset in Azure SQL DB / SQL Server](https://docs.microsoft.com/en-us/samples/azure-samples/millionsongdataset-sql/millionsongdataset-sql/): using graph objects and columnstore in Azure SQL with the Million Song dataset

### GraphQL

-  [Azure SQL & GraphQL Samples](https://github.com/azure-samples/azure-sql-db-graphql): samples on how to create a GraphQL solution using Azure SQL using .NET, Python or Node

-  [REST & GraphQL TodoMVC Sample App Full Stack Implementation with Directus](https://github.com/azure-samples/azure-sql-db-rest-graphql-directus): full Stack TodoMVC Sample app, with REST and GraphQL support, using Directus, Azure Web Apps, Vue.Js and Azure SQL

-  [REST & GraphQL TodoMVC Sample App Full Stack Implementation with Prisma](https://github.com/Azure-Samples/azure-sql-db-prisma): full-stack end-to-end implementation - both with REST and GraphQL support - with Azure SQL and Prisma.io of the well-known To-do list sample

### Jamstack

- :tv: [Jamstack/Fullstack solution from zero to hero](https://github.com/Azure-Samples/azure-sql-db-fullstack-serverless-kickstart): Fullstack/Jamstack solution with Vue.js, Azure Functions, Azure Static Web apps and Azure SQL

### REST

-  [Azure SQL Database Hyperscale Named Replicas OLTP Scale-Out Samples](https://github.com/azure-samples/azure-sql-db-named-replica-oltp-scaleout): sample of a massively scalable OLTP backed taking advantage of database secondary replicas to offload read-only workload

-  [Build serverless, full stack applications in Azure](https://github.com/Azure-Samples/serverless-full-stack-apps-azure-sql): full stack solution using Vue.js, Azure Static Web Apps, Azure Function, Azure SQL Database and a microservice architecture to monitor in real-time public transportation data, create a geofence and send notification when geofence is activated

-  [Create REST API in Python with Django, using the Django REST Framework and Azure SQL](https://github.com/azure-samples/azure-sql-db-django/tree/main/): This sample uses the Django web framework and Django REST framework package to easily implement REST APIs. mssql-django backend used to establish database connectivity with Azure SQL DB and Django.

-  [Creating a REST API with .NET Core and Azure SQL](https://github.com/azure-samples/azure-sql-db-dotnet-rest-api): create a REST API using Azure SQL, Dapper and .NET

-  [Creating a REST API with Python and Azure SQL](https://github.com/Azure-Samples/azure-sql-db-python-rest-api/): create a REST API using Azure SQL, Python and Flask

-  [Creating API to securely access data using Azure SQL Row Level Security](https://github.com/Azure-Samples/azure-sql-db-secure-data-access-api): using the Row Level Security feature of Azure SQL to create secure REST API with Python, Flask and JWT

-  [Dynamic Schema Management With Azure SQL](https://github.com/azure-samples/azure-sql-db-todo-backend-dotnet): samples on how efficiently to handle dynamic schemas in Azure SQL

-  [REST & GraphQL TodoMVC Sample App Full Stack Implementation with Directus](https://github.com/azure-samples/azure-sql-db-rest-graphql-directus): full Stack TodoMVC Sample app, with REST and GraphQL support, using Directus, Azure Web Apps, Vue.Js and Azure SQL

-  [REST & GraphQL TodoMVC Sample App Full Stack Implementation with Prisma](https://github.com/Azure-Samples/azure-sql-db-prisma): full-stack end-to-end implementation - both with REST and GraphQL support - with Azure SQL and Prisma.io of the well-known To-do list sample

-  [Serverless REST API with Azure Functions, Node and Azure SQL](https://github.com/azure-samples/azure-sql-db-node-rest-api): create a serverless REST API using Azure Functions, Node and Azure SQL

-  [TodoMVC Backend Implementation with Azure Functions, Node and Azure SQLL](https://github.com/azure-samples/azure-sql-db-todo-backend-func-node): create a REST API using Azure SQL, Azure Functions and Node

-  [TodoMVC Backend Implementation with Azure WebApps, .Net Core and Azure SQL](https://github.com/azure-samples/azure-sql-db-todo-backend-dotnet): implementation of the Todo Backend API using ASP.NET Core, JSON, Dapper and Azure SQL

-  [TodoMVC Sample App Full Stack Implementation](https://github.com/azure-samples/azure-sql-db-todo-mvc): Full-Stack implementation of the famous ToDoMVC: Vue.js, .NET Core REST API, Azure SQL

-  [Using Change Tracking API to sync data between Apps and the Cloud](https://docs.microsoft.com/en-us/samples/azure-samples/azure-sql-db-sync-api-change-tracking/azure-sql-db-dotnet-rest-api/): create a Python REST API to return only changed data from last sync using the Change Tracking feature of Azure SQL

### ScriptDOM

-  [ScriptDOM Samples](https://github.com/arvindshmicrosoft/SQLScriptDomSamples): samples on how to use the ScriptDOM parser to parse T-SQL statements

### Streaming

-  [Streaming at Scale](https://docs.microsoft.com/en-us/samples/azure-samples/streaming-at-scale/streaming-at-scale/): end-to-end solution to implement a streaming at scale scenario

## Articles

-  [Bandwidth-friendly Query Profiling for Azure SQL Database](https://sqlperformance.com/2020/04/sql-performance/bandwidth-friendly-query-profiling-azure-sql-database): using Extended Events to profile query execution

-  [How to use batching to improve application performance](https://docs.microsoft.com/en-us/azure/azure-sql/performance-improve-use-batching): an explanation of batching techniques that can be used to improve performance by a lot

## Scripts

-  [Azure SQL Diagnostic Queries](https://glennsqlperformance.com/resources/): comprehensive diagnostic and health-check queries

-  [Azure SQL Tips](https://aka.ms/sqldbtips): get tips to improve database design, health, and performance right from the Azure SQL product group

-  [sp_whoisactive](https://github.com/amachanic/sp_whoisactive): comprehensive activity monitoring stored procedure

## Tools

-  [Azure SQL Monitoring](https://github.com/denzilribeiro/sqldbmonitoring): solution for near-realtime monitoring using Grafana and the Telegraf SQL plugin

-  [dbatools](https://dbatools.io/): dbatools is a free PowerShell module with over 500 SQL Server administration, best practice and migration commands included.

-  [Smart Bulk Copy](https://github.com/Azure-Samples/smartbulkcopy): high-Speed Bulk Copy tool to move data from one Azure SQL / SQL Server database to another

-  [sqlcmd-go](https://github.com/microsoft/go-sqlcmd): modern sqlcmd tool to manage and query SQL Server and Azure SQL from the command line.

-  [sqlpackage.exe](https://docs.microsoft.com/en-us/sql/tools/sqlpackage/sqlpackage): SqlPackage.exe is a command-line utility that automates common database development and deployment tasks

## Libraries

### .NET

-  [Dapper](https://github.com/StackExchange/Dapper): a high-performance micro object mapper for .Net

-  [EF Core](https://docs.microsoft.com/en-us/ef/core/): native .NET Core OR/M mapping tool.

-  [SqlKata](https://sqlkata.com/): a fluent SQL query builder for C#

### Node

-  [Knex.js](https://knexjs.org/): "Batteries included" SQL query builder

-  [node-mssql](https://www.npmjs.com/package/mssql): Microsoft SQL Server client for Node.js

-  [Prisma](https://www.prisma.io/): Next-generation ORM for Node.js and TypeScript

-  [Sequelize](https://sequelize.org/): A promise-based Node.js ORM

### Python

-  [SQLAlchemy](https://www.sqlalchemy.org/): Python SQL toolkit and Object Relational Mapper

## DevOps

- 📄 [Advanced automated deployment of Azure SQL Database with Azure DevOps](https://erikej.github.io/sqlserver/2021/01/11/azure-sql-advanced-deployment-part1.html): detailed tutorial on how to deploy Azure SQL with Azure DevOps 

- 📄 [Continuous Delivery for Azure SQL DB using Azure DevOps Multi-stage Pipelines](https://devblogs.microsoft.com/azure-sql/continuous-delivery-for-azure-sql-db-using-azure-devops-multi-stage-pipelines/): how to create a CD pipeline using Azure DevOps

- 📄 [DevOps for Azure SQL](https://devblogs.microsoft.com/azure-sql/devops-for-azure-sql/): what is DevOps and how it can be applied to Azure SQL

- :tv: [DevOps for Azure SQL (1 of 2): Getting Started](https://www.youtube.com/watch?v=j7OnxOz7YDY): what is Data DevOps and a discussion around the first option: migration based deployment

- :tv: [DevOps for Azure SQL (2 of 2): Using Azure Pipelines for Azure SQL Deployments](https://www.youtube.com/watch?v=G7H6HbzwAfs): discussion on state based deployment, and full demo on using Azure Pipelines to deploy the database

-  [sqlpackage.exe](https://docs.microsoft.com/en-us/sql/tools/sqlpackage/sqlpackage): SqlPackage.exe is a command-line utility that automates common database development and deployment tasks

- :blue_book: [Use GitHub Actions to connect to Azure SQL Database](https://docs.microsoft.com/en-us/azure/azure-sql/database/connect-github-actions-sql-db): official Azure SQL GitHub Actions documentation

## Administration

-  [dbatools](https://dbatools.io/): dbatools is a free PowerShell module with over 500 SQL Server administration, best practice and migration commands included.

## Migration

-  [dbatools](https://dbatools.io/): dbatools is a free PowerShell module with over 500 SQL Server administration, best practice and migration commands included.

## Security

- :closed_lock_with_key: [Security Workshop](https://github.com/David-Seis/SecureYourAzureData): Workshop: SQL Server Security Ground to Cloud

## Videos

- :tv: [A Full Stack Application with Azure SQL & Prisma for Beginners](https://www.youtube.com/playlist?app=desktop&list=PLlrxD0HtieHiQEYJ-8SyKDAFJDVCII1fB): A series of 37 videos to learn how to build a full-stack application with Typescript, Node, Prisma and Azure SQL

- :tv: [Azure SQL Bootcamp](https://aka.ms/azuresqlbootcamp): interactive Azure SQL learning with Anna Hoffman and Bob Ward. Get your Azure SQL questions answered, learn to solve real-world scenarios, and more.

- :tv: [Azure SQL for Beginners](https://aka.ms/azuresql4beginners): 61 small videos to learn everything to get started

- :tv: [Azure SQL Performance Troubleshooting](https://www.youtube.com/playlist?list=PLlrxD0HtieHgDkZ84FfCSDLBcJmUn8ktU): 7 videos dedicated to performance troubleshooting

- :tv: [Create secure API with .NET, Dapper and Azure SQL](https://www.youtube.com/watch?v=TdvFYyLMHB0): Live coding recording of development of a backend API with security, full CI/CD - test included and unexpected requirements, just like the real world.

- :tv: [Data Exposed Show](https://aka.ms/azuresqlyt): an ongoing series to learn everything about the Azure Data platform, Azure SQL included

- :tv: [Data Loading Best Practices on Azure SQL DB](https://www.youtube.com/watch?v=WP-bqtVdJg4): 20 minutes video dedicate on the explanation on the best practices to load data into Azure SQL as fast as possible

- :tv: [Programming Databases with T-SQL for Beginners](https://www.youtube.com/playlist?list=PLlrxD0HtieHj551_lUtce08JUnTMY-y-R): 8 videos to learn T-SQL 

- :tv: [Serverless Full-Stack Kickstart](https://www.youtube.com/watch?v=TIh52zbi8Dk): recording of the session delivered at the Serverless conference, on how to create a full-stack application from scratch using Azure Static Web Apps, Azure Functions and Azure SQL

- :tv: [Taming Dynamic Schemas](https://www.youtube.com/watch?v=aaxymYhaIPE): three different design tecniques to manage dynamic schemas in Azure SQL ranging from a pure relational solution to a full document/JSON one.

### Azure Friday

- :tv: [Azure Friday: Azure SQL Database: A developer's best friend](https://www.youtube.com/watch?v=We5bSDHnzW8): an introduction to some features of Azure SQL Database what you want to start to use right now

- :tv: [Azure Friday: Azure SQL Database: An introduction to temporal tables](https://www.youtube.com/watch?v=FeB6aAQQfsQ): temporal tables helps to automatically track and query the changes that happends on your data in your database

- :tv: [Azure Friday: Azure SQL Database: Multi-model features](https://www.youtube.com/watch?v=n6p8nJQXXoI): Azure SQL Database is relational, modern, multi-model database, with supports for JSON, Graph and Geospatial models

- :tv: [Azure Friday: Calling external REST endpoints from Azure SQL Database](https://www.youtube.com/watch?v=R6l-2XJyu2c): Call a REST endpoint directly from Azure SQL, and integrate with everything.

- :tv: [Azure Friday: Connect your Static Web Apps to Azure Databases using REST or GraphQL](https://www.youtube.com/watch?v=gCrBSSOezSQ): Build a Jamstack solution with Azure Static Web Apps and Data API Builder

### Microsoft Build 2023

- :tv: [GraphQL: New services and tools for building API-driven apps](https://www.youtube.com/watch?v=GsXGbUWEQzo&list=PLlrxD0HtieHjolPmqWVyk446uLMPWo4oP&index=70): How to use GraphQL natively with Azure SQL, Azure Static Web Apps and Azure API Management

- :tv: [Increase developer velocity with Azure SQL Database from data to API](https://www.youtube.com/watch?v=pH5MwGzRN7Y&list=PLlrxD0HtieHjolPmqWVyk446uLMPWo4oP&index=161): All the latest features available in Azure SQL to increase developer velocity. From the new SQLCMD to GraphQL and REST API.

## Conferences

-  [SQLBits](https://sqlbits.com/): One of the most popular conference on Azure SQL and SQL Server. More than 1000 recordings available for free.

## Books

-  [Azure SQL Revealed](https://www.apress.com/it/book/9781484259306): a guide to the cloud for SQL Server Professionals

-  [Practical Azure SQL Database for Modern Developers](https://www.apress.com/it/book/9781484263693): building applications in the Microsoft cloud with Azure SQL

## Blogs

### Official

-  [Azure SQL @ TechCommunity](https://techcommunity.microsoft.com/t5/azure-sql/bg-p/AzureSQLBlog): Azure SQL team blog with focus on IT Pros

-  [Azure SQL Devs’ Corner](https://devblogs.microsoft.com/azure-sql/): Azure SQL team blog with focus on developers

## Social Media

-  [Twitter](https://twitter.com/AzureSQL): official Twitter account for Azure SQL

-  [YouTube](https://www.youtube.com/channel/UCNsev6sULZ_Zp06VL7uktuA): official YouTube channel for Azure SQL

