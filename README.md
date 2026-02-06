
HealthKart Product Review Analysis 📊
====================================

Overview
--------
This project analyzes customer product reviews to understand **user sentiment** and **brand perception**.
The goal is to extract **meaningful insights** from unstructured review text and build a **simple recommendation logic**
based on customer feedback.

The solution focuses on **clarity, explainability, and practical thinking**, instead of complex black-box models.

Dataset 📁
---------
File used: GrammarandProductReviews.csv

The dataset contains:
- **Customer review text**
- **Product name**
- **Brand name**
- **Product category**
- **User rating**

What This Project Does 🔍
------------------------
- **Cleans raw review text** to remove noise
- **Classifies reviews** into Positive, Negative, or Neutral
- **Analyzes sentiment** at brand and product level
- **Visualizes sentiment trends**
- **Creates a basic recommendation logic** using sentiment

Tools Used 🛠️
-------------
- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook (Google Colab)**

Approach 🧠
-----------
1. **Load and explore the dataset**
2. **Clean review text** (lowercase, remove symbols and extra spaces)
3. **Apply a rule-based sentiment logic** using positive and negative keywords
4. **Group and analyze results** by brand and product
5. **Visualize insights** using simple charts
6. **Recommend brands** with higher positive sentiment

This approach keeps the logic **transparent and easy to explain**.

How to Run the Project ▶️
------------------------
1. Clone the repository
2. Open HealthKart_Review_Analysis.ipynb
3. Upload GrammarandProductReviews.csv
4. Run all cells sequentially

Docker Support 🐳
----------------
A basic Docker setup is included to ensure **reproducible execution**.

Commands:
- docker build -t healthkart-review-analysis .
- docker run -p 8888:8888 healthkart-review-analysis

Results 📊
----------
- **Overall customer sentiment distribution**
- **Brands with strong positive feedback**
- **Brands with repeated negative feedback**
- **Simple sentiment-based recommendations**

Future Improvements 🔮
----------------------
- **Improve sentiment accuracy** using machine learning
- **Combine ratings with sentiment scores**
- **Category-based recommendations**
- **Build a lightweight dashboard**

Final Note 📝
------------
This project demonstrates an **end-to-end analytical workflow**, from raw data to actionable insights,
with a strong focus on **simplicity, reasoning, and real-world understanding**.
