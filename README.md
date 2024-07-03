 ![alt text](https://wp-content.remazing.eu/wp-content/uploads/Reviews_Blogpost.jpg)
# Sentiment-Analysis-on-Amazon-Reviews-Using-Natural-Language-Processing-and-Deep-Learning
In this project, we used Natural Language Processing & Deep Learning models to Classify Amazon Reviews as either positive or negative. 

Reviews serve as the lifeblood of every business offering invaluable insights into customer satisfaction, preference and areas of improvement. Therefore these reviews are paramount for businesses seeking to thrive in competetive markets in today's digital space where consumers wield unprecedented influence through online platforms, understanding & interpreting them.

### Overview

Online reviews have become a significant source of customer feedback for businesses. Amazon, being one of the largest online marketplaces, generates an enormous volume of customer reviews daily. These reviews provide valuable insights into customer satisfaction, preferences, and areas needing improvement. However, the sheer volume makes manual analysis impractical.

### Objective

This project aims to design and implement a sentiment analysis system using Natural Language Processing (NLP) and Deep Learning models to classify Amazon reviews as either positive or negative. The goal is to develop a robust model that can accurately interpret the sentiment expressed in the reviews, thus providing actionable insights for businesses to enhance their products and services.

### Approach

### •	Data Preparation

The project begins with cleaning and preprocessing the review data. This includes text cleaning to remove punctuation and special characters, tokenization to split text into words, normalization to convert text to lowercase and perform stemming or lemmatization, and padding/truncation to standardize text sequence lengths.

### •	Exploratory Data Analysis (EDA)

Visualizations and statistical analyses are conducted to understand the distribution of sentiments over time, across brands, and product categories. This helps in identifying trends and patterns in customer feedback.

### •	Feature Engineering

The textual data is transformed into numerical form using techniques like TF-IDF and Count Vectorization. Additionally, word embeddings such as Word2Vec and FastText are employed to capture semantic relationships between words. Bigrams and trigrams are also extracted to understand common word pairings.

### •	Model Building 

Two deep learning models, a Simple RNN and an LSTM, are built to predict the sentiment of the reviews.

The LSTM Model, test accuracy is 0.902 which indicates a good performance to this model. 

The Simple RNN model is at 0.865 accuracy which is lower than the LSTM model performance.

### •	Model Evaluation

The models are evaluated using accuracy scores and ROC curves to ensure they accurately classify the sentiment of the reviews.

SimpleRNN Model with an AUC of 0.91, the SimpleRNN model is performing much better than the LSTM model in distinguishing between the classes. It has a high true positive rate and a low false positive rate across various thresholds.

LSTM Model: With an AUC of 0.53 is only marginally better than random guessing. This indicates that the LSTM model is not very effective for this particular task or dataset.

Hyperparameter tuning is performed to optimize the models for better performance.

The Model tuning for simple RNN Accuracy score is 0.8694 which has no huge difference from the model before tuning which was 0.8658.

The score is slightly higher than our objective of achieving 0.85 accurracy score. The model is therefore is satisfactory.

### Results

**Customer feedback**: The overall feedback is positive. This is shown by most ratings being 4 or 5. 
 
**Product preference**: From the analysis, customers prefer these products; Fire Tablets, Tablets, and Computers & Tablets.

**Trend Analysis**: From the temporal Analysis of ratings there isn't a significant trend in average ratings over time. Periodic spikes or dips may indicate specific product launches, updates, or marketing campaigns. 

**User Experience**: Reviews with the most helpful votes are an indication of positive customer experience. This is pivotal in influencing potential customers. 
  

### Conclusion
**Customer feedback**: The overall feedback is positive.
It's therefore, essential to continue monitoring and encouraging positive customer experiences. This can be achieved through maintaining product quality, enhancing customer service, and soliciting feedback from satisfied customers to bolster positive reviews.

**Product preference**: We recommend investing in the most preferred product categories by expanding product lines, improving features based on customer feedback, and maintaining competitive pricing to sustain positive customer sentiment.

**Trend Analysis**: Periodic spikes or dips may indicate specific product launches, updates, or marketing campaigns. 
Consider correlating these fluctuations with internal events to identify factors influencing customer sentiment and adjust strategies accordingly.

**User Experience**: We recommend encouraging customers to leave detailed and informative reviews by incentivizing feedback or providing clear guidelines on what constitutes a helpful review. This will help stakeholders to highlight these reviews prominently to enhance trust and credibility among prospective buyers.
This sentiment analysis system provides a scalable and automated way to interpret vast amounts of customer feedback. By leveraging NLP and deep learning, businesses can gain valuable insights to improve their products and services, ultimately enhancing customer satisfaction.
