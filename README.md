**About Walmart**

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.


**Business Problem**
The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specifically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? 

**Concept Used**
- Central Limit Theorem
- Confidence Interval
- Hypothesis Testing
- Exploratory Data Analysis
- Outlier Treatment
- Null value Treatment

**Approach**
- Detected Null values & Outliers (using boxplot, “describe” method by checking the difference between mean and median, isnull etc.)
- Did some data exploration steps like:
- Tracked the amount spent per transaction of all the 50 million female customers, and all the 50 million male customers, calculate the average, and conclude the results.
- Used the sample average to find out an interval within which the population average will lie. Calculate the interval within which the average spending of 50 million male and female customers may lie.
- Used the Central limit theorem to compute the interval.
- Concluded the results and check if the confidence intervals of average male and female spends are overlapping or not overlapping. 
- For Age, I created bins based on life stages: 0-17, 18-25, 26-35, 36-50, 51+ years.


**Column Profiling**
- User_ID:	User ID
- Product_ID:	Product ID
- Gender:	Sex of User
- Age:	Age in bins
- Occupation:	Occupation(Masked)
- City_Category:	Category of the City (A,B,C)
- StayInCurrentCityYears:	Number of years stay in current city
- Marital_Status:	Marital Status
- ProductCategory:	Product Category (Masked)
- Purchase:	Purchase Amount
