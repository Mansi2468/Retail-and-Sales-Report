Retail Sales Data Analysis

Academic project: analysis of a public retail sales dataset using Excel and Power BI.

Dashboard

[Dashboard overview](screenshots/dashboard-overview.png)
[Dashboard with a filter applied](screenshots/dashboard-filtered.png)

Dataset
- Source: Kaggle "Retail Sales Dataset" by Mohammad Talib
  (https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)
- 1,000 transactions, January 2023 to January 2024
- Columns: Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, Total Amount
- The dataset describes a fictional retail business. It has no region column.

Tools
Microsoft Excel (pivot tables, VLOOKUP, SUMIFS), Power BI

What I did
1. Checked and cleaned the data in Excel.
2. Built pivot tables and used VLOOKUP and SUMIFS to summarize revenue by product category and month.
3. Built an interactive Power BI dashboard showing sales trends and category performance.

Questions I looked at
- Which product categories bring in the most revenue?
- How does revenue change from month to month?
- Which price levels and customer age groups matter most?

Findings
- Total revenue was 456,000 across 1,000 orders (average order: 456).
- The three categories are close: Electronics 156,905 (34.4%), Clothing 155,580 (34.1%), Beauty 143,515 (31.5%).
- Monthly revenue peaked in May 2023 (53,150) and was lowest in September 2023 (23,620). There is no steady up or down trend.
- Items priced at 300 or 500 were about 40% of orders but about 88% of revenue.
- Average order was about 500 for ages 18-25 and about 412 for ages 56+.

Suggestions
- Test a small promotion on Beauty (lowest share) before moving stock between categories.
- Keep the 300 and 500 price items well stocked, since they drive most revenue.
- Check what happened in May and September before planning ahead.

Limitations
One year of data, 1,000 orders, a fictional business, and no region or cost data. These results are a learning exercise, not business advice.

Files
- `excel/`: Excel workbook with pivot tables, SUMIFS and VLOOKUP
- `powerbi/`: Power BI dashboard file (.pbix)
- `screenshots/`: dashboard images

What I learned
How to clean a dataset, summarize it with pivot tables and formulas, and present the results in an interactive dashboard.
