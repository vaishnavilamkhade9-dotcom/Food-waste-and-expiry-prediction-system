# 🍎 Food Waste & Expiry Prediction System

## 📌 Project Overview

The Food Waste & Expiry Prediction System is a Machine Learning project developed using the Logistic Regression algorithm. The main objective is to predict whether a food item is at risk of expiring based on its storage conditions, temperature, humidity, shelf life, and days since purchase.

The model classifies food items into two categories: **At Risk (1)** and **Not at Risk (0)**.

This project demonstrates how Machine Learning can help identify food expiry risks, reduce food wastage, and improve food storage management.

## 🎯 Objectives

- Predict food expiry risk using Machine Learning.
- Analyze the impact of storage conditions on food items.
- Understand and implement Logistic Regression.
- Classify food items into risk and non-risk categories.
- Demonstrate the application of Machine Learning in food waste management.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📂 Dataset Description

The dataset contains 600 records and 7 columns.

| Feature | Description |
|---|---|
| Food_Category | Category of food item |
| Days_Since_Purchase | Number of days since purchase |
| Shelf_Life_Days | Expected shelf life of food |
| Storage_Temperature_C | Storage temperature in Celsius |
| Storage_Humidity_Percent | Storage humidity percentage |
| Storage_Condition | Proper or Improper storage |
| Expiry_Risk | Target variable (0 or 1) |

**Dataset Note:** The dataset is synthetically generated for educational and demonstration purposes.

## 🤖 Algorithm Used

### Logistic Regression

Logistic Regression is a supervised Machine Learning classification algorithm used to predict categorical outcomes.

In this project, it predicts whether a food item is at risk of expiring or not.

**Target Variable: Expiry_Risk**

- 0 = Not at Risk
- 1 = At Risk

## ⚙️ Project Workflow

1. Import required Python libraries.
2. Upload and load the dataset.
3. Explore the dataset using Pandas.
4. Check and handle missing values.
5. Encode categorical variables using OneHotEncoder.
6. Scale numerical features using StandardScaler.
7. Split the dataset into training and testing sets.
8. Train the Logistic Regression model.
9. Predict food expiry risk.
10. Evaluate model performance.
11. Visualize results using graphs and a confusion matrix.

## 📊 Model Evaluation Metrics

The model performance is evaluated using:

- **Accuracy:** Measures the overall percentage of correct predictions.
- **Precision:** Measures how many predicted at-risk items are actually at risk.
- **Recall:** Measures how many actual at-risk items are correctly identified.
- **F1-Score:** Represents the balance between precision and recall.
- **Confusion Matrix:** Displays correct and incorrect classifications.

Actual evaluation results are generated when the notebook is executed.

## 📈 Expected Output

The model predicts whether a food item is at risk of expiring based on the given input features.

Example:

| Food Item | Prediction |
|---|---|
| Milk | At Risk |
| Rice | Not at Risk |
| Bread | At Risk |

*These are illustrative examples, not verified model predictions.*

## 💡 Applications

- Supermarkets and grocery stores
- Food storage management
- Food inventory monitoring
- Food waste reduction research
- Food supply chain management

## 🚀 Future Scope

- Integration with IoT-based temperature and humidity sensors.
- Development of a real-time food monitoring system.
- Integration with supermarket inventory management.
- Use of real-world food shelf-life datasets.
- Development of a web-based prediction dashboard.

## 📝 Conclusion

This project demonstrates the implementation of Logistic Regression for food expiry risk classification. It provides practical experience in data preprocessing, feature encoding, model training, prediction, and evaluation using Python and Scikit-learn.

The project serves as an educational prototype for exploring Machine Learning applications in food waste management. Real-world deployment would require validation using actual food quality and shelf-life data.

