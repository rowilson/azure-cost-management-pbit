# Azure Cost Management Connector for Power BI Template
This Power BI Template (PBIT) is an accelerator to help you quickly monitor and manage your organization's Azure cost. It is designed to import your organization's subscription metadata to augment the cost management tables. You will be able to drill into your Azure costs and analyze them based on your tags.

This templates uses the Azure Cost Management Connector for Power BI Desktop (See Limits below e.g. 1GB PBI Desktop)
https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-connect-azure-cost-management

To connect, you must use an Enterprise Administrator account for Enterprise Agreements, or have appropriate permissions at the billing account or billing profile levels for Microsoft Customer Agreements.

# Latest Version
v02.11.23

# Recommended Azure Cost Management References 

(1) Azure Cost Management API - Data Available through the Connector
https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-connect-azure-cost-management#data-available-through-the-connector

Cost Management Tables
- Budgets (budgets)
- Pricing Sheet with Enterprise Discount (pricesheets)
- Usage (usagedetails)
- Amoritized Usage (usagedetailsamortized)
- Reservation Charges (richarges) (Depreciating)
- Reservation Transactions (ritransactions) (Replacing Resevation Charges)
- RI Recommendations - Single (rirecommendationssingle)
- RI Recommendations - Shared (rirecommendationsshared)
- RI Usage Detail (riusagedetails)
- RI Usage Summary (riusagesummary)
- Balance Summary - Current Period (balancesummary)

(2) Azure Cost Management + Billing Documentations (Best Practices)
https://learn.microsoft.com/en-us/azure/cost-management-billing/

- Product Documentation
- Manage and Optimize Costs
- Cost Management Best Practices
- How-To and Trainng

(3) Azure Cost Management (Learn)
https://learn.microsoft.com/en-us/power-query/connectors/azurecostmanagement

(4) Considerations and Limitations (e.g. 1GB PBIX)
https://learn.microsoft.com/en-us/power-query/connectors/azurecostmanagement#considerations-and-limitations

(5) Cost Management App (Microsoft AppSource) 
https://appsource.microsoft.com/en-US/product/power-bi/costmanagement.azurecostmanagementapp

# Disclaimer
THE SCRIPTS ARE PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.

# Questions or Help 
Please contact Rob Wilson rowilson@microsoft.com

# Contributing
This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the Microsoft Open Source Code of Conduct. For more information see the Code of Conduct FAQ or contact opencode@microsoft.com with any additional questions or comments.
