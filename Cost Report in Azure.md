# Cost Reports Summary

This document summarizes a cost report generated from Azure Cost Management + Billing, reflecting costs by resource type (ServiceName) for usage dates **January 1, 2025, and February 1, 2025**. Costs are presented in both USD and CAD, as exported from the Azure Cost Analysis tool on March 10, 2025.

## Report Details
- **Time Range**: January 1, 2025 – February 1, 2025
- **View**: Cost by resource type
- **Exported File**: `Cost_Report.csv`
- **Currency**: Costs are provided in USD (CostUSD) and CAD (Cost), with CAD as the billing currency.

## Cost Breakdown by Date

### January 1, 2025
| Service Name            | Cost (USD)       | Cost (CAD)       |
|-------------------------|------------------|------------------|
| (Unspecified)           | -0.0433245685    | -0.0894253695    |
| Azure Data Factory v2   | 0.03789          | 0.0546013845     |
| Bandwidth               | 0.0000251629     | 0.0000362610     |
| Log Analytics           | 0.0              | 0.0              |
| Network Watcher         | 0.0              | 0.0              |
| SQL Database            | 0.4176317613     | 0.6018282497     |
| Storage                 | 2.0209276280     | 2.9122577583     |
| Virtual Machines        | 0.0              | 0.0              |
| Virtual Network         | 0.4168500163     | 0.6007017160     |
| **Total**               | **2.850000**     | **4.079999**     |

*Note*: Totals are rounded to 6 decimal places for clarity.

### February 1, 2025
| Service Name            | Cost (USD)       | Cost (CAD)       |
|-------------------------|------------------|------------------|
| (Unspecified)           | -0.0255687388    | -0.0457322079    |
| Azure App Service       | 0.0              | 0.0              |
| Azure Cosmos DB         | 0.0              | 0.0              |
| Bandwidth               | 0.0000003076     | 0.0000004442     |
| Functions               | 0.0              | 0.0              |
| Log Analytics           | 0.0              | 0.0              |
| Storage                 | 0.5443508230     | 0.7862331112     |
| Virtual Machines        | 0.0518134416     | 0.0748367444     |
| Virtual Network         | 0.3494041667     | 0.5046619081     |
| **Total**               | **0.920000**     | **1.320000**     |

*Note*: Totals are rounded to 6 decimal places for clarity.

## Summary
- **January 1, 2025**:
  - Total Cost: $2.85 USD / 4.08 CAD
  - Highest Contributor: Storage ($2.02 USD / 2.91 CAD), followed by SQL Database ($0.42 USD / 0.60 CAD) and Virtual Network ($0.42 USD / 0.60 CAD).
  - Negative cost (-$0.04 USD / -0.09 CAD) under an unspecified service suggests a credit or adjustment.
- **February 1, 2025**:
  - Total Cost: $0.92 USD / 1.32 CAD
  - Highest Contributor: Storage ($0.54 USD / 0.79 CAD), followed by Virtual Network ($0.35 USD / 0.50 CAD).
  - Minimal usage of Virtual Machines ($0.05 USD / 0.07 CAD) and negligible Bandwidth costs.

## Observations
- Storage consistently dominates costs across both dates.
- SQL Database usage is significant in January but absent in February, possibly indicating a change in resource utilization.
- Negative costs (unspecified) may reflect discounts, refunds, or data inconsistencies in the report.

This summary fulfills the lab requirement to convert key cost report information into Markdown format for the Azure-Cost-Management-Lab repository.
