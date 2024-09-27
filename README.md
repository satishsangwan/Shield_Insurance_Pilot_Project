[Dashboard](https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/images/Dashboad_Image.png)
# Shield Insurance Pilot Project - Power BI Dashboard

## Project Overview
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
In this project, I identified 17 key features necessary for complete business analysis, such as:
- Total customers
- Total revenue
- Daily revenue growth rate
- Policy changes month-over-month
- Customer segmentation by city and age group
- Sales mode trend analysis

## Project Workflow

1. **Feature List Creation**: Created a list of 17 key metrics essential for analyzing Shield Insurance's performance and tracking key business metrics. Click here to view [Feature List]()
   
2. **Mockup Dashboard**: Developed a mockup dashboard that incorporated Shield Insurance’s feedback. This provided a clear layout for three pages: General View, Sales Mode Analysis, and Age Group Analysis. Click Here to view [Mockup Dashboard](https://github.com/satishsangwan/Shield_Insurance_Pilot_Project/blob/main/client_updated_mockup.pdf)

4. **Final Dashboard**: Delivered a comprehensive, interactive Power BI dashboard with 5 pages. The dashboard allows dynamic filtering based on factors like sales mode, city, month, and policy ID. It provides an easy-to-navigate user interface for exploring key metrics.

## Dashboard Pages Breakdown

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
- **SQL**: For extracting and transforming data where needed.

## Conclusion
This project helped Shield Insurance monitor key business metrics in an easy-to-navigate dashboard while showcasing my ability to handle end-to-end analytics projects. From data cleaning to visualization, I delivered a solution that provides deep insights into their customer and revenue trends.
