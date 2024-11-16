# Data Engineer Portfolio
Name: Yue Huang  
Email: huangyue1752@gmail.com  
Tel: +15144300566

Welcome to my data engineering portfolio, where I showcase my expertise in designing and implementing efficient data pipelines to extract, transform, and load data, thus enabling streamlined data-driven decision-making processes. Please click the project title to check the code available in repository.

# [Data Engineer Project: Real-Time Shopify Data ETL with Kafka, Azure Event Hub & Databricks](https://github.com/huangyue1752/DAB_test2)
## Objective:
Developed an ETL pipeline to stream and process real-time Shopify order data using Kafka, Azure Event Hub, Databricks, and various cloud technologies for scalable data processing and transformation.

## Technical Highlights:
- Built a Python function to extract real-time Shopify order data via GCP Pub/Sub and Kafka, and synchronized it with Azure Event Hub.
- Deployed Azure Unity Catalog and Key Vault for enhanced data security and governance.
- Developed Databricks notebooks using PySpark for real-time ingestion from Event Hub, implementing checkpointing for data reliability across Bronze, Silver, and Golden transformation layers.
- Integrated dimensional data via Fivetran, and implemented Slowly Changing Dimension (SCD) Type 2 for data versioning.
- Used DBT for data transformation, building views and tables for reporting and dashboards.
- Ensured code quality with unit tests and data linting using Ruff.
- Established CI/CD pipelines with GitHub Actions for automated deployments.

## Technologies:
- Azure, Databricks, Fivetran, DBT, Kafka, GCP Pub/Sub, Python, CI/CD (GitHub Actions), SCD Type 2, Python, SQL, Eventhub
  
---

# [Real-Time Data Sync from Wikimedia API to MySQL using Kafka](https://github.com/huangyue1752/kafka_wikimedia_project)
## Objective:
Developed a real-time data streaming solution to fetch data from the Wikimedia API, process it with Kafka, and forward it to MySQL for further use, enabling efficient data storage and processing.

## Technical Highlights:
- Built a multi-module Spring Boot application with Maven, integrating Apache Kafka for real-time data streaming and processing.
- Implemented a Kafka producer to stream data from the Wikimedia API into a Kafka topic, and a Kafka consumer to forward data to Azure Event Hub.
- Utilized the EventSource library for processing real-time data from Wikimedia and Jackson for efficient JSON parsing.
- Configured MySQL within the Spring Boot application to persist data consumed by Kafka, using Spring Data JPAfor efficient data storage.
- Conducted end-to-end testing of the entire pipeline to ensure reliable data flow from Wikimedia to Event Hub and MySQL.

## Technologies:
- Java, Spring Boot, Apache Kafka, Azure Event Hub, MySQL, EventSource, Jackson
  
---

# [Full Stack ETL Project](https://github.com/huangyue1752/Full-Stack-ETL)
## Objective:
Extract Covid data from multiple Rapid API endpoints, transform and combine the data in python, load the data to SQL server via odbc connection in Python, and finally connect SQL server with Power BI to feed the dashboard

## Technical Highlights:
- Extracting data from RapidAPI; .ENV was used to store secret information such as URL and API key; TRY function was utilized so we can easily identify HTTP error and connection error.
- Data transformation in python to generate a centralized table.
- Importing the centralized table to SQL server for a storage purpose; authentication setting; coding to avoid duplicate when inserting the datsaset into SQL server database.
- Creating a view in SQL server on the centralized table and connecting that view with Power BI(Data folding).

## Technologies:
- Python, SQL Server, Eventhub
  
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

## Technologies:
- Python, Apache Airflow

By leveraging Python, automation tools like Airflow and Docker, and a focus on efficiency and accuracy, these projects demonstrate my ability to tackle complex data engineering challenges and drive impactful outcomes for organizations. I look forward to discussing how I can contribute to your data engineering initiatives.
