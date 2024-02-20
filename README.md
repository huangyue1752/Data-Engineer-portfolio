# Tyler's Data Science/Data Engineer Portfolio
This portfolio includes 3 data engineer and data science projects I did in the past. Please click the project title in blue to access the corresponding repository, where you can find more details.

# [Multilinear Regression Integrated with Autoregression to Forecast Electricity Consumption in Quebec](https://github.com/huangyue1752/Multiple-Regression-Analysis-for-Electricity-Consumption)
Goal: This is a Multiple linear regression project to forecast the electricity consumption in Quebec that I have done 5 years ago. The final model is a multi-linear regression model integrated with Autoregression. You can find the Power Point in the Link above. 

The Power Point includes a few things
- Variable selection 
- Regression model building (Multilinear Regression integrated with Autoregression)
- Test(Heteroscedasticity and Normality)
- Future improvement (Since this project was done 5 years ago, I added my new points of view regarding future improvement)
![](/image/image.png)

# [RTD Data Transformation Project](https://github.com/huangyue1752/RTD-data-transformation)
Goal: Monthly, we receive a large data dump that include historical sales in RTD category. This data dump is messy, unpivotable, and not aligned with our calendar. The goal is to transform the data into a clean dataset aligned with our calendar.
  
  In the Python transformation, we achieved a few things below
- The messy unpivotable data set is turned into a pivotable, clean data frame
- The fiscal calendar of the data providing company has been transformed to our calendar
- Malt projects in Quebec are separated from the total RTD volume
- Data cleaning and generate a transformed dataset
   ![](/image/christopher-robin-ebbinghaus-pgSkeh0yl8o-unsplash.jpeg)

# [Holman API Data Pipeline Project](https://github.com/huangyue1752/Holman-ETL-Project)
Goal: Monthly, we need to extract tables from multiple API end points and load the data to our systems.These tables provide vehicle information about our vehicle inventory, fuel consumption, odometer information etc. We automated the whole ETL(Extract, Tranform, and Load) process with Python, Docker, and Airflow.

  In the API extraction design, the code does a few things below
- Extract tables (Inventory table, Maintenance table, Fuel tables etc.) from each corresponding API endpoint.
- Iteration is utilized to retrieve the complete dataset from multiple paged in each API endpoint.
- Transform Json format to data frame. 
- Data cleaning.
- Generate the result files with creation time included in the file name and drop them to a designated folder
   ![](/image/1.png)
