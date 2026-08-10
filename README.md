![Uploading Screenshot 2026-08-10 091359.png…]()

# Stakeholder-Insights-and-Performance-Dashboard
An Interactive Tableau Dashboard for Insurance, Stakeholder &amp; Business Performance Analysis

-The Stakeholder Insights and Performance Dashboard is an interactive Tableau dashboard designed to provide a consolidated view of insurance business performance, stakeholder contributions, premium trends, profitability, and asset distribution.

-The dashboard enables users to evaluate insurer value creation, premium performance over time, profitability across cities and policy tenures, stakeholder asset distribution, shareholding patterns, and cost-to-profitability relationships through interactive visualizations and dynamic filters.

# Purpose
The primary objective of the dashboard is to transform complex stakeholder and insurance data into a single executive-level analytical view.
It allows decision-makers to quickly answer questions such as:

- Which stakeholder category contributes the most value?
- How have premiums changed over the years?
- Which cities and policy tenures generate the highest profitability?
- How are assets under management distributed across stakeholders?
- What is the current shareholding composition?
- How do operating and commission costs relate to profitability?
- Which insurer has created the highest value?

# Tech Stack
The dashboard was developed using:

- Python – Used for exploratory data analysis, data validation, and preprocessing where required.

- SQL – Used for data cleaning, transformation, filtering, aggregation, and preparing the dataset for analysis.

- Tableau – Used to build the interactive dashboard, create visualizations, calculated fields, KPIs, filters, and dashboard interactions.

- Tableau Calculated Fields / LOD Expressions – Used to derive business metrics and analytical measures.

- CSV / Excel – Used as the source/storage format for the prepared dataset.

# Data Source

The dashboard uses an insurance and stakeholder dataset containing information related to premiums, insurers, stakeholders, assets under management, profitability, policy tenure, geography, demographics, and shareholding categories.

The dataset supports analysis across multiple dimensions including:

- Stakeholder category

- Insurer

- City

- Policy tenure

- Gender

- Date

- Assets under Management

- Premium

- Profitability

- Shareholding category

- Value Created

# Business Problem

Insurance organizations and financial institutions generate data across multiple business dimensions, but analyzing these metrics separately can make it difficult for decision-makers to obtain a holistic view of business performance.

Important questions such as:

1. Which stakeholder category creates the most value?

2. Are premium collections increasing over time?

3. Which cities and policy tenures are the most profitable?

4. Where are assets under management concentrated?

5. How are operating and commission costs affecting profitability?

may require users to examine multiple reports or datasets.

The dashboard addresses this problem by consolidating these metrics into an interactive executive performance dashboard.

# Goal of the Dashboard

The dashboard aims to:

- Provide a high-level overview of insurance performance.
- Compare value creation across stakeholder categories.
- Monitor premium trends over time.
- Analyze profitability by geography and policy tenure.
- Understand stakeholder asset distribution.
- Visualize shareholding composition.
- Examine cost ratios in relation to profitability.
- Allow users to dynamically segment the data using multiple filters.

# Dashboard Walkthrough

1. Executive KPIs

The top section provides four high-level KPIs:

Total Premium - 245.9B

Represents the total premium collected across the available dataset.

Average Age of Stakeholders - 34.45

Provides a demographic overview of the stakeholder population.

Equity Value Created - 230.82B

Measures the total value created for records where Assets Under Management is categorized as Equity.

Highest Value Created by Insurer - 49.17M

Highlights the maximum value created by an individual insurer.

These KPIs provide users with an immediate snapshot of overall business performance.

2. Value Created by Insurer

A horizontal bar chart compares Value Created across stakeholder/insurer-related categories.

The visualization highlights significant differences between categories, with Bancassurance partners contributing the largest value in the displayed view.

This allows users to quickly identify the strongest contributors to overall value creation.

3. Premiums Over Time

The Premiums Over Time visualization presents annual premium activity from 2014 through 2024.

The stacked structure allows users to observe how premium contributions vary across the different components/categories over time.

