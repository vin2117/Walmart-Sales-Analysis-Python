 # <span style="color:#4CAF50">🏪 **Walmart Sales Data Analysis Using Python Libraries**</span>

## <span style="color:#3F51B5">📊 **About This Project**</span>
Dive into the world of retail analytics with this comprehensive **Walmart Sales Data Analysis** project. Our objective is to **uncover high-performing branches**, **identify best-selling products**, and **analyze customer behavior** to optimize sales strategies. This project utilizes data sourced from the **Kaggle Walmart Sales Forecasting Competition**.

---

## <span style="color:#FF5722">🎯 **Project Goals**</span>
- **Understand the Impact** of various factors on sales across different branches.
- **Enhance Decision-Making** by providing insights that drive better sales strategies.

---

## <span style="color:#673AB7">📁 **About the Data**</span>
The dataset includes sales transactions from three Walmart branches located in **Mandalay**, **Yangon**, and **Naypyitaw**. This dataset comprises **17 columns** and **1000 rows** and contains **no null values**.

| **Column Name**       | **Description**                                 |    
|-----------------------|-------------------------------------------------|
| `invoice_id`          | Invoice of the sales made                       |        
| `branch`              | Branch at which sales were made                 | 
| `city`                | The location of the branch                      | 
| `customer_type`       | The type of the customer                        | 
| `gender`              | Gender of the customer making the purchase      | 
| `product_line`        | Product line of the product sold                | 
| `unit_price`          | The price of each product                       | 
| `quantity`            | The amount of the product sold                  | 
| `VAT`                 | The amount of tax on the purchase               | 
| `total`               | The total cost of the purchase                  |
| `date`                | The date on which the purchase was made         | 
| `time`                | The time at which the purchase was made         |             
| `payment`             | The total amount paid                           |       
| `cogs`                | Cost Of Goods Sold                              |      
| `gross_margin_pct`    | Gross margin percentage                         |
| `gross_income`       | Gross Income                                    |
| `rating`             | Customer Rating                                 | 

---

## <span style="color:#009688">🔍 **Analysis Overview**</span>
1. **Product Analysis**: Explore insights into various product lines, identify top performers, and pinpoint improvement areas.
   
2. **Sales Analysis**: Analyze sales trends to evaluate the effectiveness of sales strategies and identify necessary adjustments.
   
3. **Customer Analysis**: Segment customers to understand purchasing behavior and profitability per segment.

---

## <span style="color:#FFC107">🚀 **Approach and Methodology**</span>
### 1. **Data Wrangling**
- **Initial Examination**: Identified and addressed any potential data quality issues.
- **Database Creation**: Established a robust database schema with **NOT NULL** constraints to maintain data integrity.

### 2. **Feature Engineering**
- **Time of Day**: Introduced a `time_of_day` column to categorize sales into Morning, Afternoon, or Evening.
- **Day of Week**: Added a `day_name` column to analyze weekday sales trends.
- **Month**: Created a `month_name` column to evaluate monthly sales performance.

### 3. **Exploratory Data Analysis (EDA)**
- Conducted EDA to address key business questions, uncover patterns, and derive actionable insights.

---

## <span style="color:#F44336">❓ **Business Questions to Answer**</span>
### **Generic Questions**
- How many distinct cities are present in the dataset?
- In which city is each branch located?

### **Product Analysis**
- How many distinct product lines are there in the dataset?
- What is the most common payment method?
- What is the most selling product line?
- What is the total revenue by month?
- Which month recorded the highest Cost of Goods Sold (COGS)?
- Which product line generated the highest revenue?
- Which city has the highest revenue?
- Which product line incurred the highest VAT?
- Retrieve each product line and add a column `product_category`, indicating 'Good' or 'Bad' based on whether its sales are above average.
- Which branch sold more products than the average?
- What is the most common product line by gender?
- What is the average rating of each product line?

### **Sales Analysis**
- Number of sales made in each time of day per weekday.
- Identify the customer type that generates the highest revenue.
- Which city has the largest VAT (Value Added Tax)?
- Which customer type pays the most VAT?

### **Customer Analysis**
- How many unique customer types does the data have?
- How many unique payment methods does the data have?
- Which is the most common customer type?
- Which customer type buys the most?
- What is the gender of most of the customers?
- What is the gender distribution per branch?
- Which time of the day do customers give most ratings?
- Which time of the day do customers give most ratings per branch?
- Which day of the week has the best avg ratings?
- Which day of the week has the best average ratings per branch?
---

## <span style="color:#3F51B5">📈 **Visualizations Used**</span>
- **Pie Charts**: To visualize the distribution of categorical data.
- **Bar Charts**: For comparing sales across branches and product lines.
- **Subplots**: To provide a comprehensive view of multiple related analyses.

---

## <span style="color:#009688">🌟 **Conclusion**</span>
This project demonstrates the application of data analysis techniques using Python libraries such as **Pandas**, **NumPy**, and **Matplotlib** to extract valuable insights from Walmart's sales data. The findings offer a foundation for informed decision-making and strategic planning to drive sales performance.

---
