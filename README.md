# 🚢 Titanic Survival Trends

This project analyzes passenger data from the Titanic dataset and predicts survival outcomes using a machine learning model. It also visualizes key trends like age, gender, and class to better understand survival patterns. The application is built using Flask and offers an interactive interface for predictions and exploration.

## 📁 Contents

- `titanic_survival_analysis.ipynb`: Jupyter Notebook used for data cleaning, exploratory analysis, and model training  
- `app.py`: Flask backend for handling user input and prediction requests  
- `model.pkl`: Serialized machine learning model trained on Titanic data  
- `templates/index.html`: HTML form for user input (e.g., Age, Gender, Pclass, etc.)  
- `static/style.css`: Optional styling for the frontend  
- `requirements.txt`: List of Python dependencies for running the project  

## 🛠️ Features

- Logistic regression model trained on Titanic dataset  
- User-friendly web form for entering passenger details and predicting survival  
- Data visualizations showcasing survival trends (age distribution, gender impact, class insights, etc.)  
- Easy to extend with additional ML models or interactive visualizations  

📊 Insights
The app also provides visual analysis including:
- Survival rate by gender
- Impact of passenger class on survival
- Age-related survival likelihood
- Heatmaps and trend charts for deeper exploration
