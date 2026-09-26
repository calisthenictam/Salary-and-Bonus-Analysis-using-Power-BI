# 💰 Salary & Bonus Analysis Dashboard | Power BI

![Dashboard Preview](https://github.com/calisthenictam/C-B-Analytics-Bonus-Analysis-Dashboard/blob/main/Sales%20and%20Bonus%20Analysis%20Dashboard.png)

This project analyses employee salary and bonus data to understand compensation patterns across departments, job roles, business units, locations, and employee demographics. It transforms a raw **Excel/CSV employee dataset** of **500 employee records** into an interactive **Power BI dashboard**, making compensation trends easier to explore than in a traditional spreadsheet. The dataset includes job title, department, business unit, gender, ethnicity, age, hire date, annual salary, bonus percentage, country, city, and exit date.

## 🎯 Problem I Solved

The original data was locked in a spreadsheet, making it difficult to quickly analyse compensation across different areas of the organization. This project was designed to answer:

- Which departments have the highest average salaries?
- How are bonuses distributed across different job roles?
- Which business units have higher compensation levels?
- How does salary vary by location and employee characteristics?
- Which roles have higher average bonus percentages?
- What overall compensation patterns can be identified?

Instead of manually reviewing individual rows in Excel, I built a centralized, interactive dashboard where users can filter and explore the data efficiently.

## 🛠️ Technical Stack & Tools

- **Data Source:** Excel/CSV employee dataset
- **Initial Inspection:** Microsoft Excel
- **Data Preparation:** Power Query
- **Modelling & Measures:** DAX
- **Visualization:** Power BI

## 💻 Data Preparation & Analysis

This project was executed as an end-to-end workflow, from raw data to a fully interactive dashboard.

### 1. Data Cleaning & Preparation (Power Query)
- **Standardization:** Cleaned and standardized data types and categories across all fields.
- **Missing Values:** Checked and handled missing/null values throughout the dataset.
- **Field Preparation:** Prepared salary and bonus fields and transformed date fields (hire date, exit date) for accurate reporting.
- **Structuring:** Organized the data into a model suitable for reporting and visualization.

### 2. Dashboard Development (Power BI & DAX)
- **Calculated Measures:** Built DAX measures and KPIs for total and average salary, average bonus percentage, and comparative metrics.
- **Interactive Filters:** Added filters for department, job title, business unit, location, and other dimensions, allowing users to drill into specific segments on demand.

## 📈 Business Outcome & Key Findings

The dashboard consolidates hundreds of employee records into clear, filterable views, ready for direct use by HR and leadership teams.

| Analysis Area | What It Shows | Business Use |
|---|---|---|
| **Salary by Department** | Average/total salary across departments | Identify high-cost vs. lean departments |
| **Salary by Job Title** | Compensation spread by role | Benchmark roles against market/internal equity |
| **Bonus Distribution** | Bonus % across roles and units | Spot inconsistent or outlier bonus practices |
| **Business Unit Comparison** | Compensation levels by unit | Support budget planning across units |
| **Geographic Distribution** | Salary variance by country/city | Inform location-based pay strategy |
| **Demographic Insights** | Salary/bonus by gender, age, ethnicity | Support pay equity review |

- **Insight Example:** *The dashboard makes it possible to instantly compare average bonus percentage by job title, surfacing roles that are consistently over- or under-rewarded relative to peers.*

## 🔗 Repository Contents

- `Sales And Bonus Analysis using powr-Bi.pbit` — The complete Power BI template file with data model, DAX measures, and dashboard visuals.
- `Sales and Bonus Analysis Dashboard.png` — Static preview image of the finished dashboard.
- `employee_data.csv` — The raw employee dataset used to build the analysis.

## Skills Demonstrated

Data Cleaning & Transformation · Excel · Power Query · Power BI · DAX · Data Modelling · Data Visualization · Business & HR Analytics · Dashboard Development
