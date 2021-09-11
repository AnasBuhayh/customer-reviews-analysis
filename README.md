# Introduction

Online reviews are important for both seller and customer to evaluate a product. However, it is time-consuming to go through all product reviews to get valuable insights. This analysis will go through two methods that can be used to analyze customers' reviews. I used a Walmart reviews-scraper script to collect the reviews from Walmart.com. The script is available in my repo. This analysis will contain two methods. The first method is to collect reviews based on Term Frequency known as TF. This is used to get reviews that are more representative of the total reviews. The second method is to apply sentiment analysis for sentences based on Term Frequency - Inverse Document Frequency is known as TF-IDF to get a feel of what people feel about a specific feature.

The second part of the project research the possibility of indicating the star reviews based only on the adjectives used in the review.

# Analysis

Scraped customer reviews from a retail website and summarized reviews with frequency distribution using NLTK Library. Calculated TF-IDF to collect product features and run sentiment analysis using Scikit-Learn. Implemented XGBoost classifier to predict star reviews based on the adjectives used.

[Online Reviews Analysis (Part-1) - EDA + Sentiment analysis](https://github.com/AnasBuhayh/customer-reviews-analysis/blob/main/Online%20Reviews%20Analysis%20-%20NLP%20-%20(Part-1).ipynb)

[Online_Reviews_Analysis (Part-2) - Classification](https://github.com/AnasBuhayh/customer-reviews-analysis/blob/main/Online_Reviews_Analysis-NLP-(Part-2).ipynb)

# Conclusion

The project was successful in extracting the features of the product using TF-IDF. Measuring the accuracy of the sentiment analysis using TextBlob is a challenge without labeling the data. Implementing the XGBoost classifier to predict the star ratings using adjectives was not promising, with an accuracy of 72%. Modifying the parameters can help to increase the accuracy.
