*Project Title

Machine Learning Model to Predict Customer Satisfaction

*Project Description

This project focuses on developing a Customer Satisfaction Prediction System using machine learning techniques. The system analyzes customer feedback data and predicts whether a customer is satisfied or not based on various service-related attributes such as service quality, response time, product satisfaction, and overall experience.

The project implements multiple machine learning models and compares their performance to identify the most accurate prediction model.

 Objectives
To analyze customer feedback data
To build predictive machine learning models
To compare performance of different algorithms
To improve decision-making using data-driven insights
* Machine Learning Models Used
Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)
Linear Regression
Support Vector Regression (SVR)
* Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn
Google Colab / Jupyter Notebook
   Project Structure
Customer-Satisfaction-Prediction/
│
├── dataset/
│   └── customer_feedback.csv
│
├── notebook/
│   └── model.ipynb
│
├── src/
│   └── main.py
│
├── requirements.txt
└── README.md
  * How to Run the Project
-Option 1: Run in Google Colab (Recommended)
Open Google Colab
Click on New Notebook
Upload your project file (.ipynb or .py)
Upload dataset (customer_feedback.csv)
Install required libraries (if needed):
!pip install pandas numpy scikit-learn matplotlib seaborn
Run all cells step-by-step
View predictions and results
- Option 2: Run on Local System
Step 1: Clone Repository
git clone https://github.com/your-username/customer-satisfaction.git
cd customer-satisfaction
Step 2: Install Dependencies
pip install -r requirements.txt
Step 3: Run Python File
python main.py
*  How the System Works
Load customer dataset
Perform data preprocessing
Handle missing values
Encode categorical data
Feature scaling
Split dataset (70:30 and 80:20)
Train multiple ML models
Evaluate models using metrics
Select best-performing model
*  Evaluation Metrics
Mean Squared Error (MSE)
R² Score
Precision
Recall
F1-Score
  * Results Summary
SVR performed best with highest accuracy
Random Forest showed strong performance
KNN & Linear Regression gave moderate results
Decision Tree showed overfitting

The models were tested on both 70:30 and 80:20 splits for better reliability.

* Dataset
Source: Kaggle
Type: Structured CSV dataset
Target: Customer Satisfaction (0/1 or score)
