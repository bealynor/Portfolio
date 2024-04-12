
# Portfolio
This repository comprises the necessary files for the Portfolio Yelp Analysis Task

The dataset (Yelp_Portfolio1_Input.csv
) can be accessed via the link provided at https://github.com/COMP2200-S1-2023/portfolio-part-1-dataset/releases/download/portfolio-dataset-p1/Yelp_Portfolio1_Input.csv

# Objective of the Project
The purpose of this repository is to provide graphical presentations and insightful analysis about consumer behaviors, business profiles, and geographic locations from the given Yelp Data. 


# Description of Variables 
* business_id_- A unique identifier for each business in the dataset
* business_categories - A list of categories associated with the business
* business_city - The city where the business is located.
* user_id - A unique identifier for each user who has written a review.
* text The text of the review.
* stars - The user's rating towards the business
* Useful - The number of times the review was voted as useful.
* date - The date the review was posted.

# Summary of Tasks

1. Import cvs file and neccessary functions such as pandas, seaborn, matplotlib, etc.
2. Remove missing values from the data inlcuding empty cells, #NAME?, #VALUE!.
3. Display Dataframe of cleaned data, and provide its length.
4. Create and display a random sample of 10 cities from the cleaned data, and provide its length.
5. Create descriptive statistics of the stars and unique business and user ids, and provide its length.
6. Plot suitable graphs to display correlation, statistical data, and distribution among variables.
7. Provide analysis to each graph and give a summary.


# Overall Findings

In general, majority of the businesses across the cities have high star ratings between 3-5 eventhough some cities have larger distribution in terms of number of users or customers. Customers are more likely to give high stars between 3-5 on any business regardless of the city or location. 

In terms of reviews, majority of the consumers like to provide reviews on restaurants and hotel/travel services. This means that consumers are more likely to place a review if it is about food or their hotel/Travel experiences. Furthermore, there is a positive relation between the number of reviews and the number of useful votes. The number of Useful votes will more likely increase as the number of reviews increases. Additionally, people are more likely to leave reviews if they have a positive experience with the business.


It is also interesting to note that the top city with the most number of businesses is Phoenix. The top business category with the most reviews is Mexican Restaurants. This is most probably because majority of residents in Arizona are Hispanic. 

Overall, this Yelp Analysis can provide several insights on how to understand consumer behaviors, sales performances, and economic conditions of cities. It can be used by marketers, business owners, policy makers to better understand market profiles and make informed decisions.





