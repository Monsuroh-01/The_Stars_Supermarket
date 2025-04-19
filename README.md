# The_Stars_Supermarket_Sales_Analysis
I explored this dataset for insights that will help the management of The Stars Supermarket make data-driven decisions and drive growth for the company using Excel. I cleaned the dataset and analyzed it using Pivot table, then created an interactive visualization for The management of the company.

## Introduction
This dataset contains information about sales transactions across various products including categories, customer demographics, and locations. I analyzed the data to uncover insights to help the management make informed decisions and drive growth. The examination includes data from the invoiceid, branch, city, customer type, gender, product line, unit price, quantity sold, tax(5%), total, date, time, payment method, cost of goods sold, gross margin %, gross income, and rating tables. The dataset was imported to excel for detailed analysis.

<img width="252" alt="product line" src="https://github.com/user-attachments/assets/9863ca46-add8-48cd-b198-98c15140680c" />

**Data Source**: The Stars Supermarket is a hypothetical company, and this dataset was provided by The Data Immersed Community for learning purpose only.

### Problem Statement
The objectives of this analysis are as follows.

- To determine the overall monthly sales performance across all branches.

- To identify high-performing branches and locations.

- To compare the quantity of products sold in correlation with the revenue generated.

- To identify customers’ payment preference across different cities.

- To identify the busiest day and time. 

- To analyze the financial capacity of the supermarket. 

- To analyze the influence of gender demographics on the products purchased across different cities.


### Tools Used: 
- Excel

### Data Preparation

- Data loading and inspection
- Checked for duplicates and missing values
- Data formatting and cleaning

### Skills and Concepts Demonstrated

**Excel functions**: Used various functions such as sum, count, and more for data analysis and manipulation.

**Data Analysis**: 
Used Excel features and functions for data analysis including conditional formatting such as: 

using the "If"statement to replace "M" and "F"represented as gender with "Male"and "Female", and customer types represented by "0"and "1"with "Normal" and "Member".

```Excel
=IF([@[Customer type]]=0,"Normal","Member")

=IF([@Gender]="FM", "Female", "Male")
```

The HOUR(TIMEVALUE) function to derive the active hours

```Excel
= HOUR(TIMEVALUE([@[Purchase time]]))
```

The Hour, Text, and Time functions to convert the 24 hours’ time to 12 hours

```Excel
=HOUR([@Time])& "_"& TEXT(TIME(HOUR([@Time]), 0, 0), "h AM/PM")
```

**Pivot tables and Charts**. Utilized pivot tables to summarize the dataset and used pivot charts to visualize data and communicate insights.

**Dashboard for visualization**: Developed an interactive dashboard to present key findings using advanced excel functions, pivot tables, conditional formatting, and pivot charts

<img width="759" alt="The Stars Supermarket Indepth analysis" src="https://github.com/user-attachments/assets/5635707c-13b7-4515-a478-3eec4b032beb" />


### Key findings
**Sales Analysis:**

- Month with the highest sales: January

- Peak purchase time was 7pm

- The busiest day was Saturday 

- Most Preferred Payment: Ewallet

**Customers Analysis:**

- Member Customers contributed more to sales

- Top Gender: Female

- Top Selling Branch: Napyitaw

- Top Rated Store: Napyitaw

**Financial Analysis:** 

- Gross income = total amount of tax paid, which means no actual profit was made in Q1 of 2019.

**Product Analysis:**

- Most Sold Product Line (in quantity): Fashion

### Recommendations

-The company should focus on repricing their products as their gross income is the exact amount of tax they pay. So, there’s a need for products repricing strategy for the profitability and sustainability of the business. 

- Implement targeted marketing campaigns and promotions around January to maximize sales

- Invest in marketing and store expansion in Naypyitaw to further capitalize on its revenue potential and monitor performance regularly to identify factors contributing to high sales and further optimize them. 

- Expand the product variety within the fashion accessories category to attract more customers and use the popularity of the fashion product line to cross-promote less popular product lines like health and beauty products. 

- Conduct customer satisfaction surveys in Mandalay to identify pain points and provide staff training focused on enhancing customer service. 

- Expand digital payment options in Mandalay and Yangon and introduce loyalty programs or discounts in Napytaw for using E-wallet and credit card options to encourage the adoption. Also, ensure that cash handling in Naypyitaw is efficient and secure to meet customer preferences. 


- Ensure the availability of more staff on Saturdays and evening around 7pm daily for better customer service and ease of attending to customers. 




