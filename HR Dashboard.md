HR Dashboard.pdf

The task aimed to present the overview of Human Resources data of X company, analyze demographics indicators👧👦 , present the employee structure 👨‍💻 , and visualize trends on employment/new hires 📈

The questions answered were about employee diversification in terms of gender/age/ethnicity/department, number of hired employees by gender between the study period, percentage of employees by current employment status, the salary distribution and variation range by department and more...

Approach steps after defining the questions:

1. Cleaning and setting each column uniform (Power Query)
2. Checking data anomalies (renaming columns, replacing values, removing errors etc), and deleting irrelevant/unused data (Power Query)
3. Setting correct data types (Power Query)
4. Creating the appropriate data model (denormalization): STAR schema EmployeeFactTable, junction/bridge tables for Many-Many relationships and dimensions. (Power Query)
5. Define cardinality and relationships
6. Creating necessary measures in DAX 
7. Choosing the correct visualization depending on each data type and question.
