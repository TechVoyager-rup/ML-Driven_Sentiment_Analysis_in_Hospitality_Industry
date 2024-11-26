# ML-Driven Sentiment Analysis in Hospitality Industry

## Project Overview

This project utilizes **Machine Learning (ML)** and **Natural Language Processing (NLP)** to analyze customer reviews for hotels, enabling businesses in the hospitality industry to gain valuable insights. By classifying reviews based on sentiment (positive, neutral, or negative), it assists hotels in improving their services and customer experience, while providing actionable data to drive business strategy.

## Key Features

- **Sentiment Analysis**: Classifies hotel reviews into positive or negative categories based on the content of customer feedback.
- **Business Insights**: Generates actionable insights based on sentiment analysis to improve customer satisfaction and service quality.
- **Web Platform**: Provides a simple interface for businesses to visualize sentiment and key areas for improvement.
- **Customizable**: The solution can be adapted for analyzing reviews from different domains or industries.

## Technologies Used

- **Programming Languages**: Python
- **Libraries**:
  - **NLTK**: For preprocessing text and performing sentiment analysis.
  - **Scikit-learn**: For training machine learning models (SVM, Logistic Regression, Random Forest).
  - **Pandas & NumPy**: For handling and processing data.
  - **Matplotlib & Seaborn**: For data visualization.
- **Deployment**: Can be hosted on cloud platforms or local servers.

## Dataset

The dataset used contains hotel reviews with ratings and textual feedback. Reviews are labeled with sentiment values based on their ratings (positive or negative). The dataset is flexible and can be extended or modified for other use cases.

## Installation & Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/TechVoyager-rup/ML-Driven_Sentiment_Analysis_in_Hospitality_Industry.git
   cd ML-Driven_Sentiment_Analysis_in_Hospitality_Industry

Usage
Preprocessing & Model Training:

Reviews are preprocessed using NLP techniques like tokenization, stopword removal, and lemmatization.
Sentiment analysis models (SVM, Logistic Regression, Random Forest) are trained to predict the sentiment of new reviews.
Prediction:

Input new reviews into the model to predict whether they are positive or negative.
Example
Input Review:
"Absolutely fantastic experience at Taj City Centre Kolkata! The property is beautifully maintained and situated in a very convenient location."

Output Sentiment:
SVM Prediction: Good Review
Logistic Regression Prediction: Good Review
Random Forest Prediction: Good Review
