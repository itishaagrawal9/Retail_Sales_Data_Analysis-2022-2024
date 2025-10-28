# Exploratory Data Analysis for Retail Sector

# 1. Project Overview:
This project presents an Exploratory Data Analysis (EDA) of retail sales data for the years 2022–2024, using Python.
The goal is to uncover sales trends, identify regional and category-wise performance patterns, assess the impact of discounts and promotions, and highlight key business insights that can drive data-backed decisions for marketing and operations teams.

# 2. Business Problem:
The core challenge was to identify sales bottlenecks and inefficiencies across regions and categories. The findings were used to guide pricing, promotional, and operational strategies aimed at maximizing revenue while minimizing returns

# 3. Methodology
Exploratory Data Analysis (EDA) was performed using Python to diagnose performance issues. The raw retail sales data was first cleaned and sanitized before being analyzed.
The analysis tracked total and net sales across years, regions, and product categories, and specifically focused on the following areas:
•	Regions: North, South, East, West
•	Product Categories: Clothing, Home, Electronics, Beauty, etc.
•	Discount Ranges
•	Sales Channels: Online vs. Offline
•	Time Periods: Holidays, Weekends, and Seasonal Trends
•	Promotion impact on sales and returns
•	Category-level contribution and decline patterns
Category	Tools / Libraries
Programming	Python
Libraries	Pandas, NumPy, Matplotlib, Seaborn
Environment	Jupyter Notebook
Techniques	Data Cleaning, EDA, Visualization, Trend Analysis


# 4. Executive Summary & Key Insights:
Performance Highlights:
•	South and East regions are strategic focus areas, accounting for nearly 60% of total revenue.
•	South and East were the top-performing regions, showing consistent growth and strong contribution to revenue.
•	Clothing and Home were the top-performing categories, having high units sold with steady margins.
Areas of Concern:
•	Year-over-Year (YOY) revenue growth declined across all regions, suggesting potential market saturation or inefficiencies.
•	The West region was the lowest in sales across all years.
•	The Electronics category was a major contributor to returns and showed a declining sales trend. The highest return rate was in the Electronics category, warranting a product-level audit.
•	Electronics and Beauty were the major return contributors. Specific products, prod_039 and prod_005, showed high returns.
North Region Pricing Sensitivity:
•	The North region was highly responsive to high discounting (15–30%).
o	0% discount led to declining sales.
o	5–30% discount led to increasing sales.
•	Despite increased sales, the North region also had the highest return rate among all regions. Returns also rose in 2024.
•	Promotions were ultimately not effective in driving sustainable net sales in the North.

# 5. Results and Business Recommendation:
I recommend that the Marketing and Operations team implement a few adjustments that will lead to higher conversion from this region:
1.	Reallocate marketing efforts: Focus marketing efforts toward the South and East regions, as they are the primary revenue drivers
2.	Review North region strategy:
o	Maintain moderate discounting (5%–15%) to sustain volume.
o	Reduce promotion frequency in the North (and other low-performing regions) where discounts fail to improve net revenue.
3.	Conduct a deep dive into the Electronics segment for high-return Stock Keeping Units (SKUs), specifically prod_039 and prod_005. Reduce promotion frequency in low-performing regions where discounts fail to improve net revenue
4.	Address Product Quality/Fit Issues: Additionally, address quality/fit issues in the Electronics and Beauty segments
5.	Optimize return processes: Curb revenue leakage by considering post-sale surveys or implementing revised return policies
