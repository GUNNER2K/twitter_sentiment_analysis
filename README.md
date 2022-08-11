# twitter_sentiment_analysis

This project uses the techniques applied in NLP to perform a sentimental analysis on the tweets dataset taken from kaggle . it contains 1.6 million tweets consisting of both positive and negative tweets . Class label 4 indicates positive tweet , whereas class label 0 indicates negative tweet . Simple logistic regression is used as our predicting model.


<h3>preprocessing::</h3>

- Removal of stopwords
- removal of @ , https etc
- Stemming using porter stemmer 
- lemmatizing using WordNet Lemmatizer

<h3> Some insights into the code </h3>

- WordCloud Generator for negative tweets 

  ![image](https://user-images.githubusercontent.com/95174361/184203538-72368a69-e36d-4b81-a879-ffd878c89e13.png)

- WordCloud Generator for positive tweets 

  ![image](https://user-images.githubusercontent.com/95174361/184204550-b0cab953-3aa8-426b-8fc2-b1e6d64b0d4b.png)

- Frequency chart of positive hashtags 

  ![image](https://user-images.githubusercontent.com/95174361/184205384-a332cf99-4792-46ca-ab27-e42506ca0d71.png)

- Frequency chart of positive hashtags 

  ![image](https://user-images.githubusercontent.com/95174361/184205769-91cae795-53a4-4cba-9fe3-eea653224627.png)
