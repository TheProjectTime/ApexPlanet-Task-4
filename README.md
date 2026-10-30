# ApexPlanet Data Analytics Internship – Task 4

## Data Storytelling & Statistical Validation

### 1. Project Overview

This project is the fourth task of the ApexPlanet Data Analytics Internship. The main objective is to convert the findings from previous data analysis tasks into a meaningful business story and validate important findings using statistical methods.

The project focuses on sales performance analysis, data visualization, hypothesis testing, and business recommendations using Python and Microsoft Power BI.

### 2. Project Objectives

- Analyse overall sales performance and identify important business insights.
- Identify top-performing product categories, products, and cities.
- Present key performance indicators (KPIs) through visualizations.
- Develop an interactive Power BI dashboard.
- Perform hypothesis testing to validate a business question.
- Provide data-driven recommendations for business improvement.

### 3. Tools and Technologies

| Tool / Technology    | Purpose                                   |
| -------------------- | ----------------------------------------- |
| Python               | Data analysis and statistical testing     |
| Google Colab         | Writing and executing Python code         |
| Pandas               | Data manipulation and analysis            |
| Matplotlib / Seaborn | Data visualization                        |
| SciPy                | Statistical hypothesis testing            |
| Microsoft Power BI   | Interactive dashboard development         |
| Microsoft Excel      | Dataset management                        |
| GitHub               | Project documentation and version control |

### 4. Dataset Description

The project uses the sales dataset provided during the ApexPlanet internship.

- **Total Records:** 1,000
- **Total Columns:** 12
- **Key Information:** Order details, customer information, product categories, quantity, unit price, and total sales.
- **Data Period:** 1 January 2025 to 1 January 2026.

### 5. Key Performance Indicators (KPIs)

The following KPIs were calculated during the analysis:

| KPI                 |       Result |
| ------------------- | -----------: |
| Total Revenue       | ₹13.94 Crore |
| Total Orders        |          992 |
| Average Order Value | ₹1,40,523.63 |
| Total Quantity Sold |        5,435 |
| Unique Customers    |          947 |

### 6. Key Business Insights

- **Top Revenue Category:** Electronics generated the highest revenue of approximately ₹5.08 crore.
- **Leading Products:** Laptop and Mobile were the highest revenue-generating products.
- **Top Performing City:** Patna generated the highest city-wise revenue of approximately ₹1.93 crore.
- **Sales Trends:** Monthly sales analysis showed variations in revenue over the study period.

_Note: January 2026 contains only one day's data, so it is treated as a partial month._

### 7. Hypothesis Testing

A statistical hypothesis test was conducted to examine whether there was a significant difference in average order revenue per customer between Electronics and Fashion.

**Research Question:**

Is there a statistically significant difference in average order revenue per customer between Electronics and Fashion?

**Hypotheses:**

- **Null Hypothesis (H₀):** There is no statistically significant difference in average order revenue per customer between Electronics and Fashion.
- **Alternative Hypothesis (H₁):** There is a statistically significant difference in average order revenue per customer between Electronics and Fashion.

**Methodology:**

Welch's Independent-Samples T-Test was used with a 5% significance level (α = 0.05). Seven customers who purchased from both categories were excluded to maintain independent comparison groups.

**Results:**

| Metric                             |  Electronics |      Fashion |
| ---------------------------------- | -----------: | -----------: |
| Exclusive Customers                |          344 |          149 |
| Average Order Revenue per Customer | ₹1,43,621.03 | ₹1,29,713.92 |

| Statistical Measure     |                   Result |
| ----------------------- | -----------------------: |
| T-Statistic             |                   1.3045 |
| P-Value                 |                 0.193027 |
| Mean Difference         |               ₹13,907.12 |
| 95% Confidence Interval | -₹7,069.57 to ₹34,883.80 |
| Significance Level      |                     0.05 |

**Conclusion:**

The p-value (0.193027) is greater than the significance level (0.05). Therefore, the null hypothesis is not rejected.

Although Electronics has a higher observed average than Fashion, the difference is not statistically significant at the 5% level.

### 8. Business Recommendations

Based on the analysis, the following recommendations are suggested:

1. Focus on the high-performing Electronics category to maintain revenue growth.
2. Identify opportunities to improve the performance of lower-revenue categories.
3. Analyse city-wise sales performance to understand regional demand.
4. Monitor monthly sales trends to identify changes in business performance.
5. Use interactive dashboards to support regular KPI monitoring and data-driven decisions.

### 9. Project Structure

```text
ApexPlanet-Task-4/
│
├── data/
│   └── ApexPlanet_DataAnalytics_Dataset.xlsx
│
├── notebooks/
│   └── ApexPlanet_Task_4_Statistical_Validation.ipynb
│
├── reports/
│   ├── Hypothesis_Testing_Summary.md
│   └── task4_hypothesis_testing_summary.csv
│
├── presentation/
│   ├── ApexPlanet_Task_4_Final_Presentation.pptx
│   └── Dashboard_Screenshot.png
│
└── README.md
```

### 10. Deliverables

- Python notebook containing the analysis and statistical testing.
- Hypothesis testing summary report.
- Statistical results in CSV format.
- Final PowerPoint presentation.
- Power BI dashboard screenshot.
- Stakeholder presentation video.

### 11. Learning Outcomes

Through this task, I gained practical experience in:

- Converting data analysis results into a business story.
- Identifying and communicating meaningful business insights.
- Performing hypothesis testing using Python.
- Understanding p-values, confidence intervals, and statistical significance.
- Creating business recommendations based on data.
- Presenting analytical findings through a professional presentation.

### 12. Internship Information

**Internship:** Data Analytics Internship  
**Organization:** ApexPlanet Software Pvt. Ltd.  
**Task:** Task 4 – Data Storytelling & Statistical Validation

---

### Conclusion

This project helped me understand how data analysis and statistical validation can support business decision-making. It also improved my practical skills in Python, Power BI, data visualization, and communicating analytical findings.
