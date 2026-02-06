# HealthKart_Assignment
📊 HealthKart Product Review Sentiment Analysis
📌 Project Overview

This project analyzes customer product reviews to understand user sentiment, brand perception, and product affinity. The goal is to extract meaningful insights from unstructured review text and use them to build a simple recommendation logic.

The project is designed with a clear, explainable, and beginner-friendly approach, focusing on business understanding rather than complex black-box models.

🗂 Dataset

Source: Provided by HealthKart (assessment dataset)

Format: CSV file

Key columns used:

reviews.text → Customer review text

reviews.rating → User rating

brand → Brand name

name → Product name

categories → Product category

🔍 Problem Breakdown

This project addresses the following tasks:

Understanding and cleaning unstructured text data

Performing sentiment analysis on customer reviews

Analyzing brand and product-level sentiment trends

Inferring customer preference and dissatisfaction

Building a simple recommendation logic based on sentiment

Visualizing insights for easy interpretation

🛠 Tools & Technologies

Python

Pandas (data handling)

Matplotlib (visualization)

Google Colab (execution environment)

No pretrained sentiment models were used to keep the logic transparent and original.

🧹 Text Preprocessing

Customer reviews contain noise such as punctuation, symbols, and inconsistent casing.
To handle this:

Converted text to lowercase

Removed special characters

Removed extra spaces

This ensured cleaner input for sentiment analysis.

😊 Sentiment Analysis Approach

Instead of using a pretrained model, a custom rule-based sentiment approach was implemented.

Defined a small set of positive and negative words

Counted occurrences of these words in each review

Classified sentiment as:

Positive

Negative

Neutral

This approach is:

Easy to understand

Easy to explain

Suitable for beginner-level analysis

Less prone to plagiarism concerns

📊 Data Analysis & Insights

The following insights were derived:

Overall sentiment distribution of customer reviews

Brand-wise positive and negative sentiment trends

Product-level sentiment patterns

Identification of brands with high customer satisfaction

Detection of brands with frequent negative feedback

Visualizations were used to make trends easily interpretable for business use.

⭐ Recommendation Logic

A simple recommendation system was designed using sentiment distribution:

Brands/products with more positive than negative reviews were marked as recommended

This logic can be extended in future using ratings, categories, or advanced models

📈 Visualizations

The project includes:

Overall sentiment bar chart

Top brands with positive reviews

Brands with highest negative feedback

Top products with positive sentiment

These visuals help convert raw data into actionable insights.

🚀 How to Run the Project

Open the notebook in Google Colab

Upload the dataset file:

GrammarandProductReviews.csv


Run the cells sequentially from top to bottom

Review generated outputs and visualizations

🔮 Future Improvements

Use advanced NLP models (TF-IDF, Logistic Regression, BERT)

Incorporate star ratings into sentiment scoring

Improve sentiment vocabulary

Build category-specific recommendations

Deploy as a simple web dashboard

🧠 Key Learnings

Handling unstructured text data

Translating raw reviews into business insights

Importance of explainable logic

Building end-to-end analytical pipelines
