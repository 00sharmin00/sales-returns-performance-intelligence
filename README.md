# Sales & Returns Performance Intelligence

**An Interactive Retail Sales, Profitability & Returns Analysis Dashboard | Power BI**

## 1. Executive Summary

The **Sales & Returns Performance Intelligence** project delivers an interactive Power BI dashboard designed to evaluate retail sales performance, profitability, order activity, and product return patterns.

Using Power Query for data preparation and DAX for analytical calculations, this project transforms transactional sales data into actionable business insights. It enables stakeholders to monitor key performance indicators (KPIs), compare historical performance, identify sales fluctuations, and evaluate the relationship between orders and returns.

The dashboard supports data-driven decisions related to sales strategy, inventory management, and profitability monitoring.

## 2. Business Problem

Retail businesses must balance revenue growth with profitability and effective returns management. However, analyzing sales and returns separately can make it difficult to identify operational issues and understand changes in business performance.

Key business challenges addressed in this project include:

- **Returns Monitoring:** Understanding the relationship between unique orders and unique returns.
- **Profitability Analysis:** Tracking profit performance and percentage changes over time.
- **Historical Benchmarking:** Comparing current performance with previous-year sales and profit metrics.
- **Sales Trend Analysis:** Identifying monthly and quarterly fluctuations in sales performance.
- **Performance Visibility:** Presenting multiple business metrics in a centralized, interactive dashboard.

## 3. Project Objectives

- Analyze overall sales and profit performance.
- Evaluate sales and profit changes against historical benchmarks.
- Compare unique orders with unique returns.
- Identify sales trends and seasonal fluctuations.
- Enable year, quarter, month, and day-level analysis.
- Build an executive-style Power BI dashboard for business stakeholders.

## 4. Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Excel | Source data review and preliminary inspection |
| Power Query | Data cleaning, transformation, and preparation |
| Power BI | Interactive dashboard development |
| DAX | KPI calculations, percentage changes, and analytical measures |
| Data Visualization | Communicating trends, comparisons, and performance indicators |

## 5. Dataset Overview

The project uses transactional retail sales data containing information required for sales performance, profitability, order, return, and time-based analysis.

**Analytical dimensions include:**
- Sales and profit metrics
- Unique orders and unique returns
- Previous-year performance benchmarks
- Year, quarter, month, and day
- Sales and profit percentage changes

*Note: Update this section with the actual dataset name, source URL, date range, row count, and column names before publishing. Include only fields present in your dataset.*

## 6. Key Performance Indicators (KPIs)

The dashboard focuses on the following analytical measures:

- Total Sales
- Total Profit
- Profit Percentage Change
- Unique Orders
- Unique Returns
- Return-to-Order Ratio
- Previous Year Sales
- Previous Year Profit
- Period-over-Period Sales Variance

### Highlighted Metrics

| Metric | Reported Value |
|---|---:|
| Profit Percentage Change | 93.07% |
| Main Baseline Profit Share | 81.43% |
| Historical Sales Baseline | 2K volume |

**Important:** These values are reported from the current project description. Before publication, confirm the calculation definitions, units, date range, and whether each percentage represents growth, share, or another measure. The 2K baseline should also be labeled with the correct unit.

## 7. Dashboard Features

### A. Sales Performance Analysis
- Monitor sales performance across reporting periods.
- Compare sales trends by year, quarter, and month.
- Identify periods of growth and decline.
- Analyze percentage changes in sales.

### B. Profitability Analysis
- Track total profit and profit-related KPIs.
- Evaluate profit percentage changes.
- Compare current results against historical benchmarks.
- Identify periods that may require further profitability investigation.

### C. Returns & Order Intelligence
- Compare unique orders with unique returns.
- Evaluate the return-to-order ratio.
- Identify potential return-related operational issues.
- Support further investigation into product and fulfillment performance.

### D. Time-Based Analysis
- Drill down from year to quarter, month, and day.
- Explore historical performance patterns.
- Identify demand fluctuations and potential seasonal trends.

