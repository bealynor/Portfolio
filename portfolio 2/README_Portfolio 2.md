

# Portfolio
This repository comprises the necessary files for the Portfolio 2 task.

# Objective of the Project
The purpose of this repository is to provide reliable data analysis about Yelp businesses by cleaning, and filtering unnecessary data through the use of different data processing techniques. It also aims to provide insightful analysis about correlations between businesses and user ratings.  


# Description of Variables 
* business_categories - A list of categories associated with the business
* business_city - The city where the business is located.
* business_id_- A unique identifier for each business in the dataset
* date - The date the review was posted.
* stars - The user's rating towards the business
* text The text of the review.
* Useful - The number of times the review was voted as useful.
* user_id - A unique identifier for each user who has written a review.


# Summary of Tasks

1. Import cvs file and neccessary functions such as pandas, seaborn, matplotlib, etc.
2. Filter unique busines categories with star ratings and provide boxplot
3. Clean the business category column by using only the last word per row of business category
4. Display the clean Business Category column with its frequency
5. Clean business categories by removing frequency less than 200 and output its length
6. Remove >=6 values in Useful column from the clean sample data and provide a boxplot of original data vs. data with values removed
7. Print its lenght
8. Remove active users who rate businesses more than 30 times (>30) and print its length
9. Provide boxplot of User Rating Count with outliers vs User Rating Count < 30)
10.Output its length
11. Provide a linear regression model between useful column as the input variable and the stars column as the output variable
12. Provide a linear regression model between Business Review count and star ratings
13. Output and analyse the correlations between Business Review Count and Useful variables with stars 



# Overall Findings

There is a negligible/insignificant correlation between Business Review Count and Useful Variables with Stars. This means that there is no linear  relationship between any of two variables. If a business review count increases, it does not mean that stars or useful votes will also increase, or the other way around.







