# Loan Data Analysis Project (Power BI + SQL + DAX)

This project analyzes loan data using Power BI Desktop and Microsoft SQL Server, with data validation in Excel. It includes advanced DAX measures and interactive dashboards to deliver meaningful business insights.

## Tools & Technologies Used
- Microsoft SQL Server
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query Editor
- Microsoft Excel

---

## Project Workflow

1. **SQL Server Setup**
   - Installed Microsoft SQL Server
   - Imported and cleaned data in SQL Server
   - Structured dataset with correct data types and formats

2. **Power BI Integration**
   - Imported SQL data directly into Power BI Desktop
   - Performed data profiling and data type correction in Power Query Editor

3. **Data Modeling & Cleaning**
   - Renamed columns, handled nulls, reshaped data
   - Performed multiple data validations after DAX calculations

---

## Key Data Validation Performed

- Average Loan by Age Group (cross-checked in Excel)
- Default Rate by Year (manually verified)
- Median Loan Amount validation (using Excel and DAX)
- Donut Chart data vs source consistency
- Cross-validation for education type and credit categories

---

## DAX Measures and Visuals

|  Analysis | DAX Used |
|------------|-------------|
| Loan Amount by Purpose | `SUMX`, `FILTER`, `NOT`, `ISBLANK` |
| Average Income by Employment Type | `CALCULATE`, `AVERAGE`, `ALLEXCEPT` |
| Default Rate by Employment Type | `COUNTROWS`, `DIVIDE`, `FILTER`, `ALL`, `ALLEXCEPT` |
| Average Loan by Age Groups | `AVERAGE`, `AVERAGEX`, `VALUES` |
| YOY Loan Amount Change | `DATESYTD`, `SAMEPERIODLASTYEAR` |
| Decomposition Tree | `SWITCH` |
| Others | `MEDIANX`, `CALCULATE`, `SUM`, `COUNT`, `ALLEXCEPT` |

---

##  Dashboard Highlights

- Visuals: Line Charts, Donut Charts, Clustered Columns, Decomposition Tree
- YOY & YTD trend measures using DAX
- Credit score category analysis
- Filters by age group, marital status, and education

---

##  Files Included

- `LOAN.pbix` – Final Power BI dashboard
- `loan_raw_data.xlsx` – Raw/validated Excel data
- `README.md` – Project documentation

---

##  Author

**Anjali Kushwaha**  
