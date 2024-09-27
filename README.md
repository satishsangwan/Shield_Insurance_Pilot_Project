![Dashboard](https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/images/Dashboad_Image.png)
# Shield Insurance Pilot Project - Power BI Dashboard

## Project Overview

**Domain:** Insurance  
**Function:** Sales  
**Company:** Shield Insurance

As a Data Analyst intern at AtliQ Technologies, I completed this pilot project for **Shield Insurance**, focusing on customer and revenue analysis. The goal of this project was to provide insights into customer growth, revenue trends, and policy analysis to support business decision-making. This project showcases my ability to translate business requirements into meaningful data visualizations using Power BI.

### Project Scope
The project required me to analyze key metrics such as:
- Total customers and revenue
- Daily revenue growth rate and customer growth rate
- Monthly changes in policies
- Segmentation of customers by age group and city
- Sales mode analysis

**Key Deliverables:**
- A dynamic, interactive Power BI dashboard with 5 pages:
  - **Home Page**: Overview of the dashboard with key insights
  - **General View**: Trends in customers and revenue, with a toggle between graphs
  - **Sales Mode Analysis**: Analysis of sales mode preferences and trends
  - **Age Group Analysis**: Revenue and customer segmentation based on age groups
  - **Top/Bottom Analysis**: Insight into the top-performing and least-performing categories

## Data Sources
The analysis was performed on data from **five CSV files** provided by Shield Insurance, including customer, date, policy, premium, and settlement data. Below is a summary of each file:

1. **dim_customer.csv**: Contains customer details like customer code, date of birth, and city.
2. **dim_date.csv**: Provides date-related data including daily, monthly, and week number information.
3. **dim_policies.csv**: Holds information about policies such as policy ID, base cover, and premium amount.
4. **fact_premiums.csv**: Contains premium data such as sales date, policy ID, and sales mode.
5. **fact_settlements.csv**: Data on policy settlements segmented by age.

## Data Model   
![Data Model](https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/images/Data%20Model.png)

## Key Features & Metrics
In this project, I identified 17 key features necessary for complete business analysis, which are given in the table below :

| Sr. No.| Features    | Comments    |Priority|
|--------|-------------|-------------|--------|
| 1|Show total customers, total revenue, daily revenue growth, daily customer growth as key metrics| To monitor all the crucial metrics|High|
| 2|Month over month change% on key metrics| Tracking the month-over-month change in policies on key metrics can offer valuable insights into a company's performance trends.|High|
| 3| Segment customers based on their age groups: 18-24, 25-30, 31-40, 41-50, 51-65, and 65+.| To categorise customers into different age group to better understand behavior and preferences.|High|
|4|Total revenue split by age group, city|To identify most profitable customer demographics and geographical areas|High|
|5|Total customers split by age group, city|To understand customer's locations and age groups, we can customize our products and marketing strategies.|High|
|6|Customers, daily customers growth trend by month|To understand customers growth trends over time and spot changes in customer behavior and adjust our marketing efforts accordingly|Low|
|7|Revenue, daily revenue growth trend by month|To track business's financial performance and growth trends over time and spot any changes or fluctuations in revenue.|Low|
|8|Create a switch between revenue trend graph and customer trend graph |Switching between revenue trend and customer trend graphs enhances the user experience by providing a more customized and efficient way to view the data.|Low|
|9| Filters on sale mode, age group, city, month, policy ID|Provides users with the ability to filter and sort data according to specific parameters, allowing for a more targeted and efficient analysis |High|
|10| Separate page for sales mode analysis|A dedicated page for sales mode analysis|High|
|11|Total customers split percentage by sales mode|Provides insights into which modes are most effective in attracting and retaining customers|High|
|12|Total revenue split percentage by sales mode|Providing insights into which modes are most effective in generating revenue for the business|High|
|13|Trend of sales mode over month|To understand the trend of sales mode over the month|Low|
|14|Separate page for age group analysis|A dedicated page for age group analysis|High|
|15|Age group vs expected settlement|To know what is the expected annual settlement|High|
|16|Age group vs sales mode|To understand what sales mode people prefer by age group|Low|
|17|Age group vs policy preference|To understand what policy people buy by age group|High|





## Project Workflow

1. **Feature List Creation**: Created a list of 17 key metrics essential for analyzing Shield Insurance's performance and tracking key business metrics. Click here to view [Feature List](https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/benchmark_feature_list.xlsx)
   
