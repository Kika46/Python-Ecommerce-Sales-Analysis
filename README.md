🛍️ 2019 Sales Data Analysis (Python)
High-impact e-commerce sales analysis for 2019. This project showcases advanced Python (Pandas) for data wrangling, feature engineering, and time-series analysis to deliver actionable insights on peak sales trends, geographic performance, and product purchasing behavior.

🎯 Key Performance Indicators (KPIs)
The analysis of the merged annual sales data established the core metrics for 2019:

Metric	Result
Total Annual Revenue (2019)	$34.49 Million

Export to Sheets
📈 Time-Based & Geographic Insights
The project identified the optimal times and locations for the business:

Performance Area	Top Performer	Metric/Value	Business Insight
Best Month	December	$4.61 Million	Suggests a strong holiday/year-end spending rush requiring maximized inventory.
Best Time of Day	7:00 PM (19:00)	14,470 Units	The primary post-work shopping peak, ideal for targeted online advertising campaigns.
Best City	San Francisco	$8.26 Million	The highest-value geographic market, warrants focused expansion and resource allocation.

Export to Sheets
💻 Product Performance
The analysis provides clarity on which products drive the most revenue versus which drive the highest volume:

Rank	Product (by Revenue)	Revenue Generated
1	Macbook Pro Laptop	$8,037,600
2	iPhone	$4,794,300
3	ThinkPad Laptop	$4,129,960
Top by Quantity	AAA Batteries (4-pack)	31,017 Units

Export to Sheets
🛠️ Technical Workflow
Data Wrangling & Cleaning: Handled missing data, dropped invalid records, and ensured proper data type conversion for numerical and date fields.  
Feature Engineering: Calculated the Sales column, and derived temporal (Month, Hour) and geographic (City) features using string splitting for analytical grouping.
Core Analysis: Used Pandas groupby() functions to aggregate data and extract all key metrics across time, location, and product categories

Feature Engineering: Calculated the Sales column, and derived temporal (Month, Hour) and geographic (City) features using string splitting for analytical grouping.

Core Analysis: Used Pandas groupby() functions to aggregate data and extract all key metrics across time, location, and product categories.
