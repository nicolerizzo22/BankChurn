# Bank Churn Analysis 💰

### You’ve just been hired as a Data Scientist for the Bank of Dataland, the national bank in the country where data analysis is the most popular pastime.  

### The product team at the bank has noticed an uptick in customer churn & a decline in growth and they want to find new ways to reduce churn & appeal to new customers. 

### You’ve been asked to prepare and explore a set of customer data that will be used for 2 Machine Learning projects: Churn Prediction and Customer Segmentation. 

**Objectives:**
1.	Join and QA the data
2.	Clean the data
3.	Explore feature relationships with customer churn
4.	Prepare the data for modeling

**OBJECTIVE #1: JOIN AND QA THE DATA**
- Import/open both tables in the “Bank_Churn_Messy.xlsx” file
-	Use left join to join ‘Account_Info’ to ‘Customer_Info’ using the ‘CustomerID’ column
-	Check for and remove duplicate rows and columns

**OBJECTIVE #2: CLEAN THE DATA** (*By fixing inconsistencies in labeling, handling erroneous values & fixing currency fields*)
-	Check the data types for each column and make any necessary fixes
-	Replace missing values in categorical columns with ‘MISSING’, and missing values in the numeric columns with the median value
-	Profile the numeric columns in the data, if there are any extreme or non-sensical values, impute them with the median of the column
-	Combine any variations in country names in the ‘Geography’ column to a single value per country


**OBJECTIVE #3: EXPLORE THE DATA (EDA)**
-	Build a bar chart displaying the count of churners (exited=1 meaning they left our bank) vs. non-churners (exited=0 meaning they still have an account with our bank)
-	Explore the categorical variables vs. the target and look at the percentage of churners by “geography” and “gender”
-	Build box plots for each numeric field, broken out by churners vs. non-churners


Thank you for taking the time to look at this project! 🫶
