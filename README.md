# Data Cleaning and Geographically Locating High Churn Risks

In this project, I cleaned a data set involving customer churn using Python.
In the following code, I checked for and corrected outliers, duplicates, invalid data, and missing values.
To do so, I used: Isolation forest algorithm, python methods, boolean masks, and K-Nearest Neighbor imputation respectively.

([https://github.com/AlanCArmstrong/ML_Cleaning_and_Visualizing/blob/main/Python_Code.txt])

After I cleaned the data, I filtered for customers who had not yet churned and used matplotlib to create a bar graph of the fifteen highest
churn rates in each locational variables (state, county, city, etc.) The most relevant findings are in the graphs below.

High Churn rate risks per state:  
([https://github.com/AlanCArmstrong/ML_Cleaning_and_Visualizing/blob/main/Average_Churn_per_State.png])

High Churn rate risks per timezone:  
([https://github.com/AlanCArmstrong/ML_Cleaning_and_Visualizing/blob/main/Average_Churn_per_Timezone.jpg)])

The bar charts revealed no particular bias towards any region, except a very high average churn rate in alaska and indiana regions, as well as a few states. However, this code's function
as a predicter of churn can be used to further analyze factors other than location. This analysis can also be used find what low churn states are doing right. 
Finally, as time goes on, with frequent updating, this model can be transformed into a time series model and provide more helpful insights. 
