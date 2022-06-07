# Introduction to Azure Synapse Analytics

Azure Synapse Analytics is an integrated analytics platform, which combines data warehousing, big data analytics, data integration, and visualization into a single environment.

## Analytical Supported Types

- Descriptive analytics - “What is happening in my business?” The data to answer this question is typically answered through the creation of a data warehouse.
- Diagnostic analytics - “Why is it happening?” Explore data within a data lake.
- Predictive analytics -  “What is likely to happen in the future based on previous trends and patterns?” by using its integrated Apache Spark engine.
- Prescriptive analytics - "What should I do?" Leads to Decision Support and Decision Automation. By executing actions based on real-time or near real-time analysis of data, using predictive analytics.

Azure Synapse Analytics provides:

- Analytics capabilities offered through Azure Synapse SQL through either dedicated SQL pools or serverless SQL pools: Azure Synapse SQL is a distributed query system that enables to implement data warehousing and data virtualization scenarios using standard T-SQL. Works with descriptive and diagnostic analytical scenarios.  For predictable performance and cost, create dedicated SQL pools to reserve processing power for data stored in SQL tables. For unplanned or ad-hoc workloads, use the always-available, serverless SQL endpoint.
- Apache Spark pool with full support for Scala, Python, SparkSQL, and C#
- Data integration with Azure Synapse Pipelines
- Perform operational analytics with near real-time hybrid transactional and analytical processing with Azure Synapse Link:
- A single Web UI to be able to access all Azure Synapse (Studio) Analytics capabilities: Explore data estate, Develop TSQL scripts and notebooks to interact with the analytical engines, Build data integration pipelines for managing data movement, monitor the workloads within the service and manage the components of the service.
- Integrate with a variety of Azure Data Platform technologies:


## When to use Azure Synapse Analytics

- Modern data warehousing
- Advanced analytics
- Data exploration and discovery
- Real time analytics
- Data integration
- Integrated analytics

## Evaluation

- Predictive analytics “What is likely to happen in the future based on previous trends and patterns?”.
- You have a requirement to occasionally prepare data for ad hoc data exploration and analysis. Which resource model in Azure Synapse Analytics is the most effective to use to meet this requirement? The serverless resource model is the ideal resource model in this scenario as it makes use of the resources when required.
- Pipelines are a component of Azure Synapse Analytics that enables you to ingest, prepare, and serve data to other Azure Synapse Components or Azure services.
- Where can you develop TSQL scripts and notebooks in Azure Synapse Analytics? Azure Synapse Studio.
- The Data Lake is primary storage location for source files that can be used within the various analytical engines.

## Activity: Log into the Azure portal and explain and create resource groups.
