# 🚀 Twitter Sentiment Analysis Bot: Emotion Detection with NLP 🚀

The Twitter Sentiment Analysis Bot is a project that analyzes the emotional expressions of social media users. This bot classifies Turkish tweets as positive, negative, or neutral, providing striking insights into users' emotional states. 🎉

## 📊 Project Goal
In this project, I developed a model capable of detecting the emotions behind tweets by analyzing Turkish tweets from 2022. By classifying tweets as positive, negative, or neutral, this bot offers remarkable insights into the emotional world of social media users!

## 🛠️ Technical Process

### 1. Data Collection
- Turkish tweets from 2022 were collected using Twitter APIs.
- Tweets containing emotional content, such as those about political figures, public institutions, and breaking news, were filtered out, focusing only on tweets reflecting users' personal emotions.

### 2. Data Cleaning and Preparation
- Stopwords were removed, punctuation marks were eliminated, and all texts were converted to lowercase.
- Lemmatization was applied to simplify the texts for more meaningful analysis.

### 3. Modeling and Algorithms
- Texts were transformed into numerical data using the TF-IDF Vectorizer.
- A model was trained using Logistic Regression to classify tweets as positive, negative, or neutral.
- Cross-validation was used to optimize the model's accuracy.

## 📉 Results and Findings
- The model assigned emotional labels (positive, negative, neutral) to each tweet in the dataset, allowing observation of the emotions behind the tweets.
- Emotional trends of tweets were analyzed based on time periods. For instance, an increase in positive tweets was observed on weekends, while neutral and negative tweet rates were higher during the weekdays.

## 🎨 Visualization and Analysis
- The relationships between numerical and categorical variables and the target variable (emotional labels) were visualized with graphs. This analysis revealed which factors influenced the likelihood of tweets being positive, negative, or neutral.
- The distribution of positive, negative, and neutral tweet counts was illustrated, providing valuable insights into the overall user mood.

## ✨ Benefits of the Project
This project offers a wide application area for brands, researchers, and individual users looking to analyze the emotional states of social media users. It can be used as a tool for improving user experience, conducting trend analyses, and developing social media strategies.
