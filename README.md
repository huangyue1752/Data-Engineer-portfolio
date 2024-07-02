# Tyler's Data Engineer Portfolio

Welcome to my data engineering portfolio, where I showcase my expertise in designing and implementing efficient data pipelines to extract, transform, and load data, thus enabling streamlined data-driven decision-making processes. Please click the project title to check the code available in repository.

# [RTD Data Transformation Project](https://github.com/huangyue1752/RTD-data-transformation)
## Objective:
The goal of this project was to streamline the transformation of a messy, unpivotable data dump of historical sales in the RTD category into a clean dataset aligned with our calendar.

## Technical Highlights:
- Leveraged Python to pivot the data into a clean, analyzable format.
- Transformed the fiscal calendar to align with our company's calendar system.
- Implemented data cleaning techniques to enhance data quality.
- Developed automated processes to generate transformed datasets in CSV format.

## Impact:
- Reduced weekly data transformation time by over 10 hours.
- Enhanced data accuracy, minimizing human errors.
- Widely adopted across the organization, benefiting all teams relying on RTD sales data.

---

# [Holman API Data Pipeline Project](https://github.com/huangyue1752/Holman-ETL-Project)
## Objective:
This project aimed to automate the extraction, transformation, and loading (ETL) process of vehicle-related data from multiple API endpoints into our systems.

## Technical Highlights:
- Utilized Python, Docker, and Airflow for seamless ETL automation.
- Extracted various tables including inventory, maintenance, and fuel data from API endpoints.
- Implemented iterative techniques to retrieve complete datasets from paginated API responses.
- Converted JSON data into structured data frames for analysis.
- Integrated Docker and Airflow for scheduling and orchestration of ETL tasks.

## Impact:
- Reduced monthly extraction and transformation time by over 10 hours.
- Empowered a team of 10 members with timely and accurate data access.
- Improved operational efficiency and data reliability in vehicle-related analytics.

---

# [Full Stack ETL Project](https://github.com/huangyue1752/Full-Stack-ETL)
## Objective:
Extracting multiple Covid datasources from Rapid API endpoints, transform and combine the data in python, load the data to SQL server via odbc connection in Python, and finally connect SQL server with Power BI to feed the dashboard

## Technical Highlights:
- Extracting data from RapidAPI; .env was used to store secret information such as URL and API key; try function was utilized so we can easily identify HTTP error and connection error.
- Data transformation in python to generate a centralized table.
- Importing the centralized table to SQL server for a storage purpose; Authentication setting; coding to avoid duplicate when inserting the datsaset into SQL server database.
- Created a view in SQL server on the centralized table and connected that view with Power BI(Data folding).

## Impact:
- Saved over 20 hours per ETL cycle if done manually.
- Streamlined ETL processes.


By leveraging Python, automation tools like Airflow and Docker, and a focus on efficiency and accuracy, these projects demonstrate my ability to tackle complex data engineering challenges and drive impactful outcomes for organizations. I look forward to discussing how I can contribute to your data engineering initiatives.
