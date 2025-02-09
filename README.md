# disneyland-sentimentAnalysis


1. Problem

The Walt Disney Company’s theme parks are extremely popular around the world. So much so, that the company now boasts six resorts in total, four of which are found outside the United States - in Tokyo, Hong Kong, Beijing and Paris. While it’s logical to imagine Disney exporting their signature “magical” quality to each of their park ventures, it also makes sense that each of these locations must present unique challenges in terms of logistics, culture and finances. While some of these can be gauged internally, a metric of customer satisfaction is of paramount importance to truly measure the quality offered by each park experience.
What separates a negative review from a positive one? And what are the customers’ shared sentiments within each the positive and negative reviews? After we establish some answers to these questions we can begin pinpointing the areas in which the parks are performing well, and in which there’s still room for improvement. Ideally, we would also be able to identify unique customer sentiments for each park.
I want to exploit the tools offered by Python and its packages to both analyze review text (word frequency, time series, etc.) and subsequently create a predictive tool to classify incoming reviews as either positive or negative (i.e. using a Logistic Regression model and a RNN based on TensorFlow/Keras).

2. Dataset

To address the above issue, I’ve decided to make use of Arush Chillar’s Disneyland Reviews dataset from Kaggle, which collects 42,000 reviews from 3 Disney resorts - California, Paris and Hong Kong. It contains the following features:
- A unique review ID
- A numerical rating from 1 - 5
- The year and month of the submission
- Reviewer location
- Review text

The most significant features for our purposes will be both the body of the text and the respective rating assigned by the customer. Additionally, I’ll make use of both the date and user location features to gain further insights into customer satisfaction across time and regions. 


[DisneylandSentimentAnalysis.pdf](https://github.com/user-attachments/files/18723102/DisneylandSentimentAnalysis.pdf)


