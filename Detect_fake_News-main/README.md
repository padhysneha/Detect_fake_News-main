Team Name- Codergirls
Team Members-Bhakti Panhale
             Sneha Padhy
             Arti Pail
Topic-Detecting Fake News(S-06)

# Detect_fake_News
Introduction:
  In today's generation, we cant trust all the news from social media. So we came up with this project of detecting fake news.
  We will ue Multinomial Naives Bayes Method
  
 Data:
    We are using news.csv file which has cleaned data (i.e news).We are using for classifying as REAL or Fake.
    
 Project Struture:
    We first import the libraries needed.
    Then import the text file in the form of csv.
    Then count the REAL and FAKE news and TOTAL RECORDS.
    We have plot a graph showing the Fake and REAL news.
    We have used wordcloud for showing the frequencies of words in the text file.
    Then we are splitting the data into train.
    Transforming data into feature vectors using tdifdvectorizer
    Counting Accuracy using PassiveAggressiveClassifier Algorithm
    Creating a pipeline that first creates list of words(removing stopwords) & then applies Multinomial Naive Bayes model
    Calculating accuracy score and Predicting the label for the test data
    
    
    
