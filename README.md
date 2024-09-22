# Walmart-Sales
I studied the sales data of one of the largest retailers in the world and figured out what factors influence its revenue. 

## Key features
The data contains the following columns:
Store: Store number
Date: Sales week start date
Weekly_Sales: Sales
Holiday_Flag: Mark on the presence or absence of a holiday
Temperature: Air temperature in the region
Fuel_Price: Fuel cost in the region
CPI: Consumer price index
Unemployment: Unemployment rate

## Clean the data first:
Data is sorted first by store number (ascending) and second by date (ascending)  
Date is in the format MM-DD-YYYY  
Weekly Sales is rounded to the nearest 2 decimal places  
Temperature is rounded to the nearest whole number  
Fuel Price is rounded to the nearest 2 decimal places  
CPI is rounded to the nearest 3 decimal places  
Unemployment is rounded to the nearest 3 decimal places  
Ensure that there is no missing data  

## Business Questions:
Which holidays affect weekly sales the most?
Which stores in the dataset have the lowest and highest unemployment rate? What factors do you think are impacting the unemployment rate?
Is there any correlation between CPI and Weekly Sales? How does the correlation differ when the Holiday Flag is 0 versus when the Holiday Flag is 1?
Why do you think Fuel Price is included in this dataset? What conclusions can be made about Fuel Price compared to any of the other fields?
