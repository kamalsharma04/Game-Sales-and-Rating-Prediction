Game Sales and Rating Prediction
📊 Overview

This project analyzes and predicts global video game sales based on various features such as platform, genre, critic scores, user scores, publisher, and more.
It also visualizes trends in the gaming industry, revealing insights about top-selling publishers, genres, and regional preferences.

🚀 Key Features

📈 Data Cleaning and Preprocessing

🧩 Feature Encoding and Scaling

🔍 Data Visualization using Matplotlib, Seaborn, and Plotly

🧠 Machine Learning Model: Random Forest Regressor

⚙️ Model Evaluation with MSE and RMSE

💡 Predicts future global sales of video games based on user and critic scores

🧰 Tech Stack

Python 🐍

NumPy, Pandas — Data manipulation

Matplotlib, Seaborn, Plotly — Data visualization

Scikit-learn — Machine learning

Jupyter Notebook — Development environment

📁 Project Structure
📦 Game-Sales-and-Rating-Prediction
 ┣ 📜 Video_Games.csv
 ┣ 📜 sales_ratting.ipynb
 ┗ 📜 README.md

📊 Model Performance
Metric	Score
MSE	1.10
RMSE	1.04
🧠 How It Works

Cleans and preprocesses the dataset

Encodes categorical data

Splits dataset into training and testing sets

Trains a Random Forest Regression model

Evaluates predictions using MSE & RMSE

📸 Visual Insights

Top 10 publishers by global sales

Most popular genres worldwide

Correlation heatmap between key features

Comparison of critic vs user ratings

🧑‍💻 Author

Kamal Sharma
🎓 BCA Student @ Multani Mal Modi College, Patiala
💭 Aspiring Data Scientist
📬 GitHub Profile

🌟 Future Improvements

Add a recommendation system for games

Integrate more features (price, platform release year, etc.)

Deploy model using Streamlit or Flask