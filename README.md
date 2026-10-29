# IT-Expenditure-Analysis
IT Expenditure Analysis
Project Overview
This project explores IT expenditure data to understand how technology-related costs are distributed across business areas, regions, countries, IT areas, and cost elements. The workbook contains two worksheets: Data and Future Data. It includes actual, forecast, and plan values in the main dataset, making it suitable for budget monitoring and expenditure comparison.
Dataset
Source file: `IT Expenditure dataset.xlsx`
Data: 81,610 data rows (plus the header row), with 12 columns.
Future Data: 12,119 data rows (plus the header row), with 10 columns.
The workbook contains financial values, including both positive and negative amounts. Negative values may represent credits, reversals, or adjustments and should be checked against the dataset's business rules before interpretation.
Main fields
Field	Description
Date	Period associated with the expenditure record
Business Area	Business function or organizational area
Region	Geographic region
Country	Country associated with the record
IT Sub Area	More detailed IT function or sub-area
IT Area	Broader IT function
Cost element name	Specific type of cost
Cost Element Group	High-level grouping of costs
Cost Element Sub Group	More detailed cost classification
Actual	Recorded actual expenditure
Forecast	Estimated expenditure
Plan	Planned or budgeted expenditure
The `Future Data` sheet has fewer columns than `Data`; confirm its available fields before combining the sheets for analysis.
Project Objectives
Organize and inspect the expenditure data.
Compare actual expenditure with forecast and plan values where those fields are available.
Identify the business areas, IT areas, regions, countries, and cost elements associated with the largest expenditure.
Examine expenditure patterns over time.
Highlight potential budget variances and unusual positive or negative values.
Use the findings to support budget reviews and IT cost-management decisions.
Work Completed
Inspected the workbook structure and identified its two worksheets.
Identified the principal dimensions used to classify expenditure: time, organization, geography, IT function, and cost element.
Identified the financial measures available in the main `Data` sheet: Actual, Forecast, and Plan.
Established a framework for comparing expenditure, investigating variances, and summarizing cost drivers.
Important: This README describes the dataset and analysis approach. It does not claim that detailed visualizations, statistical tests, or a complete variance analysis have been completed. Add specific charts, calculations, and confirmed findings here after performing the analysis.
Recommended Analysis
Data quality: Check missing values, duplicate records, inconsistent category names, date formats, and numeric types.
Time trends: Aggregate expenditure by month or other available reporting period.
Budget comparison: Calculate `Actual - Plan` and `Actual - Forecast` where comparable values exist. Positive and negative variances should be interpreted according to the organization's accounting conventions.
Cost drivers: Rank cost elements, IT areas, business areas, and countries by total expenditure.
Geographic comparison: Compare expenditure by region and country, taking into account differences in organizational size and scope.
Future outlook: Review the `Future Data` sheet separately and document how it relates to the main dataset before comparing or combining them.
Visualizations: Use line charts for time trends, bar charts for top cost categories, and variance charts for actual-versus-plan comparisons.
Conclusions
The workbook provides a structured basis for examining IT spending across time, business functions, geographies, and cost categories. The availability of Actual, Forecast, and Plan fields in the main dataset supports budget tracking and variance analysis. The separate `Future Data` worksheet may also support forward-looking analysis, subject to confirming its schema and relationship to the main data.
No single cost category, region, or business area should be described as the largest spender until totals have been validated and compared. Likewise, negative values should not automatically be treated as errors; they may be legitimate accounting adjustments. The final project conclusion should report the largest verified cost drivers, material budget variances, changes over time, data-quality limitations, and practical recommendations based on the completed analysis.
Tools and Methods
The workbook is supplied in Microsoft Excel format. Analysis can be completed using Excel, Python (for example, pandas and matplotlib), or a business-intelligence tool. Document the exact tools, formulas, filters, and visualizations used in the final submission.
Suggested Final Deliverables
Cleaned dataset or documented data-quality checks
Summary tables for expenditure by time, business area, geography, and cost element
Actual-versus-plan and actual-versus-forecast variance analysis
Charts showing trends and major cost drivers
A concise findings section with evidence-based recommendations
How to Use
Open `IT Expenditure dataset.xlsx`.
Review the `Data` and `Future Data` worksheets and confirm their field definitions.
Validate the data before calculating totals or variances.
Perform the recommended aggregations and visualizations.
Replace the general conclusions above with specific, quantified findings from the completed analysis.
