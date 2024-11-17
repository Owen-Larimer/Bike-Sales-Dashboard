### Project Overview

The ultimate goal of this project was to glean insights into what kinds of people are buying bicycles. Learning what factors, such as age, gender, education etc. affect bike sales can aid firms in deciding to what groups they should prioritize marketing.

### Data Sources

Layoffs Data: The main data source used for this project was the dataset found in the "Excel_bike_sales_data.xlsx" file. It contains uncleaned information about bike sales. Each row is a single customer visit with columns regarding that customer's attributes and whether they purchased a bike. There are well over 1000 rows.

### Tools

- Excel - Loaded Dataset; Cleaned and Analyzed
 - Pivot Tables - Backbone of Interactable Dashboard

### Data Cleaning/Preparation Phase

In cleaning, we performed the following in excel:
1. Removed all duplicates.
2. Detailed columns using Find and Replace.
3. Fixed format issues with data types
4. Created an age bracket column using a nested if statement **(=IF(L2>54, "Old", IF(L2>=31,"Middle Age",IF(L2<31, "Adolescent","Invalid"))))**

### Table/Visualization Phase

During this phase, we used the data and pivot table feature of excel to create a number of charts and graphs to visualize each customer attribute and its effect on sales. Filters were applied to each visualization individually to allow the final dashboard to be interacted with.

![image](https://github.com/user-attachments/assets/2165f3be-754e-43de-bfec-3365d8e43097)

### Final Dashboard

![image](https://github.com/user-attachments/assets/d04ebd56-ec06-4f4d-86dd-66cb70655488)

### Findings
In exploring some of the dashboard's filters, we can discover that:
1. Men with only partial high school education are most likely to buy a bike if they are customers.
2. Commute distance is a great predictor of whether someone will buy a bike.
3. Customers in Europe are much more likely to buy bikes.
4. Marital Status only has significant change in bike sales proportion for men.

### From Here
My main goal for this project was to work in excel and get more used to pivot tables and filters for future projects. It is an incredibly good way of visualizing what goes into sales of a product, and as such, this kind of dashboard could be made for any number of industries that deal with sales. This type of project could be expanded with even more rows with even more attributes if such a dataset exists for that particular product.