## 8. Key Analytical Insights

Based on the current dashboard observations:

1. **Profit Performance:** The dashboard displays a reported 93.07% profit percentage change metric, providing a starting point for evaluating profitability trends.
2. **Sales Fluctuations:** Quarterly and monthly visualizations help reveal changes in sales performance across 2024–2025.
3. **Historical Benchmarking:** Comparative visuals show a reported 2K sales baseline and an 81.43% main baseline profit-share metric.
4. **Returns Monitoring:** Comparing unique orders and unique returns provides visibility into return activity and helps identify areas for further analysis.

*These observations should be validated against the underlying dataset and measure definitions before being presented as final business conclusions.*

## 9. Data Preparation & Analytical Workflow

1. **Data Inspection:** Reviewed the available transactional data and relevant fields.
2. **Data Cleaning:** Used Power Query to inspect data types, missing values, duplicate records, and inconsistencies where applicable.
3. **Data Transformation:** Structured fields and prepared the dataset for reporting.
4. **DAX Development:** Created measures for KPIs, historical comparisons, percentage changes, and return analysis.
5. **Dashboard Design:** Built interactive visuals for sales trends, profitability, order activity, and returns.
6. **Insight Generation:** Interpreted dashboard results to identify performance patterns and potential business opportunities.

## 10. Business Recommendations

Based on the analysis framework, retail stakeholders can:

- Monitor return-to-order ratios over time and investigate unusual increases.
- Review products or periods associated with declining profitability.
- Compare sales performance with historical benchmarks before making inventory decisions.
- Investigate monthly and quarterly sales declines to understand potential demand changes.
- Combine sales, profit, and returns metrics to support more balanced operational decisions.

*Recommendations should be prioritized using verified findings from the actual dataset.*

## 11. Dashboard Preview

Add your actual Power BI dashboard screenshots to the `screenshots/` folder in this repository.

### Sales Performance Overview

![Sales Performance Overview](screenshots/sales-performance-overview.png)

### Returns & Profitability Analysis

![Returns and Profitability Analysis](screenshots/returns-profitability-analysis.png)

*Replace the image paths above if your screenshot filenames are different.*

## 12. Repository Structure

```text
sales-returns-performance-intelligence/
│
├── README.md
├── data/
│   └── sales_data_sample.csv
├── power-bi/
│   └── sales-returns-dashboard.pbix
├── screenshots/
│   ├── sales-performance-overview.png
│   └── returns-profitability-analysis.png
├── docs/
│   ├── data-dictionary.md
│   └── data-cleaning-methodology.md
└── dax/
    └── measures.md
```

*This is a suggested structure. Keep only files and folders that actually exist in your repository, and replace example filenames with your actual filenames.*

## 13. Skills Demonstrated

- Data Cleaning & Transformation
- Power Query
- DAX Measures & KPI Development
- Sales Performance Analysis
- Profitability Analysis
- Returns & Order Analysis
- Time-Series Analysis
- Data Visualization & Dashboard Design
- Business Insight Communication

## 14. Limitations

- The reliability of the findings depends on the quality and completeness of the source data.
- Return patterns alone do not establish the reasons for customer returns.
- Historical comparisons require consistent definitions and comparable reporting periods.
- Percentage-change measures should be interpreted using their documented formulas and baseline values.

## 15. Future Improvements

- Add product-level and category-level return analysis.
- Investigate return reasons if the dataset contains them.
- Incorporate customer and regional performance analysis where supported by the data.
- Add automated refresh and data-quality checks.
- Extend the analysis with SQL-based data preparation and validation if applicable.

## 16. Author

**Sharmin Akter**  
Junior Data Analyst | Excel • SQL • Power BI • Power Query • DAX

- **GitHub:** [Add your GitHub profile URL]
- **LinkedIn:** [Add your LinkedIn profile URL]
- **Portfolio:** [Add your portfolio website URL]

---

*This project demonstrates the use of business intelligence tools to transform retail transaction data into interactive performance reporting and actionable analytical insights.*
