# Covid Data Analysis
## This project focuses on the analysis of COVID-19 data, leveraging SQL to explore key metrics, trends, and insights. The dataset includes COVID-19 cases, deaths, and vaccination data from various countries and continents, offering a comprehensive view of the pandemic's impact globally and regionally.
## Dataset Used ->
 <a href="https://github.com/AlexTheAnalyst/Por...">Covid Deaths</a>
 <a href="https://github.com/AlexTheAnalyst/Por...">Covid Vaccinations</a>

## Key Objectives 
 * Cleaned COVID-19 data using Excel for consistency and accuracy.
 * Explored infection and death trends globally and in India using SQL.
 * Analyzed infection and death rates relative to population.
 * Identified countries and continents with the highest impact.
 * Assessed global vaccination progress using window functions.
 * Created temporary tables and views for streamlined analysis and visualization

## Key SQL Techniques Used:
•	Basic Select Queries: To retrieve and explore the raw data, including total cases, deaths, and vaccination statistics.
•	Aggregations and Grouping: To calculate the highest infection rates, death counts, and total new cases per continent and country.
•	Window Functions: Used SUM() with PARTITION BY to calculate cumulative values like the total number of people vaccinated.
•	Temporary Tables: Employed temporary tables (#PercentPopulationVaccinated) to store intermediate data for further analysis.
•	SQL Views: Created a view (PercentPopulationVaccinate) for easy access to vaccination data across different countries and continents.
•	Filtering and Sorting: Applied WHERE and ORDER BY clauses to focus on specific locations and sort the results by relevant metrics.

## Dashboard
![Dashboard 1](https://github.com/user-attachments/assets/1af3c94a-3784-4ad7-b9cd-1b29ae513a10)




