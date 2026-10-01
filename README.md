# Week 4 – Data Visualization Project

## Project Overview
This repository contains my Week 4 internship assignment, focused on data visualization and an end-to-end business analysis workflow.

The project uses a sales dataset and follows the assignment workflow:
1. Clean and explore the dataset in Python.
2. Analyze the data using Pandas.
3. Prepare supporting analysis in Excel.
4. Build an interactive dashboard in Power BI.
5. Compile the findings into a final PDF report.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Microsoft Excel
- Microsoft Power BI
- Notebook

## Dataset
The source dataset contains 700 records and 16 original columns covering:
- Segment
- Country
- Product
- Discount Band
- Units Sold
- Manufacturing Price
- Sale Price
- Gross Sales
- Discounts
- Sales
- COGS
- Profit
- Date
- Month Number
- Month Name
- Year

## Data Cleaning
The Python workflow included:
- Inspecting dataset shape, data types, descriptive statistics, and missing values.
- Stripping whitespace from column names.
- Checking and removing duplicate records.
- Filling missing numeric values with the column median.
- Filling missing categorical values with the column mode.
- Converting the Date column to a datetime type.
- Deriving Year, Month, and Month_Name from Date.
- Creating business metrics for Profit Margin, Discount Percentage, and Revenue per Unit.

The original dataset contained 53 missing values in Discount Band. These were filled using the mode of the categorical column. No duplicate records were identified.

## Calculated Metrics
The project uses the following calculated fields:

### Profit Margin
Profit Margin = Profit / Sales × 100

### Discount Percentage
Discount Percentage = Discounts / Gross Sales × 100

### Revenue per Unit
Revenue per Unit = Sales / Units Sold

### YoY Growth
YoY Growth compares sales in the selected year with the previous year.

## Key Results
Based on the cleaned dataset:
- Total Sales: approximately $118.73M
- Total Profit: approximately $16.89M
- Total Units Sold: approximately 1.13M
- Gross Sales: approximately $127.93M
- Discounts: approximately $9.21M
- Overall Profit Margin: approximately 14.23%
- Overall Discount Impact: approximately 7.20%
- Average Revenue per Unit: approximately $105.46
- Sales YoY Growth from 2013 to 2014: approximately 249.46%

## Main Analysis Findings
### Year
Sales increased from approximately $26.42M in 2013 to approximately $92.31M in 2014.

### Country
The United States of America generated the highest total sales, followed closely by Canada and France.

### Product
Paseo generated the highest total sales and the highest total profit among the products in the dataset.

### Segment
Government generated the highest total sales and profit. Enterprise recorded a negative total profit in the analyzed dataset.

### Profit
Total profit was approximately $16.89M across the dataset.

## Power BI Dashboard
The Power BI file contains the interactive dashboard created for the assignment.

The dashboard is organized into three analytical pages:
1. Executive Overview
2. Product Intelligence
3. Geography & Segment

The dashboard uses KPI cards, trend charts, bar charts, treemap, donut chart, scatter analysis, slicers, and other supporting visuals.

## Repository Structure
```text
Week_4_Data_Visualization_Capstone/
│
├── README.md
│
├── 01 Dataset/
│   └── Sample data.csv
│
├── 02 Python/
│   └── Week_4_Data_Analysis.ipynb
│
├── 03 Cleaned_Data/
│   └── Cleaned Sales Data.csv
│
├── 04 Excel/
│   └── Week_4_Analysis.xlsx
│
├── 05 PowerBI/
│   └── Week 4 Data Visualization PowerBI.pbix
│
├── 06 Screenshots/
│   └── Dashboard screenshots
│
└── 07 Report/
    ├── Week_4_Data_Visualization_Report.pdf
    └── report_assets/
```

## How to Review the Project
1. Start with the final PDF report in `07 Report`.
2. Open the Python notebook in `02 Python` to review the cleaning and analysis workflow.
3. Open `03 Cleaned_Data/Cleaned Sales Data.csv` to inspect the cleaned dataset.
4. Open `04 Excel/Week_4_Analysis.xlsx` to review the Excel analysis.
5. Open the `.pbix` file in Power BI Desktop to interact with the dashboard.

## Notes
The project report summarizes the work performed in Python, Excel, and Power BI. The `.pbix` file requires Power BI Desktop to open and interact with the dashboard.


## Done by Kirti Sambyal (Github: kirti220)
