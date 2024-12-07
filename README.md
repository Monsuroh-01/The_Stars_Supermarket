# The_Stars_Supermarket_Sales_Analysis
I explored this dataset for insights that will help the management of The Stars Supermarket make data-driven decisions and drive growth for the company using Excel. I cleaned the dataset and analyzed it using Pivot table, then created an interactive visualization for The management of the company.



<img width="570" alt="Sales Analysis report front page" src="https://github.com/user-attachments/assets/e5ee1c9b-7101-4f2e-993a-94d50e6b58b2">


## Introduction
This dataset contains information about sales transactions across various products including categories, customer demographics, and locations. I analyzed the data to uncover insights to help the management make informed decisions and drive growth. The examination includes data from the invoiceid, branch, city, customer type, gender, product line, unit price, quantity sold, tax(5%), total, date, tie, payment method, cost of goods sold, gross margin %, gross income, and rating tables. The dataset was imported to excel for detailed analysis.

**Data Source**: The Stars Supermarket is a hypothetical company, and, this dataset was provided by The Data Immersed Community for learning purpose only.

### Problem Statement
The objectives of this analysis are as follows.

- To determine the overall monthly sales performance across all branches.

- To identify high-performing branches and locations.

- To compare the quantity of products sold in correlation with the revenue generated.

- To identify customers’ payment preference across different cities.

- To analyze the influence of gender demographics on the products purchased across different cities.


### Tools: 
- Excel

### Data Preparation

- Data loading and inspection
- Checked for duplicates and missing values
- Data formatting and cleaning

### Skills and Concepts Demonstrated

**Excel functions**: Used various functions such as sum, count, and more for data analysis and manipulation.

**Data Analysis**: Used Excel features and functions for data analysis including conditional formatting such as using the "If"statement to replace "M" and "F"represented as gender with "Male"and "Female", and customer types represented by "0"and "1"with "Normal" and "Member".

```Excel
=IF([@[Customer type]]=0,"Normal","Member")

=IF([@Gender]="FM", "Female", "Male")
```


**Pivot tables and Charts**. Utilized pivot tables to summarize the dataset and used pivot charts to visualize data and communicate insights.

**Dashboard for visualization**: Developed an interactive dashboard to present key findings using advanced excel functions, pivot tables, conditional formatting, and pivot charts

### Key findings

- **Sales Trends**: January recorded the highest sales volume and revenue across all stores, with Naypyitaw generating the largest share of revenue.

  <img width="479" alt="Sales record" src="https://github.com/user-attachments/assets/6fda3749-57f1-4460-a80f-3e1006e13af7">


- **Top-Selling Product Line**: Food and beverages consistently led as the top-selling product line.

  <img width="250" alt="Sales by product line" src="https://github.com/user-attachments/assets/6f349d05-124c-4968-b390-17b8aaa63fcb">


- **Customer Experience**: Naypyitaw ranked highest in customer satisfaction scores, while Mandalay had the lowest.

  <img width="158" alt="Napyitaw average rating" src="https://github.com/user-attachments/assets/b0af1bc1-d38f-4874-a885-4057d39baae5">


- **Payment Preferences**: E-wallets were the most preferred payment method in Mandalay and Yangon, while cash dominated in Naypyitaw.

### Recommendations

- Implement targeted marketing campaigns and promotions around January to maximize sales

- Invest in marketing and store expansion in Naypyitaw to further capitalize on its revenue potential, and monitor performance regularly to identify factors contributing to high sales to further optimize them. 

- Expand the product variety within the food and beverages category to attract more customers, and use the popularity of food and beverages to cross-promote less popular product lines like health and beauty products. 

- Conduct customer satisfaction surveys in Mandalay to identify pain points, and provide staff training focused on enhancing customer service. 

- Expand digital payment options in Mandalay and Yangon, and introduce loyalty programs or discounts in Napytaw for using E-wallet and credit card options to encourage the adoption. Also, ensure that cash handling in Naypyitaw is efficient and secure to meet customer preferences. 



