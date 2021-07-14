# Team Fear & Comfort

Project 2 Bootcamp (Team 9). 

# Team Members

- Derrick Claye
- Yourik Hacoupian
- Sheldon Larmond
- Alice Lin

# Fear and Comfort Index
Creating a fear and comfort index using sentiment analysis and covid stats. 
 

# Research Question

Can a Fear and Comfort Index be used to predict future movements of the stock market?

**Assumptions/Defaults:** Best performing supervised learning algorithm is based on the *accuracy score*. 

# Datasets Used

- Yahoo Finance 
- Twitter 
- Google trend search 

# Supervised Learning Notebook

* This notebook runs **three** different **supervised learning algorithms** (*Random Forest, Gradient Boost, and KNeighbor*) and will output the correponding classification report, confusion matrix, ROC curve, and the feature importance plot. 

## Dataset Feild Descriptions

**HST:** Host Hotels & Resorts, Inc. is an S&P 500 company and is the largest lodging real estate investment trust and one of the largest owners of luxury and upper-upscale hotels. 

**XTN:** The S&P Transportation Select Industry Index (the “Index”) represents the transportation segment of the S&P Total Market Index (“S&P TMI”).

**Interest Score:** Google search trends on COVID

**Sentiment:** Twiter sentiment based on usage of the "COVID" word for the day. REesults are obtained by applying VADER sentiment analysis to 1000 tweats per day.

**Total_cases:** Total COVID cases since inception. 

**New_cases:** Number of new cases reported for the day.

**Total_deaths:** Total deaths since inception. 

**New_deaths:** Number of new deaths reported for the day. 

**S&P 500 Daily Movement:** This is the daily percentchange of the S&P index. 

## External Library

We use the lightgbm framework to perform the gradiant boosting classification. You may install it using the following command:

```!pip install lightgbm```

We also used snscrape to obtain tweets.  