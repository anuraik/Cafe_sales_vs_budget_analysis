# 📊 Sales Performance Analysis

📌 Project Overview

This project analyses sales performance across products, locations, payment methods and time periods.

The analysis also compares actual sales with budget targets to identify sales trends and areas of strong or weak performance.

🎯 Business Question

The analysis focuses on identifying the products that generate the highest sales and sales volume, comparing performance across different locations and payment methods, evaluating actual sales against the budget, and analysing how sales performance changes over time.


🛠️ Tools

- Excel
- SQL
- Data visualization

The analysis covers:

- Product performance
- Sales by location
- Payment method analysis
- Monthly sales trends
- Sales vs budget

🧹 Data Cleaning

The dataset was cheked and prepared before analysis.

The following steps were performed:
- Checked every column value
- Changed ERROR and NULL values to UNKNOWN in columns
- Created a new file with clean data
- Compined new file with budget file

📊 Analysis

The analysis examined:

Quantity of units per item sold annually

The analysis compared all sales and filtered out products, that were sold more than 3000 units. The most sold item was coffee, with 3284 units, followed by juice (3176), salad (3141), cake (3137), sandwich (3113) and smoothie (3015). Items, that sold less than that, were tea (2915), cookie (2913) and unknown with 2603 units.   

Annual sales by sum

Although coffe was the most sold item by unit, then the biggest annual sales amount comes from salad. Following are sandwich and smoothie. The product that sells the most may not be the product with the highest sales revenue.

Average sale by item compared to average sale

Compared average sale with average sale by item. The average sale was 8,93. Higher sales were salad, smoothie, sandwich, cake and juice. Lower sales came from cookie, tea and coffee. Salads sale was 15,17, which is almost double the amount of average sale. 

Sales by location

The analysis compared sales locations, which were unkonwn, in-store and takeaway. The biggest part of sales came from unknown. Since unknown contains also error and null values, it means that a lot of location information is missing or unspecified. Therefore, it should not be concluded that unknown is the best location. 

Annual sales by payment method

Compared different payment methods. The most popular one was Unknown, followed by cash. Digital wallet and credit card were very close. In here Unknown also has a big part of this data set and it should be handled as a data quality problem. 

Monthly sales

The analysis looked monthly sales. The biggest sales month was June (7031) and the lowest was February (6345,50). The difference beween months is there but its not very big. 

Sales vs budget

The analysis compared actual sales and budget. Out of 12 months, 8 months were above budget and 4 months were below budget. Those 4 months were July, August, September and December. Biggest differences come from July (-445) and September (-444). Best performing months were April (+422) and October (+383,5). 

🔍 Key Findings

- Coffee had the highest sales volume, with 3,284 units sold annually.
- Salad generated the highest annual sales revenue at 15,705, despite not having the highest sales volume.
- Salad also had the highest average sales per item (15.17), compared with the overall average of 8.93.
- Several products, including Salad, Sandwich and Smoothie, generated above-average sales per item.
- Actual monthly sales exceeded the budget in 8 out of 12 months.
- April had the largest positive variance from budget (+422), while July had the largest negative variance (-445).
- June recorded the highest monthly sales at 7,031, while February had the lowest at 6,345.50.
- A significant share of sales and payment records were categorized as "UNKNOWN", indicating a potential data quality issue that should be investigated before making location- or payment-based business decisions.

💡 Recommendations

- Consider promoting high-performing products such as Salad, Sandwich and Smoothie to support revenue growth.
- Investigate why July and September sales underperformed against the budget and identify potential seasonal or operational factors.
- Analyse the characteristics of high-performing products to understand what contributes to stronger average sales.
- Improve data collection and categorization for location and payment method fields to reduce the number of "UNKNOWN" records.
- Use monthly budget variance analysis to identify periods requiring additional sales or marketing activities.

📈 Visualizations

- Top annual sales
- Monthly sales
- Sales vs Budget
- Annual sales by quantity
- Annual sales by location
- Annual sales by payment method
- Top items by quantity (over 3000)
- Average sales per item vs total average sale



📁 Data Source


👩‍💻 Author
Anu Raik











