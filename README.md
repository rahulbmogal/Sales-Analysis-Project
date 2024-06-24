# Adventure Works Sales Analysis Report
![add tect](https://github.com/rahulbmogal/Sales-Analysis-Project/blob/main/Images/Screenshot%202024-06-05%20000222.png)
## 1. Introduction
The Adventure Works Sales Analysis project aims to provide insights into the sales performance of the Adventure Works company. The analysis includes data import, data modeling, and the creation of a comprehensive report with various visualizations.

## 2. Data Import
In this project, data was imported from multiple sources to ensure a comprehensive analysis of the sales data. The data sources included:

### Sales Data: 
Imported from a CSV file containing sales transactions.
### Product Data: 
Imported from an Excel file with product details.
### Customer Data: 
Imported from a SQL database with customer information.

The data import process involved connecting to these data sources and loading the necessary tables into Power BI.

## 3. Data Modeling
Once the data was imported, the next step was to create a data model that defines the relationships between different tables. The key components of the data model include:
![add tect](https://github.com/rahulbmogal/Sales-Analysis-Project/blob/main/Images/Data%20Modell.png?raw=true)

### Tables:

### Sales:
Contains sales transaction details.
### Products: 
Contains information about products sold.
### Customers: 
Contains customer information.

### Relationships:

A relationship was established between the Sales table and the Products table using the ProductID field.
A relationship was established between the Sales table and the Customers table using the CustomerID field.
These relationships were configured as many-to-one, with the Sales table on the many side and the Products and Customers tables on the one side. This setup enables effective querying and reporting across these tables.

## 4. Report Creation
The final step was to create a report that visualizes the insights derived from the data. The report includes multiple pages, each focusing on different aspects of sales performance. Key visualizations include:

### Sales Overview:


A bar chart showing total sales by product category.
A line chart displaying monthly sales trends.
A card visualization summarizing total sales, total customers, and average sales per transaction.

### Product Analysis:
![add tect](https://github.com/rahulbmogal/Sales-Analysis-Project/blob/main/Images/Screenshot%202024-06-05%20000634.png?raw=true)

A table listing top-selling products with their sales figures.
A pie chart showing the distribution of sales by product category.
A bar chart comparing sales of different products.

### Customer Insights:
![add tect](https://github.com/rahulbmogal/Sales-Analysis-Project/blob/main/Images/Screenshot%202024-06-05%20000305.png?raw=true)

Trend Analysis:
A line chart showing sales trends over the past year.
A column chart comparing monthly sales across different years.
A scatter plot analyzing the relationship between sales and customer demographics.

## 5. Conclusion
The Adventure Works Sales Analysis report provides a comprehensive view of the company's sales performance. By integrating data from multiple sources, establishing a robust data model, and creating insightful visualizations, this project offers valuable insights that can help the company make informed business decisions. Future enhancements could include more advanced analytics, such as predictive modeling and customer segmentation, to further enhance the insights provided by the report.