2. **Mockup Dashboard**: Developed a mockup dashboard that incorporated Shield Insurance’s feedback. This provided a clear layout for three pages: General View, Sales Mode Analysis, and Age Group Analysis. Click Here to view [Mockup Dashboard](https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/client_updated_mockup.pdf)

4. **Final Dashboard**: Delivered a comprehensive, interactive Power BI dashboard with 5 pages. The dashboard allows dynamic filtering based on factors like sales mode, city, month, and policy ID. It provides an easy-to-navigate user interface for exploring key metrics.

## Dashboard Pages Breakdown

You can view the live Shield Insurance Power BI dashboard by clicking the link below:
[View Shield Insurance Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODhmMjc0ZGMtNDBiMy00ZjdjLWE1ZTItNGI5N2VhNDdhYTFhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

### 1. **Home Page**  
   The Home Page serves as the landing page of the dashboard, providing easy navigation to various key sections, including:
- **General View**
- **Sales Mode Analysis**
- **Age Group Analysis**
- **Top/Bottom Analysis**

It also includes important information such as:
- Links to the **Info** and **Support** pages for further guidance.
- The **last data refresh date** and the **data coverage period**, ensuring that users are aware of the data's currency.

 <p align="center"> 
  <img src= "https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/images/Home_GIF.gif" alt="Home Page"/>  
  </p>   

### 2. **General View**  
   The General View offers a comprehensive overview of Shield Insurance's performance, highlighting key metrics such as:
- **Total Revenue**
- **Total Customers**
- **Daily Revenue Growth**
- **Daily Customer Growth**

Each metric is displayed using card visuals, which also include the previous month's values and the percentage change compared to the last month, allowing for quick comparisons. Additionally, this page presents:
- **Revenue and Customer Trends** over time using line charts.
- A **Month-over-Month (MoM) change table** showcasing critical metrics.
- A **bar chart** breaking down revenue and customer data by **city** and **age group**.
   
   <p align="center"> 
  <img src= "https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/images/General%20View_GIF.gif" alt="General View"/>  
  </p>   

### 3. **Sales Mode Analysis**  
The Sales Mode Analysis page is designed to provide insights into revenue and customer data segmented by **sales mode**. This includes an analysis of the following sales channels:
- **Offline-Agent**
- **Offline-Direct**
- **Online-App**
- **Online-Website**

The page features:
- A **trend analysis** of both customers and revenue over the months, segmented by sales mode.
- Visual representations of customer behavior and sales performance by different policy sales modes.

  <p align="center"> 
  <img src= "https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/images/Sales%20Mode_GIF.gif" alt="Sales Mode"/>  
  </p>  
  
### 4. **Age Group Analysis**  
The Age Group Analysis page focuses on the impact of different age groups on Shield Insurance's business. It includes:
- A **table visual** displaying the number of customers within each age group, segmented by **policy type** and **sales mode**.
- A **trend analysis** showing customer behavior over time for various age groups.
- A **bar chart** depicting the **expected policy settlements** based on age groups, which helps in understanding customer demographics and potential policy outcomes.

   <p align="center"> 
  <img src= "https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/images/Age%20Group_GIF.gif" alt="Age Group"/>  
  </p>

### 5. **Top/Bottom Analysis**  
The Top/Bottom Analysis page provides a detailed comparison of the top-performing and underperforming segments across multiple categories, such as:
- **City**
- **Age Group**
- **Sales Mode**
- **Policy ID**

This analysis allows the business to quickly identify which segments are contributing the most and least to the company's growth, facilitating data-driven decision-making and strategic focus.

   <p align="center"> 
  <img src= "https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/images/Top%20Bottom_GIF.gif" alt="Top Bottom"/>  
  </p>

## Key Learnings & Skills Demonstrated
- **Data Preparation**: Cleaned and transformed data from various sources to make it ready for analysis.
- **Data Visualization**: Created dynamic and interactive visualizations in Power BI, allowing users to toggle between graphs and filter data by sales mode, city, age group, and more.
- **Business Insights**: Delivered actionable insights to Shield Insurance, helping them monitor revenue, customer growth, and policy preferences over time.
- **Project Management**: Worked closely with Shield Insurance stakeholders to iteratively build a dashboard that meets their requirements and exceeds expectations.

## Tools & Technologies Used
- **Power BI**: Main tool for data visualization and dashboard creation.
- **Excel**: Used for feature listing and initial data analysis.

## Conclusion
This project helped Shield Insurance monitor key business metrics in an easy-to-navigate dashboard while showcasing my ability to handle end-to-end analytics projects. From data cleaning to visualization, I delivered a solution that provides deep insights into their customer and revenue trends.
