# Understand the evolving world of data

## Types of data

- Structured: Defined structure, for example stored in Azure SQL Database and Azure SQL Data Warehouse.
- Unstructured: Each data element can have its own schema at query time, for example stored as a file in Azure Blob storage or as NoSQL data in Azure Cosmos DB or Azure HDInsight.
- Aggregated

Data systems must be accurate, highly secure, and constantly available and must comply with applicable regulations (GDPR) and standards such as PCI DSS (Payment Card Industry Data Security Standard).

## On-premises vs cloud-based servers

|   | On-premises environments | Computing environment |
| --|------------- | ------------- |
| Computing environment  | - Physical servers, network infrastructure, and storage. <br> - A server needs at least one OS. | Provide the physical and logical infrastructure to host services, virtual servers, intelligent applications, and containers for their subscribers. No capital investment requiered-|
| Licensing | - Own licensing cost per OS.  | |
| Maintenance | - Hardware <br> - Firmware <br> - Drivers <br> - BIOS <br> - Operating system <br> - Software <br> - Antivirus software | Microsoft manages key infrastructure services such as physical hardware, computer networking, firewalls and network security, datacenter fault tolerance, compliance, and physical security of the buildings. |
| Scalability | To scale server horizontally add another server node to a cluster uses either a hardware load balancer or a software load balancer. Replace it when it reaches maximun capacity. | Easy to achieve and measured in compute units.|
| Availability | The more uptime the Service-level agreements (SLA) requires, the higher the cost. | Azure duplicates customer content for redundancy and high availability. |
| Total cost of ownership | - Hardware <br> - Software licensing <br> - Labor (installation, upgrades, maintenance) <br> - Datacenter overhead (power, telecommunications, building, heating and cooling) | Costs by subscriptions. | 

Lift and shift - Migrate from physical or virtualized on-premises servers to Azure Virtual Machines. 
Benefits: higher availability, lower operational costs, and the ability to transfer workloads from one datacenter to another. 
Disadvantage: the application can't take advantage of the many features available within Azure.

## Data Process

Extract, transform, and load (ETL).

The transformation step may take a long time. It is the process used for ingesting data from an on-premises database to an on-premises data warehouse.

An alternative approach is extract, load, and transform (ELT). The data is extracted and loaded into a large data repository, such as Azure Cosmos DB or Azure Data Lake Storage. This process is used for ingesting data from an on-premises database into the cloud.

## Evaluation notes 

Duplicating customer content for redundancy and meeting service-level agreements (SLAs) in Azure meets which cloud technical requirement? High availability, it  duplicates customer content for redundancy and meets SLAs in Azure.



