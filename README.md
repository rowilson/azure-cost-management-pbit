# Power BI Template for Azure Cost Management
This Power BI Template (PBIT) is an accelerator to help organizations quickly monitor, visualize, analyze and govern Azure usage, costs, trends, and anomalies. It is designed to augment the Azure Cost Management APIs with organizational metadata to help establish deeper Azure cost management governance. The template enables extensive drill-down into all Azure costs and analyzes those costs against organizational defined Tags such as Application, Cost Center, Division, Business Unit, Owner etc.

This templates uses the <strong>Azure Cost Management Connector for Power BI Desktop</strong><br>
https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-connect-azure-cost-management

To connect, you must use an Enterprise Administrator account for Enterprise Agreements, or have appropriate permissions at the billing account or billing profile levels for Microsoft Customer Agreements.

# Template Version History
v3.19.23 (Current)<br>
v3.14.23<br>
v3.10.23<br>
v2.17.23b<br>

# Metadata File Version History
v3.19.23 (Current)<br>
v3.10.23<br>

# Installation
https://github.com/rowilson/azure-cost-management-pbit/blob/main/Documentation/Power%20BI%20Template%20for%20Azure%20Cost%20Management%20-%20Instructions%20v12.15.22.pdf

# Recommended Azure Cost Management References 

<strong>(1) Azure Cost Management API - Data Available through the Connector</strong><br>
https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-connect-azure-cost-management#data-available-through-the-connector

Cost Management Tables
- Budgets (budgets)
- Pricing Sheet with Enterprise Discount (pricesheets)
- Usage (usagedetails)
- Amoritized Usage (usagedetailsamortized)
- Reservation Charges (richarges) (Depreciating) (NOTE: Not included in Template)
- Reservation Transactions (ritransactions) (Replacing Resevation Charges)
- RI Recommendations - Single (rirecommendationssingle)
- RI Recommendations - Shared (rirecommendationsshared)
- RI Usage Detail (riusagedetails)
- RI Usage Summary (riusagesummary)
- Balance Summary - Current Period (balancesummary)

<strong>(2) Azure Cost Management + Billing Documentations (Best Practices)</strong><br>
https://learn.microsoft.com/en-us/azure/cost-management-billing/

- Product Documentation
- Manage and Optimize Costs
- Cost Management Best Practices
- How-To and Trainng

<strong>(3) Azure Cost Management (Learn)</strong><br>
https://learn.microsoft.com/en-us/power-query/connectors/azurecostmanagement

<strong>(4) Azure Cost Management Discipline, Best Practices, Governance Templates/</strong><br>
https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/govern/cost-management/

- Cost Management Discipline Template
- Cost Management Tools in Azure - Native Tools for Policy and Process Automation
- Cost Management sample Azure Policy statements
- Cost Management Best Practices
- Cost Management Discipline Improvement

<strong>(5) Considerations and Limitations (e.g. 1GB PBIX)</strong><br>
https://learn.microsoft.com/en-us/power-query/connectors/azurecostmanagement#considerations-and-limitations

<strong>(6) Microsoft Management Videos - Best Practices (YouTube)</strong><br>
https://www.youtube.com/c/AzureCostManagement

# Other Azure Power BI Templates 
<strong>(1) Microsoft Cost Management App (Microsoft AppSource)</strong><br>
https://appsource.microsoft.com/en-US/product/power-bi/costmanagement.azurecostmanagementapp

<strong>(2) Chris Bowman Github Template </strong><br>
https://github.com/chris-bowman/Azure-Cost-Reporting

# Azure Architecture Icons 
The Power BI Azure Cost Management Template uses Azure Architecture Icons (SVG)<br><br>
Azure Icons - https://learn.microsoft.com/en-us/azure/architecture/icons/<br>
Power Platform Icons - https://learn.microsoft.com/en-us/power-platform/guidance/icons<br>
M365 Icons - https://learn.microsoft.com/en-us/microsoft-365/solutions/architecture-icons-templates?view=o365-worldwide<br>
D365 Icons - https://learn.microsoft.com/en-us/dynamics365/get-started/icons<br>
<br><br>
<img src="https://github.com/rowilson/azure-cost-management-pbit/blob/main/Images/Dashboard%20-%20Architecture%20Icons.png" alt="Azure Architecture Icons">
<br><br>
Please review icons terms of use prior to use. Architecture Icons are not included in this Github repository.<br>
<br>
Microsoft permits the use of these icons in architectural diagrams, training materials, or documentation. You may copy, distribute, and display the icons only for the permitted use unless granted explicit permission by Microsoft.

# RSS Feeds (Azure Announcements) 
Azure News and Cost Management Announcements are pulled directly from the following RSS Feeds
<br><br>
(1) Azure Updates - https://azurecomcdn.azureedge.net/en-us/updates/feed/
<br>
(2) Azure Announcements - https://azurecomcdn.azureedge.net/en-us/blog/topics/announcements/feed/
<br>
(3) Azure Cost Management News - https://azurecomcdn.azureedge.net/en-us/blog/tag/cost-management/feed/
<br>
(4) Power BI - https://powerbi.microsoft.com/en-us/blog/feed/
<br><br>
The Power Automate Flows and SQL Schema are not included in the current template version. It will be availabe in a future release.
<br><br>
<img src="https://github.com/rowilson/azure-cost-management-pbit/blob/main/Images/Dashboard%20-%20Announcements.png" alt="Azure Announcements">
<br>
# Disclaimer
THE SCRIPTS ARE PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.

# Questions or Help 
Please contact Rob Wilson rowilson@microsoft.com | Follow Me on Twitter @robswilson

# Contributing
This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the Microsoft Open Source Code of Conduct. For more information see the Code of Conduct FAQ or contact opencode@microsoft.com with any additional questions or comments.
