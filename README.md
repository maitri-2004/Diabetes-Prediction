# Diabetes Prediction using Machine Learning  

## Overview  
This project aims to predict whether a person is diabetic or not based on various medical features. The model is trained using **Logistic Regression** and achieves an accuracy of **78.5%**. A **Streamlit web app** is developed for easy user interaction, where users can input their health data to get a prediction.  

## Features  

### **Input Features:**  
The model takes the following health parameters as input:  
- **Pregnancies** - Number of times pregnant  
- **Glucose** - Glucose concentration level  
- **BloodPressure** - Blood pressure measurement  
- **SkinThickness** - Thickness of skin fold  
- **Insulin** - Insulin level in the blood  
- **BMI** - Body Mass Index  
- **DiabetesPedigreeFunction** - Genetic risk factor for diabetes  
- **Age** - Age of the individual  

### **Output:**  
- **1** → The person is **Diabetic**  
- **0** → The person is **Not Diabetic**  

## Model Details  

### **Algorithm Used:**  
- **Logistic Regression**: A statistical model that predicts binary outcomes based on input features.  

### **Libraries Used:**  
- `numpy` → For numerical operations  
- `pandas` → For data manipulation  
- `scikit-learn` → For model training and preprocessing  
- `pickle` → To save and load the trained model  
- `streamlit` → For building an interactive web application  

## Future Improvements  
- Improve model accuracy using **feature selection** and **hyperparameter tuning**.  
- Train with advanced models like **Random Forest**, **XGBoost**, or **Neural Networks**.  
- Deploy the web app using **AWS, GCP, or Heroku** for online access.  
- Enhance the UI with better visualizations and user experience improvements.  





