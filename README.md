# Energy_Consumption_Prediction

# Overview

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Saving Energy can help human live, using energy more efficiently can be the fastest, most cost-effective ways to save money, reduce green house gas emissions, create jobs, and meet growing energy demand [1]. And saving energy consumption can help us to reduces air and water pollution and conserves natural resources, which can help us to get healthier living environment [2]. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Therefore in this case I make a prediction using time series algorithm in deep learning to predict energy consumption to help saving the energy consumption and get healthier live.

# Dataset

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The dataset can be download on this link [kaggle - Energy Consumption](https://www.kaggle.com/code/ranja7/energy-consumption-forecast-baseline-models/data)

![image](https://user-images.githubusercontent.com/91602612/200095686-e1d9c7eb-2493-43ff-aebc-9c74205bf90c.png)

# Exploratory Data Analysis

**1. Check Dataset**

![image](https://user-images.githubusercontent.com/91602612/200095771-37368a64-1786-4d73-9916-284c11db0999.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this dataset there are few missing values, I found that there are 948 missing values in column **Site ID** and 948 missing values in column **Energy Consumption (kwh)**. 

![image](https://user-images.githubusercontent.com/91602612/200095824-4ab9fc47-51a2-4864-acc5-82860a8f908b.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Therefore I remove all misisng values and got 8316 rows and 3 columns.

**2. Plot timestamp and value**

![image](https://user-images.githubusercontent.com/91602612/200096721-a9482293-aff6-4b40-b795-54117653374c.png)

# Data Preprocessing

**1. Normalize value**

**2. Create window dataset**

# Build Model

# References

[1] https://www.epa.gov/statelocalenergy/local-energy-efficiency-benefits-and-opportunities

[2] https://www.aceee.org/sites/default/files/ee-improves-environment.pdf
