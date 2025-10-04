# 💻 Laptop Price Prediction

[![Live Project](https://img.shields.io/badge/Live_Project-Click_Here-blue)](https://laptop-price-prediction.onrender.com)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📄 Introduction

This project predicts the **price of laptops** based on specifications such as brand, RAM, processor, storage, and display type. It uses **machine learning regression models** to estimate laptop prices accurately. The model is deployed via **Flask** and accessible online for interactive predictions.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📊 Dataset

The dataset contains laptop specifications and their corresponding prices.

**Key Features:**
- `Brand` — Manufacturer of the laptop (e.g., Dell, HP, Apple)
- `RAM` — Memory size in GB
- `Processor` — Type of CPU
- `Storage` — HDD or SSD storage capacity
- `Display` — Screen size and type
- `Price` — Target variable (Laptop price)

**Steps Taken:**
- Loaded dataset into **Jupyter Notebook**
- Cleaned and encoded categorical features
- Removed duplicates and handled missing values
- Scaled/normalized numerical features where necessary

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📑 Steps Involved

* Dataset Loading & Inspection
* Data Preprocessing & Feature Engineering
* Exploratory Data Analysis using Seaborn & Matplotlib
* Model Training:
  - **Linear Regression**
  - **Random Forest Regression**
  - **Other regression pipelines**
* Model Evaluation using R² Score and error metrics
* Saving Trained Pipeline with `pickle`
* Flask App Development for Model Serving
* Deployment on Render

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🤖 Machine Learning Approach

- Preprocessing included **encoding categorical features** and **scaling numerical features**.
- Regression models were trained to predict laptop prices.
- The **final model pipeline** was saved as `pipe.pkl` for deployment.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🌐 Web App

- Built using **Flask**
- Users can input laptop specifications and get predicted prices
- Uses the trained pipeline (`pipe.pkl`) to make predictions
- Templates include `index.html` for input and `result.html` for displaying predictions

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 🔗 Deployment

This project is live and accessible at the following link:  
👉 **[Live](https://laptop-price-prediction.onrender.com)**

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## ✅ Conclusion

* Built a regression model pipeline to predict laptop prices.
* Deployed the model with Flask to create an interactive web application.
* Provides an easy-to-use interface for real-world laptop price prediction.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📚 References

* Original Dataset from **Kaggle**
* Scikit-learn Documentation: [https://scikit-learn.org](https://scikit-learn.org/)
* Flask Documentation: [https://flask.palletsprojects.com](https://flask.palletsprojects.com)
* Render Deployment: [https://render.com](https://render.com)

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nizaaf-dabir-524596203/)  
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NizaafDabir)