This visualization can help identify:

- Growth patterns
- Changes in premium contribution
- High-performing years
- Potential shifts in business composition

4. Profitability by City and Policy Tenure

This visualization combines two important dimensions:

City × Policy Tenure

The dashboard displays profitability across cities such as:

Ahmedabad
Bangalore
Goa
Jamshedpur
Jhalna
Mangalore
Mumbai
Mysore
Pune

while simultaneously breaking profitability down into policy-tenure groups:

Less than 1 year
1–3 years
3–5 years
More than 5 years

This provides a more granular view of where and under which policy durations profitability is being generated.

5. Assets Under Management by Stakeholder

The AUM visualization compares assets across stakeholder categories such as:

People
Distributors
Customers
Investors
Community
Environment
Premium

The visualization makes it easy to identify categories with significantly higher asset values and understand the concentration of assets under management.

6. Shareholding Distribution

A donut chart presents the composition of the organization's shareholding structure.

The displayed distribution includes:

Category	Share
FII	38.4%
DII	30.2%
Promoters	28.2%
Retail	3.3%

This gives management an immediate understanding of the ownership structure and concentration among investor categories.

7. Cost Ratio vs Profitability

The dashboard compares different cost-related metrics against profitability measures, including:

Opex Ratio
Commission Ratio
Total Cost Ratio
Net Worth
Profit After Tax

The visualization helps users evaluate the relationship between operational/commission costs and overall financial performance.

This can be particularly useful for identifying areas where cost efficiency may influence profitability.

# Interactive Filters

The left-side filter panel allows users to dynamically segment the dashboard by:

- Stakeholder

Analyze performance for individual stakeholder categories.

- Assets Under Management

Focus on specific AUM classifications.

- City

Perform regional analysis.

- Gender

Analyze demographic differences.

- Date

Analyze performance within a specific time period.

- Profitability

Filter based on profitability values.

- Premium

Filter records based on premium values.

Because these filters affect the dashboard dynamically, users can move from a high-level business overview to a much more specific analysis.

# Interactivity

The dashboard is designed as an interactive analytical tool rather than a static report.

Users can:

- Apply multiple filters simultaneously.
- Select specific stakeholder categories.
- Drill into geographical performance.
- Compare different policy tenures.
- Explore premium trends across years.
- Hover over charts for detailed information.
- Dynamically update KPIs and visualizations based on selections.

This allows different users to investigate the same dataset according to their specific business questions.

# PDF Export

A Download PDF option is provided in the dashboard interface, allowing users to export the dashboard for offline reporting and sharing.

The exported report is intended to preserve the dashboard's key KPIs and visual analytical content for stakeholders who need to distribute or review the analysis outside Tableau.

# Business Impact

1. Executive Performance Monitoring

Provides management with a single view of important business metrics rather than requiring multiple reports.

2. Stakeholder Performance Analysis

Helps identify which stakeholder categories contribute most significantly to value creation and assets under management.

3. Regional Decision-Making

City-level profitability analysis can help identify stronger and weaker geographical markets.

4. Portfolio & Policy Analysis

Understanding profitability across policy-tenure groups can support decisions around policy portfolio composition.

5. Cost Optimization

The cost-ratio analysis provides visibility into operating and commission costs relative to financial performance.

6. Ownership Analysis

Shareholding distribution provides a clear picture of the composition and concentration of different investor categories.

7. Data-Driven Decision Making

By bringing all these dimensions together, the dashboard allows stakeholders to move from "What is happening?" to "Where is it happening?" and "What factors are associated with the performance?"

#  Project Summary

Stakeholder Insights and Performance Dashboard is an interactive Tableau-based business intelligence solution that consolidates insurance, stakeholder, profitability, premium, and asset-management metrics into a single executive dashboard. Through dynamic KPIs, stakeholder comparisons, time-series analysis, geographical profitability analysis, AUM distribution, shareholding analysis, and cost-ratio visualization, the dashboard enables users to explore business performance and derive actionable insights from multiple perspectives.
