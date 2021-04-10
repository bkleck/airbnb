# airbnb
- Notebooks for Price Regression and Sentiment Analysis
- With much of the AirBnB app targeted at consumers, our model intends to create another dimension to help AirBnB hosts instead.
- These models will help owners price their accomodations appropriately with the given features and sieve out negative reviews to notify owers for improvement.

## Notebooks
1) airbnb_EDA_final
In this notebook, we explored the various datasets provided to sieve out meaningful insights on our data. We also reduced the number of variables to our models by removing noisy features and outliers.

2) airbnb_prediction
We performed regression to predict prices based on our selected features using various machine learning models on several platforms: sk-learn, Pycaret and Keras. 

3) word2vec_sentiment
In this section, we made use of word2vec algorithm to convert our words into spatial vectors and performed unsupervised clustering into positive and negative groupings. Afterwards, tf-idf weights were given to the words within sentences and these are aggregated on a sentence level to give their overall sentiment.

4) bert_sentiment
We also labelled 2,000 data points for the highly popularized BERT model for supervised sentiment classification. BERT gave amazing results on just little training.

