# Tyler's Data Engineer Portfolio
This portfolio includes 3 data engineer projects I did in the past. Please click the project title in blue to access the corresponding repository, where you can find more details.

# [RTD Data Transformation Project](https://github.com/huangyue1752/RTD-data-transformation)
Goal: Monthly, we receive a large data dump that includes historical sales in RTD category. This data dump is messy, unpivotable, and not aligned with our calendar. The goal is to transform the data into a clean dataset aligned with our calendar.
  
  In the Python transformation, we achieved a few things below
- The messy unpivotable data set is turned into a pivotable, clean data frame
- The fiscal calendar of the data providing company has been transformed to our calendar
- Malt products in Quebec are separated from the total RTD volume
- Data cleaning and generate a transformed dataset in csv

Result: this data transformation process has saved more than 10 hours per week; and it is used by the whole company; the human error has been minimized.
   ![](/image/christopher-robin-ebbinghaus-pgSkeh0yl8o-unsplash.jpeg)

# [Holman API Data Pipeline Project](https://github.com/huangyue1752/Holman-ETL-Project)
Goal: Monthly, we need to extract tables from multiple API end points and load the data to our systems. These tables provide vehicle information about our vehicle inventory, fuel consumption, odometer information etc. We automated the whole ETL(Extract, Tranform, and Load) process with Python, Docker, and Airflow.

  In the API extraction design, the code does a few things below
- Extract tables (Inventory table, Maintenance table, Fuel tables etc.) from each corresponding API endpoint.
- Iteration is utilized to retrieve the complete dataset from multiple pages in each API endpoint.
- Transform Json format to regular data frame. 
- Data cleaning.
- Generate the result files with creation time included in the file name and drop them to a designated folder
- Docker and Airflow are integreted in the ETL process for scheduling automation

result: this data extraction process has saved more than 10 hours monthly in the extration and transformation and is used by a team of 10 people.
   ![](/image/1.png)


   # [VHCS Forecasting Data loading Project]
Goal: quarterly, VHCS finance team generate more than 50 files saved in the sharepoint, which include the sales target in volume and dollars for the numerous product lines and divisions. These files need to be conbined to generate 1 data set which will be uploaded to Microsoft Azure Blob connected to Snowflake database which feeds our Profit and Loss dashboards. We need to create an exe. file, which combines all the files in Sharepoint and then upload to Azure blob container by just one click.

  In python uploading design , the code does a few things below
- Connect to the KDP Share Point folder that contains all the indivisual forecasting files.
- Combine all the individual files to generate a centrelized file.
- Upload the centralized file to the designated Azure Blob container after building the Azure connection
- genrating the exe application

result: this data uploading process has saved more than 20 hours for 5 people in the finance team each time when they upload forecastig. This benifites the whole VHCS of more than 100 people.
   ![](/image/1.png)

  
