# Data Cleaning and Geographically Locating High Churn Risks

In this project, I cleaned a data set involving customer churn using Python.
In the following code, I checked for and corrected outliers, duplicates, invalid data, and missing values.
To do so, I used: Isolation forest algorithm, python methods, boolean masks, and K-Nearest Neighbor imputation respectively.

([https://github.com/AlanCArmstrong/Data_Cleaning_and_Plotting_Locations/blob/main/Cleaning_Data_In_Python.txt])

After I cleaned the data, I filtered for churn risks above the elbow (0.1) and used matplotlib to create a bar graph of the ten highest
churn rates in each locational variables (state, county, city, etc.) The main findings are in the graphs below.

High Churn rate risks per state:  
([https://github.com/AlanCArmstrong/Data_Cleaning_and_Plotting_Locations/blob/main/State_Churn.png])

High Churn rate risks per timezone:  
([https://github.com/AlanCArmstrong/ML_Cleaning_and_Visualizing/blob/main/Average_Churn_per_Timezone.jpg)])

Unfortunately, the data revealed a somewhat obvious conclusion that the areas with the highest populations
have the highest expected churn. I also checked the average rates of churn but the highest churn rates mostly had an insignificant amount
of customers. However, this effort was not fruitless. This code can be repurposed as a predicter of amount of churn to inform expected
customer totals. Also, 

Future business analytics,
perhaps on the survey data, could be easily done to inform a recommendation that, if acted upon, will reduce churn rates.
