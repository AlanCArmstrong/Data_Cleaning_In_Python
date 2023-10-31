# Data Cleaning and Geographically Locating High Churn Risks

In this project, I cleaned a data set involving customer churn using Python.
In the following code, I checked for and corrected outliers, duplicates, invalid data, and missing values.
To do so, I used: Isolation forest algorithm, python methods, boolean masks, and K-Nearest Neighbor imputation respectively.

([https://github.com/AlanCArmstrong/Data_Cleaning_and_Plotting_Locations/blob/main/Cleaning_Data_In_Python.txt])

After I cleaned the data, I filtered for high churn risks and used matplotlib to create a bar graph of the ten highest
churn rates in each locational variables (state, county, city, etc.) The main findings are in the graphs below.

High Churn rate risks per state:  
([https://github.com/AlanCArmstrong/Data_Cleaning_and_Plotting_Locations/blob/main/State_Churn.png])

High Churn rate risks per timezone:  
([https://github.com/AlanCArmstrong/Data_Cleaning_and_Plotting_Locations/blob/main/Timezone_Churn.png])

I concluded that the customers in the midwest have the highest chance of churn. Future business analytics,
perhaps on the survey data, could be easily done to inform a recommendation to start reducing churn rates.
