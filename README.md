# Superstore Sales Performance Analysis  
End-to-End Data Analytics Project (Excel → SQL → Python)

---

## Project Overview
This project analyzes retail sales data from a Superstore dataset to uncover revenue drivers, profitability issues, discount effects, and customer behavior patterns.  
It follows a real-world analytics workflow using Excel Power Query for data cleaning, MySQL for storage & validation, and Python for EDA & visualization.

---

## Objectives
- Prepare and clean raw data
- Build a structured data pipeline
- Analyze sales, profit, and discount patterns
- Identify growth opportunities and cost leakages
- Deliver business insights and recommendations

---

## Tools & Technologies

| Stage                      | Tool                        | Purpose                                        |
|----------------------------|-----------------------------|------------------------------------------------|
| Data Cleaning & Preprocessing | Excel (Power Query)     | Remove blanks, fix errors, clean data           |
| Database & Querying        | MySQL / SQL                 | Store clean data, validate/test, run queries    |
| Analysis & Visualization   | Python (Pandas, Matplotlib, Seaborn) | EDA, KPIs, trends, stats, plotting           |
| Documentation              | Jupyter, PDF, PPT           | Storytelling for management/portfolio           |

Skills: ETL • EDA • SQL • Python • Visualization • Business Intelligence

---

## Dataset Summary

| Detail      | Value    |
|-------------|----------|
| Rows        | 9,994    |
| Columns     | 21       |
| Time Span   | ~3 years |
| Key Fields  | Sales, Profit, Quantity, Discount, Category, Segment, Region, Ship Mode |

_Clean dataset used: Cleaned_Superstore.csv_

---

## Key Metrics

| Metric             | Value       |
|--------------------|------------|
| Total Sales        | $2.29M     |
| Total Profit       | $286K      |
| Profit Margin      | 12.47%     |
| Orders             | 5,009      |
| Customers          | 793        |
| Avg Order Value    | $458.61    |
| Avg Discount       | 15.62%     |

---

## Key Insights

**Category & Product Performance**
- Technology: ~$836K revenue, ~$145K profit (highest margin)
- Office Supplies: ~$719K revenue, ~$122K profit
- Furniture: ~$742K revenue but low/negative margin
- Tables sub-category incurred ~$17K loss

Insight: High revenue does not mean high profitability. Close product-level profit monitoring is required.

**Customer Segment Insights**
| Segment     | Revenue Contribution |
|-------------|---------------------|
| Consumer    | 52% ($1.2M)       |
| Corporate   | 30% ($690K)       |
| Home Office | 18% ($405K)       |

Insight: Corporate segment should be a focus for increasing profitability.

**Regional Insights**
| Region  | Sales      |
|---------|------------|
| West    | $725K      |
| East    | $680K      |
| Central | $480K      |
| South   | $400K      |

**Discount Behavior**
- Average discount: 15.62%
- Discounts above 30% frequently lead to negative profit
- Strong negative correlation between discount and profit margin

Insight: Reducing deep discounts can recover $20K+ per year in profit.

---

## Recommendations

- Re-evaluate pricing & supplier strategy for loss-making products (especially Tables)
- Limit high discounting and adopt value-based pricing
- Increase focus on Corporate customer acquisition
- Expand presence in South region
- Promote Standard shipping to reduce logistics cost

---

## Project Workflow

1. Data Cleaning: Excel (Power Query) for missing value and structure correction  
2. Data Upload: MySQL for storage  
3. Analysis: Python (Pandas, Seaborn, Matplotlib) for EDA, KPI reports, for-loop visualizations  
4. Reporting: Jupyter Notebook, PDF/storytelling, with executive summary  

---

## Author
- [PRIYANKA_LAKRA]
