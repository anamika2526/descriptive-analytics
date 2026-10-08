# PhonePe Descriptive Analytics Report: Daily Transaction Behavior at Scale

Author: Anamika Gupta  
Course: BCA (DS & AI) | Section:BCADS27  
Date: october 6, 2026  

---

## 📌 Executive Summary
This project provides a **Descriptive Analytics** layer built over a aggregated PhonePe dataset to analyze key performance indicators (KPIs), regional demand trends, payment operational success, and merchant activity metrics.

The dataset includes **200 records** covering **8 states** and **6 payment categories** over a 5-day observation window.

---

📊 Key Insights & Summary Metrics

| Metric | Aggregate Value |
| :--- | :--- |
| **Total Volume Processed** | 23.85 Million Transactions |
| **Total Gross Merchandise Value (GMV)** | ₹1,428.14 Cr (~₹105.40 Billion aggregate) |
| **Average Success Rate** | 97.96% |
| **Overall CSAT Score** | 4.62 / 5.0 |
| **Top Performing State** | Maharashtra (31.71% volume share, 82.14M total) |
| **Highest CSAT State** | Rajasthan (4.78 / 5.0) |
| **Lowest CSAT State** | West Bengal (4.60 / 5.0) |

---

🎯 Business Questions Addressed
* **Daily Trends:** Tracking daily transaction volume and GMV spikes over time.
* **Geographic Demand:** Identifying top-contributing Indian states in transaction volume & monetary value.
* **Operational Performance:** Evaluating network success rate stability vs. Customer Satisfaction (CSAT).
* **Merchant Dynamics:** Correlation between active merchant density and state-wise transaction growth.
* **Temporal Patterns:** Comparing weekday vs. weekend transaction distributions (Avg. 1.25M weekday vs. 1.33M weekend).




# RetailPulse Sales Reporting – IBM Cognos Analytics

## About the Project

This project contains practical exercises performed using **IBM Cognos Analytics** with the **RetailPulse Sales** package.

The practicals demonstrate how to create reports, apply filters, work with regions and dates, organize sales data, and create summarized reports using IBM Cognos Analytics.

## Tools and Technologies

* IBM Cognos Analytics
* RetailPulse Sales Package
* Cognos Reporting
* List Reports
* Filters
* Prompts
* Crosstab Reports

## Practicals Included

### Practical 1 – First RetailPulse Sales Report

Created a basic list report using the RetailPulse Sales package.

The report contains:

* Region
* Product Category
* Sales Amount

### Practical 2 – Grouped Retail Sales Report

Created a detailed Retail Sales Report by grouping the data based on:

* Region
* Store Name
* Product Category
* Quantity
* Sales Amount

The report also includes:

* Currency formatting for Sales Amount
* Total Sales Amount
* Proper alignment of numerical columns
* Report header and run date

### Practical 3 – Filter RetailPulse Sales by Region and Date

Applied filters to focus the report on a particular region and reporting period.

The report uses:

* Region filter
* Sales Date filter
* Date range
* AND condition between filters
* Prompt-based filtering

The practical report demonstrates sales information for the **North** region. The report includes stores such as Gomti Nagar, Hazratganj, and Lucknow Central.

The North region total shown in the report is:

**₹628,000.00**

### Practical 4 – RetailPulse Region-Product Crosstab

Created a crosstab report to summarize sales by region and product category.

The report displays:

* Region
* Electronics Sales
* Clothing Sales
* Home & Kitchen Sales
* Quantity

Example summary:

| Region | Electronics | Clothing | Home & Kitchen | Quantity |
| ------ | ----------: | -------: | -------------: | -------: |
| East   |    ₹120,000 |  ₹28,000 |        ₹34,000 |       55 |
| North  |    ₹432,000 |  ₹82,000 |       ₹114,000 |      175 |
| South  |    ₹384,000 |  ₹78,000 |       ₹100,000 |      160 |
| West   |    ₹288,000 |  ₹46,000 |        ₹68,000 |      104 |

## Learning Outcomes

After completing these practicals, I learned how to:

* Create reports in IBM Cognos Analytics
* Select data items from a package
* Create list reports
* Group and organize report data
* Apply filters
* Apply date-range conditions
* Create prompts
* Create crosstab reports
* Calculate totals
* Format numerical and currency values
* Present sales information in a meaningful way

## Project Structure

```text
RetailPulse-Cognos/
│
├── README.md
├── Practical-1/
├── Practical-2/
├── Practical-3/
└── Practical-4/
```

## Conclusion

The RetailPulse Sales practicals provide hands-on experience with **IBM Cognos Analytics reporting**. The project demonstrates the use of lists, grouping, filters, prompts, totals, and crosstab reports to analyze and present retail sales data effectively.

## Author

**Anamika Gupta**

BCA – Data Science & AI
Babu Banarasi Das University (BBDU), Lucknow

