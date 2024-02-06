# COVID-19 Data Analysis Project

## Project Overview
This project involves analyzing COVID-19 data to uncover insights related to infection rates, death rates, and vaccination progress worldwide. Using SQL, we explore various aspects of the pandemic, including the likelihood of dying after contracting the virus, the percentage of populations infected, and vaccination rates across different countries and continents.

## Data Sources
The analysis is based on data from two primary tables:
- `CovidDeaths`: Contains data on COVID-19 deaths, cases, and other related metrics.
- `CovidVaccinations`: Contains data on COVID-19 vaccination rates and progress.

Both tables are stored within the `covid_analysis` schema in our SQL database.

## Features
This project showcases the following SQL techniques and concepts:
- **Joins:** Used to combine rows from two or more tables based on a related column between them.
- **CTEs (Common Table Expressions):** Allow the creation of temporary result sets that can be referred to within a SELECT, INSERT, UPDATE, or DELETE statement.
- **Temp Tables:** Temporary tables store and process intermediate results by using them in the later stages of our SQL queries.
- **Window Functions:** Used for performing calculations across a set of table rows that are somehow related to the current row.
- **Aggregate Functions:** Used to compute a single result from a set of input values.
- **Creating Views:** Views are used to save a specific query so that it can be reused and referenced in future queries.
- **Converting Data Types:** Essential for calculations and ensuring compatibility between different columns.

## Queries
The SQL queries in this project cover a wide range of data manipulations and analyses, including but not limited to:
- Basic data filtering and ordering to prepare datasets for analysis.
- Calculating death percentages to assess the severity of the disease.
- Analyzing infection rates in relation to total population to understand the spread.
- Identifying countries with the highest infection and death rates.
- Comparing continental data to observe larger trends.
- Summarizing global COVID-19 cases and deaths.
- Examining vaccination rates and progress.

## How to Use
1. Ensure your SQL environment is set up and the `covid_analysis` schema is available.
2. Execute the provided SQL queries within your SQL tool of choice (e.g., MySQL Workbench, PostgreSQL pgAdmin, SQL Server Management Studio).
3. Adjust the queries according to your specific analysis needs or to explore different aspects of the data.

## Contributing
Contributions to this project are welcome! Whether it's enhancing the analysis, improving the SQL queries, or correcting data inaccuracies, feel free to fork the project and submit a pull request.

## License
This project is open-source and available under the [MIT License](LICENSE.txt).
