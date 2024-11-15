# Azure-Anomaly-Detector
Project creates an Anomaly detector to figure out abnormal points in a time series data using Microsoft Azure API

**Motivation behind the Project:** Motivation: Anomaly detectors can help customers to easily detect any abnormal activities in their real time business use cases which can notify the users if detected any while monitoring, this service does not require any pre-trained ML model to be developed by users to use it. 

**Implementation Process:**
In this project we will obtain US stock performance data from Alpha Vantage 
API. Alpha Vantage API is supported minutely, hourly, daily, weekly and monthly stock time series data call. Azure anomaly detector API also supports yearly time series calls as well.  
 
**STEP-1**: Obtain and Prepare stock data from alpha vantage API to feed azure anomaly detector API. 
1.	Installing alpha vantage package 
2.	Dropping unnecessary dataframes  
3.	Finally loading into a .json file stockdatafromav.json
   
**STEP-2:** Create a stock anomaly detector resource in the azure portal  

**STEP-3:** Load the json file to Azure Anomaly Detector API to Analyze Stock Performance Data. 
 
●	To start sending requests to the Anomaly Detector API, we should paste the subscription key received after creating the Anomaly Detector resource.  ' 
●	Use the endpoint received from overview section of the Anomaly Detector resource we created 

●	Defining API Function call 

●	Define API response handling function 

Step-4: Load prepared stock performance data from Alpha Vantage API import (Using prep_stock_data_from_alpha_vantage.ipynb file)

**Refer to Report.pdf for detailed explaination.**

