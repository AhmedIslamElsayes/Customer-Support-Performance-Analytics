# Customer Support Cases Analysis Dashboard

## Business Problem

Managing more than 75,000 customer support cases across multiple categories, priorities, statuses, and support channels can be challenging. The organization needed a centralized analytical solution to monitor operational performance, improve SLA compliance, identify recurring issues, evaluate agent productivity, and support data-driven decision-making.

---

## Data Collection

The project was built using multiple datasets organized into one fact table and several dimension tables.

### Fact Table
- Fact Cases

### Dimension Tables
- Dim Customer
- Dim Agent
- Dim Date
- Dim Status
- Dim Priority
- Dim Category
- Dim Type
- Dim Sub Type
- Dim Origin

---

## Data Cleaning & Transformation

Using Power Query, the data was prepared through several transformation steps:

- Removing duplicates
- Handling missing values
- Standardizing data types
- Formatting date fields
- Creating calculated columns
- Data validation and quality checks
- Building an Issue Hierarchy

### Issue Hierarchy

Category → Type → Sub Type

This hierarchy enables detailed drill-down analysis to identify the root causes of customer issues.

---

## Data Modeling

A Star Schema model was implemented to optimize performance and simplify analytical reporting.

### Model Structure

Fact Cases was placed at the center of the model and connected to all dimension tables.

### Benefits

- Improved report performance
- Simplified DAX calculations
- Better scalability
- Enhanced drill-down capabilities
- Easier maintenance

---

## Descriptive Analytics

The first stage of analysis focused on understanding what happened within the support operation.

### Key Performance Indicators (KPIs)

- Total Cases
- Open Cases
- Closed Cases
- Closure Rate %
- SLA Compliance %
- Average Resolution Time
- Paid vs Unpaid Customers

### Analysis Performed

- Cases Trend Over Time
- Cases by Category
- Cases by Status
- Cases by Priority
- Cases by Origin
- Customer Distribution Analysis

---

## Diagnostic Analytics

The second stage focused on identifying why certain operational issues occurred.

### Analysis Performed

- Category Analysis
- Type Analysis
- Sub Type Analysis
- Resolution Time Analysis
- Reopen Rate Analysis
- Escalation Analysis
- Decomposition Tree Analysis

### Key Finding

Network & Connectivity Related issues represented the largest share of customer support cases, indicating a major operational focus area.

---

## Predictive Analytics

The final stage focused on forecasting future support performance using Power BI forecasting capabilities.

### Forecasted Metrics

- Future Case Volume
- Future Resolution Time
- Future SLA Compliance

### Business Impact

These forecasts help management proactively allocate resources, plan workforce requirements, and reduce the risk of SLA breaches.

---

## Business Recommendations

Based on the analysis, the following recommendations were identified:

- Prioritize Network & Connectivity issues due to their high case volume.
- Improve Provisioning processes to reduce recurring support requests.
- Reduce Reopened Cases through better first-time resolution practices.
- Optimize workload distribution among support agents.
- Allocate additional resources during forecasted peak periods.
- Continuously monitor SLA performance to ensure service quality.

---

## Project Outcome

This project transformed over 75,000 customer support records into a comprehensive analytical solution that combines:

- Descriptive Analytics
- Diagnostic Analytics
- Predictive Analytics

The dashboard provides management with actionable insights that improve operational efficiency, enhance customer experience, and support strategic decision-making.

---

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Star Schema
- Forecasting
- Data Visualization

---

## Author

Ahmed Eslam

Data Analyst | Business Intelligence Enthusiast
