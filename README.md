# Budget-and-Financials-of-MBTA
MBTA receives revenue in different ways like passes, tickets for the subway, bus and commuter rail mode of transportation. They need to pay salaries to the employees and have maintenance costs like fuel and electricity, which happens to be most of their financial giving. Analyzing the budget and financials of the Massachusetts Bay Transportation Authority (MBTA). The project files includes detailed sections on the project's introduction, data modeling, data model implementation using MySQL and NoSQL, and Python database access for data visualization. It also offers a conclusion summarizing the MBTA's revenue streams and expenditures, with a particular focus on the revenue from subway services

## Project Overview

**Introduction**

This project cover the background of the Massachusetts Bay Transportation Authority (MBTA), its significance in public transportation, and the importance of financial and operational data analysis in improving its services. It would set the stage for the report by outlining the objectives, which include examining MBTA's revenue streams and expenditure, and optimizing its operations through sophisticated data management strategies.It aims to enhance budget allocation and operational efficiencies through data management and analytics.

**Approach**

The approach for analyzing the Massachusetts Bay Transportation Authority's (MBTA) budget and financial operations combines conceptual data modeling and practical implementation. It starts with constructing a conceptual ER model, detailing entities like Expense, Salary, and Maintenance, along with their relationships. The approach progresses by mapping these entities to a relational database schema, which is then implemented in MySQL. A parallel NoSQL model is developed in MongoDB to handle unstructured data. The approach is comprehensive, integrating database management systems with Python for data access and visualization, thereby facilitating a multifaceted analysis of MBTA's financial data.

**Usage of Tools And Framework**

In the project, Python was used to interface with both MySQL and MongoDB databases for data access and visualization. MySQL was utilized for structured data queries, while MongoDB managed unstructured data. Python's libraries facilitated the execution of SQL and NoSQL queries and the subsequent analysis of the MBTA's financial data. Data visualization scripts in Python provided clear representations of the insights derived from the data, illustrating trends and patterns in MBTA's operational expenditures and revenue streams. This integrative use of Python with MySQL and MongoDB underpinned the project's analytical capabilities.

**Queries Overview**

Queries used to analyze and manage data for the MBTA, these include selecting department details based on conditions, aggregating bill amounts, joining tables to get employee details who started two years ago, joining vehicle details with bus licenses, and selecting fuel energy records based on average unit usage. A correlated subquery is used to find salaries above the average, and a query checks for the existence of scanner IDs in transactions. MongoDB queries match employees in a department, sort employees by birth date, and join bus details with vehicles, limiting the results. 

**Conclusion and Futureworks**

Subway systems are identified as important sources of income, with operational costs emphasized as crucial factors in budgetary planning. The integration of predictive analytics can be used to facilitate financial planning and the implementation of machine learning to optimize operational processes.The approaches can be utilized in other public transportation systems to enhance financial and operational management. Additionally, they can serve as a blueprint for other sectors that want advanced data analysis.
