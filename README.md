# sales-performance-analytics-python
End-to-end sales data generation, analysis, and Excel reporting using Python
# Sales Performance Analytics using Python

This project demonstrates an end-to-end sales analytics workflow using Python, from synthetic data generation to automated Excel reporting.

## Project Overview
- Generated sales data for 800 representatives with individual revenue targets
- Simulated high-volume transactions across products, regions, and dates
- Calculated actual sales, achievement percentage, and commissions
- Produced a fully formatted Excel report with conditional formatting

## Tech Stack
- Python
- Pandas
- NumPy
- XlsxWriter
- Excel Automation

## Project Structure
sales-performance-analytics-python/
├── data_generation.py
├── sales_analysis.py
├── sample_output/
│ └── Final_Sales_Report.xlsx


## Business Logic
- Target Achievement = Actual Sales / Target Revenue
- Commission:
  - 5% if target met or exceeded
  - 2% if target not met

## Output
The final output is an executive-ready Excel report highlighting:
- Sales performance
- Achievement status
- Commission earned




