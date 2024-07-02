# Sentimental-Analysis-on-Amazon-Reviews-Using-Natural-Language-Processing-and-Deep-Learning
In this project , we used Natural Language Processing & Deep Learning models to Classify Amazon Reviews as either positive or negative. Reviews serve as the lifeblood of every business offering invaluable insights into customer satisfaction, prefernece and areas of improvement. Therefore these reviews are paramount for businesses seeking to thrive in comptetive markets, in todays digital space where consumers wield unprecedented influence through online platforms, understanding & interpregtting them.

### Overview
Online reviews have become a significant source of customer feedback for businesses. Amazon, being one of the largest online marketplaces, generates an enormous volume of customer reviews daily. These reviews provide valuable insights into customer satisfaction, preferences, and areas needing improvement. However, the sheer volume makes manual analysis impractical.

### Objective
This project aims to design and implement a sentiment analysis system using Natural Language Processing (NLP) and Deep Learning models to classify Amazon reviews as either positive or negative. The goal is to develop a robust model that can accurately interpret the sentiment expressed in the reviews, thus providing actionable insights for businesses to enhance their products and services.

### Approach
• Data Preparation

The project begins with cleaning and preprocessing the review data. This includes text cleaning to remove punctuation and special characters, tokenization to split text into words, normalization to convert text to lowercase and perform stemming or lemmatization, and padding/truncation to standardize text sequence lengths.

• Exploratory Data Analysis (EDA)

Visualizations and statistical analyses are conducted to understand the distribution of sentiments over time, across brands, and product categories. This helps in identifying trends and patterns in customer feedback.

• Feature Engineering

The textual data is transformed into numerical form using techniques like TF-IDF and Count Vectorization. Additionally, word embeddings such as Word2Vec and FastText are employed to capture semantic relationships between words. Bigrams and trigrams are also extracted to understand common word pairings.

• Model Building

Two deep learning models, a Simple RNN and an LSTM, are built to predict the sentiment of the reviews. Hyperparameter tuning is performed to optimize the models for better performance.

• Model Evaluation

The models are evaluated using accuracy scores, confusion matrices, and ROC curves to ensure they accurately classify the sentiment of the reviews.

### Results
The analysis reveals key insights into customer satisfaction and preferences. The distribution of review ratings shows a predominance of positive reviews. Temporal analysis indicates fluctuations in average ratings, while category analysis highlights high engagement in specific product categories. Bivariate analysis shows correlations between helpful votes, recommendations, and review lengths with ratings.

### Recommendations & Conclusion
This sentiment analysis system provides a scalable and automated way to interpret vast amounts of customer feedback. By leveraging NLP and deep learning, businesses can gain valuable insights to improve their products and services, ultimately enhancing customer satisfaction.
