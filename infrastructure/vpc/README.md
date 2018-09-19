# VPC
High availability VPC for there staging and production environments.

**CIDR in AvailabilityZone**

VPC | Subnet | us-east-1a | us-east-1b | us-east-1c 
--- | :---: | --- | --- |---
**ProdVPC** `10.50.0.0/16` | **ProdPublic1/2/3** | 10.50.1.0/24 | 10.50.2.0/24 | 10.50.3.0/24
\_ | **ProdPrivate1/2/3** | 10.50.10.0/24 | 10.50.20.0/24 | 10.50.30.0/24
**StagingVPC** `10.5.0.0/16` | **StagingPublic1/2/3** | 10.5.1.0/24 | 10.5.2.0/24 | 10.5.3.0/24
\_ | **StagingPrivate1/2/3** | 10.5.10.0/24 | 10.5.20.0/24 | 10.5.30.0/24
