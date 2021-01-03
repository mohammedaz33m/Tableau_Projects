![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/readme_img/atliq-technologies-pvt-ltd-alkapuri-vadodara-software-companies-5wj1ejfd5r.jpg)

# Defining AIMS Grid:
The Aim's Grid is a central tool for planning any venture and a must-have for project leaders. This tool helps you to collect the most important information about your project on one simple page and hence lay the foundation for a successful implementation.

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/readme_img/aims%20grid.png)


![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/readme_img/Aims_grid%20(1).png)

# Purpose: 
### To understand the sales insigts that are not visible before for the sales team to help in decision making & automate the task in to reduce the time spent in gathering data.

# Stakeholders:
- Sales Team
- IT team 
- Marketing team
- Customer service team
- Data Analytics team

# End Results:
### A fullly functioning dynamic dashboard for sales team.

# Success Criteria:
- Dashboard uncovering the sales order insights
- Take better decisions & prove 10% cost saving.
- Sales Analyst stop gathering data & save 20% of business time & reinvest elsewhere to add value.

# Data Extraction Method

> Generally it is not a good idea to directly connect with the main data source as any unwanted glitch may stop the entire process & thus affecting end users. Since the OLTP:Online transaction processing system is recording the data on a daily basis thus, any problem with the extraction would have a direct adversal affect on the data source. Also, the data analysis task is a compute intense & running analysis on the main source will slow down the system & thus affecting the end business & customer satisfaction.

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/readme_img/NormalETL.png)

> Therefore we go for another way by creating a copy of the master data in a data warehouse: OLAP-Online Analytical processing system. Any affect to the data warehouse soes not affect the main data source thereby not affecting the business.

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/readme_img/SafeETL.png)

# Data Connection & dashboard Creation in Tableau

1. The data is connected to the tableau via an option beside the main menu

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/Tableau-mysql.JPG)

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/mysql%20details%20for%20tableau.JPG)

2. When connected this is the view.

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/Tableau%20upon%20connection.JPG)

3.Drag the tale 1

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/drag%20table1.JPG)

4. Check Update automatically

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/update%20automatically.JPG)

5. Drag table 2 & establish a relationship

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/establish%20a%20relationship.JPG)

6. drag table 3 & establish a relationship 

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/drag%20table3.JPG)

7. Similarly connect all the tables & establish a relationship based on the matchine columns & filter the data

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/data%20filter.JPG)

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/filter%20-1.JPG)

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/filter%20US%20%26%20NY.JPG)

8. When connected it looks like this: STAR SCHEMA

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/Sales%20Insights-Atliq/images/when%20all%20connected%20-star%20schema.JPG)

9. CREATE DASHBOARDS USING TABLEAU

- DASHBOARD 1

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/readme_img/Dashboard%201.jpg)

- DASHBOARD 2

![screenshot](https://github.com/mohammedaz33m/Tableau_Projects/blob/main/SQL%20Projects/readme_img/Dashboard%202.jpg)

# FOR INTERACTIVE DASHBOARD
## VISIT: https://public.tableau.com/profile/mohammed.azeem78#!/vizhome/sales-insights-AtliQ/AtliQSalesInsight
















