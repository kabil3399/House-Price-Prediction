# Real Estate Price Prediction Web Application

This Data Science project series walks through the **end-to-end process** of building a Real Estate Price Prediction website.

## Project Overview

The project is divided into three main components:

1. **Model Building**  
   We start by building a machine learning model using `scikit-learn` and `Linear Regression`, trained on the **Bangalore home prices dataset** from [Kaggle](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data). The focus is on data preprocessing and building a robust regression model.

2. **Python Flask Server**  
   In the next step, we save the trained model and build a **Python Flask server** that exposes an API endpoint to serve predictions via HTTP requests.

3. **Frontend Website**  
   Finally, we develop a simple frontend using **HTML, CSS, and JavaScript** that allows users to input property details (like square footage, number of bedrooms, etc.) and get a real-time price prediction using the Flask backend.

## Key Concepts Covered

This project covers a wide range of **Data Science** and **Machine Learning** concepts, including:

- Data loading and cleaning
- Handling missing values
- Outlier detection and removal
- Feature engineering
- Dimensionality reduction
- Model training and evaluation
- K-Fold cross-validation
- GridSearchCV for hyperparameter tuning
- Saving and loading trained models using `pickle`
- Creating REST API with Flask
- Frontend integration with backend using AJAX

## Technologies & Tools Used

- **Python**
- **NumPy** and **Pandas** for data manipulation
- **Matplotlib** for data visualization
- **scikit-learn** for model training and evaluation
- **Jupyter Notebook**, **Visual Studio Code**, and **PyCharm** as development environments
- **pickle** for model serialization
- **Flask** for building the API
- **HTML**, **CSS**, and **JavaScript** for the frontend UI

---

This project demonstrates a real-world application of machine learning, integrating backend and frontend to create a complete data-driven web application.
