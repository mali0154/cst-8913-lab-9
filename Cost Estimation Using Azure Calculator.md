# Cost Estimate for 2-Tier Application Deployment

This document provides a cost estimate for deploying a simple 2-tier application on Microsoft Azure, calculated using the Azure Pricing Calculator. The estimate was generated on **March 11, 2025, at 12:17:01 AM UTC**, with all prices in **United States Dollar (USD)**. The selected region for all resources is **Canada Central**.

## Application Configuration
- **Frontend**:
  - **Service Type**: Virtual Machines
  - **Custom Name**: FrontEnd VM Cost
  - **Description**: 1 B2s (2 vCPUs, 4 GB RAM) x 730 Hours (Pay as you go), Windows (License included), OS Only; 1 managed disk – S6; 5 GB outbound data transfer from Canada Central to East Asia
- **Backend**:
  - **Service Type**: Virtual Machines
  - **Custom Name**: BackEnd Cost
  - **Description**: 1 D4 v3 (4 vCPUs, 16 GB RAM) x 730 Hours (Pay as you go), Windows (License included), OS Only; 1 managed disk – S4; 200 GB outbound data transfer from Canada Central to East Asia
  - **Service Type**: Azure SQL Database
  - **Description**: Single Database, vCore, General Purpose, Provisioned, Standard-series (Gen 5), Primary or Geo replica Disaster Recovery, Locally Redundant, 1 - 2 vCore Database(s) x 730 Hours, 32 GB Storage, SQL License (Pay as you go), RA-GRS Backup Storage Redundancy, 0 GB Point-In-Time Restore, 0 x 5 GB Long Term Retention

## Cost Breakdown
| Service Category | Service Type          | Custom Name       | Region         | Estimated Monthly Cost (USD) |
|------------------|-----------------------|-------------------|----------------|------------------------------|
| Compute          | Virtual Machines      | FrontEnd VM Cost  | Canada Central | 43.021                       |
| Compute          | Virtual Machines      | BackEnd Cost      | Canada Central | 307.82                       |
| Databases        | Azure SQL Database    |                   | Canada Central | 417.89636                    |
| Support          |                       | Support           |                | 0                            |
| **Total**        |                       |                   |                | **768.73736**                |

## Additional Details
- **Licensing Program**: Microsoft Customer Agreement (MCA)
- **Billing Account/Profile**: Not specified
- **Estimated Upfront Cost**: $0.00
- **Total Estimated Monthly Cost**: $768.74 (rounded)

## Notes
- The frontend VM (B2s) includes a smaller managed disk (S6) and 5 GB of outbound data transfer to East Asia.
- The backend VM (D4 v3) includes a larger managed disk (S4) and 200 GB of outbound data transfer to East Asia.
- The Azure SQL Database is configured with 32 GB of storage and RA-GRS backup redundancy, though no additional Point-In-Time Restore or Long-Term Retention storage is included.

## Disclaimer
All prices are in USD and represent a summary estimate, not a quote. For the most current pricing, refer to [Azure Pricing Calculator](https://azure.microsoft.com/pricing/calculator/). This estimate reflects pricing as of March 11, 2025.

## Summary
The total estimated monthly cost for deploying this 2-tier application in Canada Central is **$768.74**. The estimate aligns with the lab requirements, though it exceeds the initial $50 budget example due to the inclusion of a more robust backend VM (D4 v3) and a higher-tier SQL Database configuration.
