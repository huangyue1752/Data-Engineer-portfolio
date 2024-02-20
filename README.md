# Tyler's portfolio
This is my portfolio that includes 3 data engineer and data science project I did in the past. Please click the project title to access the corresponding repository, where you can find more details.

# [Multilinear Regression Integrated with Autoregression to Forecast Electricity Consumption in Quebec](https://github.com/huangyue1752/Multiple-Regression-Analysis-for-Electricity-Consumption)
This is a Multiple linear regression project to forecast the electricity consumption in Quebec that I have done 5 years ago. The final model is a multi-linear regression model integrated with Autoregression. You can find the Power Point in the Link above. 
The Power Point includes a few things
1) Variable selection 
2) Regression model building (Multilinear Regression integrated with Autoregression)
3) Test(Heteroscedasticity and Normality)
4) Future improvement (Since this project was done 5 years ago, I added my new points of view regarding future improvement)


# [RTD data transformation project](https://github.com/huangyue1752/RTD-data-transformation)
- Goal: Monthly, we receive a large data dump that include historical sales in RTD category. This data dump is messy, unpivotable, and not aligned with our calendar. The goal is to transform the data into a clean dataset aligned with our calendar.
  In the Python transformation, we achieved a few things below
1) The messy unpivotable data set is turned into a pivotable, clean data frame
2) The fiscal calendar of the data providing company has been transformed to our calendar
3) Malt projects in Quebec are separated from the total RTD volume
4) Data cleaning and generate a transformed dataset



# [Holman API data pipeline project](https://github.com/huangyue1752/Holman-ETL-Project)
- Monthly, we need to extract tables from multiple API end points and load the data to our systems.These tables provide vehicle information about our vehicle inventory, fuel consumption, odometer information etc. We automated the whole ETL(Extract, Tranform, and Load) process with Python, Docker, and Airflow.
  In the API extraction design, the code does a few things below
1) Extract tables (Inventory table, Maintenance table, Fuel tables etc.) from each corresponding API endpoint.
2) Iteration is utilized to retrieve the complete dataset from multiple paged in each API endpoint.
3) Transform Json format to data frame. 
4) Data cleaning.
5) Generate the result files with creation time included in the file name and drop them to a designated folder
