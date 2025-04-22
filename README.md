# DATA_ANALYST_TASK2
Power BI Sales Dashboard – FY17-18 vs FY18-19
This Power BI report provides a comprehensive overview of sales performance across different fiscal years, store locations, and products. The dashboard offers interactive visualizations for deeper insights into year-to-date (YTD), month-to-date (MTD), and historical sales trends.


📊 Key Visualizations
1. KPI Tiles
Total Sales: Overall sales across all timeframes.
YTD Sales / LY YTD Sales: Compare this year's sales with last year's.
MTD Sales / LY MTD Sales: Current month's performance compared with the same month in the previous year.

2. Total Sales | Month Wise
Bar chart showing monthly sales trends.
Helps identify peak and low-performing months.

3. Sales by Store Location
Table format showing:
Total Sales
YTD Sales vs. LY YTD Sales
YTD Growth % with conditional formatting (green for positive growth).

4. Store Distribution Map
Geographic visualization to show store performance globally.
Pins on map display total sales by store city.

5. Top 5 Products by Revenue
Bar chart comparing YTD Sales and LY YTD Sales by product.
Helps highlight high-performing products.

📁 Dataset
The dataset is structured into the following key tables:
products: Contains product information like category, cost, name, and price.
sales: Transaction-level data with date, product, store, and sales amount.
stores: Store metadata including name, city, and location.

🔍 Filters & Slicers
Dynamic filtering is available for:
Financial Year (FY 17-18 / FY 18-19)
Month-Year
Product Category
Product Name
Store Name / Location / City

💡 Insights & Storytelling
Growth Analysis: Identifies which stores and products are driving the most growth YoY.
Sales Trends: Monthly trendlines reveal seasonality and performance dips/spikes.
Geographic Spread: Understand which cities contribute the most to total revenue.
Product Revenue Split: Highlights top-performing products with side-by-side comparisons.

🚀 How to Use
Clone or download the repository.
Open the .pbix file in Power BI Desktop.
Refresh the data (if dataset is included or linked).
Use slicers to interact and uncover insights based on your analysis goals.

🛠 Tools Used
Power BI Desktop
DAX for calculated fields (YTD Growth %, Sales comparisons)
