🏏 IPL Score Prediction using Machine Learning:

This project uses machine learning techniques to predict the final score of an IPL innings based on live match data like current runs, wickets, overs, and run rate. It combines data cleaning, exploratory analysis, model training, and an interactive widget interface built with ipywidgets.



📌 Project Objective:

The goal is to build a regression model that predicts the final score of a team in an IPL match using partial match data (e.g., first 5 to 15 overs). This can help simulate match outcomes, assist broadcasters with analytics, and support fan engagement in real-time.



🔍 Key Features:

🧹 Data Cleaning & Preprocessing
* Removed irrelevant columns and handled categorical data.



📊 Exploratory Data Analysis (EDA):

Visualized run distribution, wicket trends, and team-based scoring patterns using Seaborn and Matplotlib.



🤖 Model Building:

Used Random Forest to train on historical data and predict the total score.



🧩 Interactive Widget:

Designed an intuitive UI with ipywidgets to input match parameters and view predicted scores instantly.



✅ Model Performance:

* R² Score: ~0.95

* Indicates a strong predictive performance with low error.

* Metrics Used: R², Mean Absolute Error (MAE)



🧠 Tech Stack:

* Python

* Pandas, NumPy

* Matplotlib, Seaborn

* Scikit-learn

* ipywidgets

* Jupyter Notebook
