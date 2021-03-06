## Fear and Comfort Index

Inspired by the Fear & Greed index, the Fear and Comfort index was created to measure the public's general feeling about Covid. The index was created using covid sentiment analysis and other covid related data.
 

### Research Question

Can a Fear and Comfort Index be used to predict future movements of the stock market?

**Assumptions/Defaults:** Best performing supervised learning algorithm is based on the *accuracy score*. 

### Datasets Used

- Yahoo Finance 
- Twitter 
- Google trend search 
- Kaggle Covid World Dataset (https://www.kaggle.com/hussainaliarif/largest-covid19-world-dataset)

### Supervised Learning Notebook

This notebook runs **three** different **supervised learning algorithms** (*Random Forest, Gradient Boost, and KNeighbor*) and will output the correponding classification report, confusion matrix, ROC curve, and the feature importance plot. 

### Unsupervised Learning Notebook

K-Means and Gaussian Mixture Models to cluster the data. Theoretically, each clusters will represent a general feeling - ranging from from comfortable to fearful.

### Dataset Feild Descriptions

**HST:** Host Hotels & Resorts, Inc. is an S&P 500 company and is the largest lodging real estate investment trust and one of the largest owners of luxury and upper-upscale hotels. 

**XTN:** The S&P Transportation Select Industry Index (the “Index”) represents the transportation segment of the S&P Total Market Index (“S&P TMI”).

**Interest Score:** Google search trends on COVID

**Sentiment:** Twiter sentiment based on usage of the "COVID" word for the day. Reesults are obtained by applying VADER sentiment analysis to 1000 tweets per day.

**Total_cases:** Total COVID cases since inception. 

**New_cases:** Number of new cases reported for the day.

**Total_deaths:** Total deaths since inception. 

**New_deaths:** Number of new deaths reported for the day. 

**S&P 500 Daily Movement:** This is the daily percentchange of the S&P index. 

### External Library

The lightgbm framework was used to perform the gradiant boosting classification. You may install it using the following command:

```!pip install lightgbm```

snscrape was used to obtain tweets.  

```!pip install snscrape```
