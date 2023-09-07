Project Information

Title: Data Analysis, Visualization and Report of staff_salary_silver.parquet Data Using Databricks and Power BI Tools

Summary: 
 - Carry out data analysis and prepare visualization of staff_salary_silver data that is stored as a table in delta format in Databricks Delta Warehouse. The 
   insights deduced from the analysis and report will be used to ascertain the factors that can contribute to salary growth withing the context of 
   the information (table dimensional fields) provided in the table  

Data File Details:
 - staff_salary_silver.parquet of a fictitious company contains 6,572 records/rows and 9 fields/columns stored in four (4) partitions (files), based on Education_Level column categories:
 - Field definitions
   - Id: Unique identifier (primary key) for each record (staff)
   - Firstname: The firstname of each staff
   - Lastname: The lastname of each staff
   - Age: The age of each staff
   - Gender: The sex of each staff  
   - Education_Level: The educational qualification of each staff
   - Year of Experience: The number of years of experience by each staff
   - Salary: The fixed regular payment, typically paid on a monthly basis to each staff. This is the target field
   - Age_Group: The age category each staff's age belongs
 - Data Source: Databricks Delta Warehouse

Data Cleaning Requirements: None (The data is good to go for analytics and reporting purposes)

Methodology: 
 - Load the data (staff_salary_silver.parquet) into Databricks notebook that is attached to a spark cluster
 - Analyse the data and save various analysis output tables, each in a single partition (delta format) to the 
   driver node's delta warehouse for power BI reporting
 - Connect Power BI to the Databricks notebook and build a Report (Graphs and Charts) that presents 
   the results of the analysis carried out on the data
 - Publish the Report

Tech Stack:
 - Databricks (Community Edition)
 - Power BI

Languages/Runtimes
 - Apache Spark 3.3.2


 