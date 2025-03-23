# Slash It!

Power BI Contract Assurance Dashboard: Enhancing Revenue & Cost Optimization and Savings Analysis

## Project Overview

This Power BI Interactive Dashboard has been designed to provide a comprehensive view of contract assurance by consolidating contract-wise savings, internal & external savings breakdown, and materialized vs. unrealized savings. The dashboard serves as a powerful analytical tool for stakeholders to monitor financial efficiencies and identify savings opportunities.

## Business Scenario: Cost Assurance & Savings Visibility

Organizations often face challenges in tracking cost transformation initiatives, ensuring contract compliance, and identifying potential cost savings. This dashboard provides a data-driven approach by:

- Consolidating savings data from multiple sources.
- Categorizing savings as "Internal" or "External".
- Segregating savings into "Materialized" and "Unrealized" categories.
- Providing contract-wise breakdowns to enable better negotiation and cost forecasting.

## Dashboard Design & Features

The Power BI dashboard has been structured to ensure clear data visualization and interactive filtering for better decision-making.

#### 1. Card Visuals (Key Metrics)

The following key cost assurance metrics are displayed via card visuals:

- Total Savings: Aggregated sum of all cost savings.
- Internal & External Savings: Segregation of savings within and outside the organization.
- Materialized & Unrealized Savings: Distinguishing actualized vs. potential savings.
- Contracts Covered: Total number of contracts contributing to savings.

![Image](https://github.com/user-attachments/assets/1fea9f17-67c7-4292-ac6e-1837411922dd)

#### 2. Slicers for Data Filtering

- Resource Filter: Enables users to view savings data based on individual teams or personnel.

![Image](https://github.com/user-attachments/assets/ba1317d5-27c3-4c03-94d6-2162b4faac2f)

- Savings Status Filter: Allows filtering between "Internal" & "External" and "Materialized" & "Unrealized" savings.

![Image](https://github.com/user-attachments/assets/1661c0aa-64c9-4200-86b2-a007de322a52)


- Product Filter: Enable users to understand high impact critical products, helping them in benchmarking different products based on their cost savings and supporting procurement and finance teams in renegotiating contracts with vendors supplying high-cost or low-saving products.

![Image](https://github.com/user-attachments/assets/07d00048-2c18-4c0d-ad63-709d8b6c8786)

#### 3. Drill-Down & Hierarchy Functionality

- Total Savings → Materialized & Unrealized Savings: Allows users to drill down into status of savings identified.
- Contract-wise Drill-Through: Enables users to click on a contract and view its associated savings data in detail.

![Image](https://github.com/user-attachments/assets/60fb9c70-e09e-4916-b708-2582fcf381b4)

- Tooltips: Addition of tooltips on visuals give deeper insights on financial figures with just hovering the mouse on visual, making it effortless to dive in details.

#### 4. Interactive Capabilities

- Clicking on "Unrealized Savings" in a Card Visual: Filters the contract table visual to show only the contracts that contribute to unrealized savings.

![Image](https://github.com/user-attachments/assets/df550eed-804d-47f3-a677-243067065787)

- Clicking on Contract Names in a Table: Filters all visuals to display the relevant cost/revenue - saving details for that contract.

![Image](https://github.com/user-attachments/assets/a8f3e89c-3d9d-43e4-a507-9be72f13f229)

- Hierarchical Drill-Downs: Users can explore savings breakdowns at multiple levels.

![Image](https://github.com/user-attachments/assets/ec7a2e6e-c833-4ed0-b7a9-ae70ead7466d)

## Data Sources & Transformation

- Raw Data Import: Revenue data is sourced from billing inventory, and cost data from various contract wise cost sources.
- Data Transformation: Power Query is used to clean and structure the data, ensuring proper currency formatting, hierarchical classification, and missing value handling.
- DAX Measures:

Created DAX measures with specific conditions for dynamic iteractions with board visuals.

![Image](https://github.com/user-attachments/assets/dd6f34a2-5e2d-4525-8525-a1a2f9af796b)

Adding "+0" to ensure 0 gets populated in absence of value.

## Value Additions to the Business

- Enhanced Visibility & Cost and revenue Tracking: Enables finance teams to monitor savings trends in real time.
- Improved Decision-Making: Helps in identifying high-impact contract-saving initiatives.
- Contractual Compliance & Assurance: Ensures that savings commitments are being met as per contract terms.
- User-Friendly Interface: Enables non-technical stakeholders to easily interpret and interact with financial data.
- Individual Contributions: The dashboard highlights each team member's impact on cost transformation through dedicated visual representations of resource-wise savings, ensuring transparency and recognition of efforts.

![Image](https://github.com/user-attachments/assets/6cd96aec-ee77-4019-9bb8-c4734b397df5)

## Conclusion

The Power BI Contract Assurance Dashboard is an effective analytical tool that simplifies savings tracking, improves transparency, and empowers teams to make data-driven decisions. The interactive features allow for real-time insights, ensuring that organizations can optimize their financial performance and maximize cost & revenue optimization opportunities.
