# Superstore Sales Dashboard
An interactive Power BI dashboard analysing sales and profit performance for a US retail business. It’s based on the Superstore dataset, which has 9,994 orders from 2011 to 2014.

Tools

Power BI Desktop, Power Query, DAX

What I did
Cleaned the data in Power Query: converted day-month-year text dates using the correct locale, set the correct data types, removed unused columns (Row ID, Country) and created Year and Month columns.
Fixed duplicate loading so each figure is counted once.
Wrote a DAX measure for profit margin: Profit Margin = DIVIDE(SUM(Superstore[Profit]), SUM(Superstore[Sales]))
Built the dashboard with three KPI cards (total sales, total profit, profit margin), three charts (sales by region, profit by category, monthly sales trend) and slicers for Region and Year. Clicking any chart or slicer cross-filters the whole page.
Key insights
Total sales were $2.30M, with $286.40K profit and an overall margin of 12.5%.
West and East are the strongest regions for sales, and South is the weakest.
Technology and Office Supplies drive most of the profit, while Furniture contributes very little.
Sales are seasonal, rising sharply in September to December and peaking in November.
Skills shown

Data cleaning, data modelling, DAX, dashboard design, interactive filtering and turning data into business insights.

Files
Superstore_Dashboard.pbix: the Power BI file
Superstore_Dashboard.pdf: a PDF export
dashboard.png: a screenshot
Superstore.csv: the source data
