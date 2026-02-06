🏥 HealthKart Product Review Analysis 📊
📌 Overview

This project analyzes customer product reviews to understand user sentiment and brand perception.
The goal is to extract meaningful insights from unstructured review text and build a simple recommendation logic based on customer feedback.

The solution focuses on clarity, explainability, and practical thinking, rather than complex black-box models.

🗂️ Dataset

📄 File: GrammarandProductReviews.csv

The dataset contains:

📝 Customer review text

📦 Product name

🏷️ Brand name

🗃️ Product category

⭐ User rating

🔍 What This Project Does

🧹 Cleans raw review text

😊 Classifies reviews into Positive, Negative, or Neutral

🏢 Analyzes sentiment at brand level

📦 Analyzes sentiment at product level

📊 Visualizes key sentiment trends

⭐ Creates a simple sentiment-based recommendation logic

🛠️ Tools Used

🐍 Python

📊 Pandas

📈 Matplotlib

📓 Jupyter Notebook (Google Colab)

🧠 Approach

📥 Load and explore the dataset

🧹 Clean review text to remove noise

😊 Apply a rule-based sentiment logic using positive and negative keywords

🏷️ Group and analyze results by brand and product

📊 Visualize insights using simple charts

⭐ Recommend brands with higher positive sentiment

This approach keeps the logic transparent and easy to explain.

▶️ How to Run the Project

📁 Clone the repository

git clone <your-github-repo-link>


📓 Open HealthKart_Review_Analysis.ipynb

📤 Upload GrammarandProductReviews.csv

▶️ Run all cells sequentially

🐳 Docker Support

A basic Docker setup is included to ensure reproducible execution.

docker build -t healthkart-review-analysis .
docker run -p 8888:8888 healthkart-review-analysis

📊 Results

📈 Overall customer sentiment distribution

🏆 Brands with strong positive feedback

⚠️ Brands with repeated negative feedback

⭐ Simple sentiment-based recommendations

🔮 Future Improvements

🤖 Improve sentiment accuracy using machine learning

⭐ Combine ratings with sentiment scores

🗂️ Category-based recommendations

📊 Build a lightweight dashboard

📝 Final Note

This project demonstrates an end-to-end analytical workflow, from raw data to actionable insights, with a focus on simplicity and real-world understanding.
