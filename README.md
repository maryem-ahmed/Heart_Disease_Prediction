Heart Disease Prediction using Machine Learning
A comprehensive machine learning project implementing multiple supervised learning algorithms to predict heart disease risk based on clinical parameters.

 Project Overview
This project demonstrates the application of various supervised learning techniques for binary classification in healthcare. Using the Cleveland Heart Disease dataset (303 patients with 13 clinical features), multiple machine learning models are trained and compared to identify the most effective approach for predicting heart disease presence. The dataset has a balanced distribution with approximately 54% positive cases (heart disease present) and 46% negative cases.

Models Implemented
Random Forest (RF) - Ensemble method using multiple decision trees
Decision Tree (DT) - Tree-based model for interpretable predictions
Support Vector Machine (SVM) - Kernel-based classification algorithm
K-Nearest Neighbors (KNN) - Distance-based classification method
Dataset Information
The dataset contains 303 patient records with 14 attributes for heart disease prediction:

Features Description:
age: Age in years
sex: Gender (1 = male, 0 = female)
cp: Chest pain type (0-3: typical angina, atypical angina, non-anginal pain, asymptomatic)
trestbps: Resting blood pressure (in mm Hg)
chol: Serum cholesterol level (in mg/dl)
fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
restecg: Resting electrocardiographic results (0-2)
thalach: Maximum heart rate achieved
exang: Exercise induced angina (1 = yes, 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: Slope of the peak exercise ST segment (0-2)
ca: Number of major vessels colored by fluoroscopy (0-4)
thal: Thalassemia type (0-3: normal, fixed defect, reversible defect)
target: Heart disease presence (1 = disease, 0 = no disease)
Technologies Used
Python - Primary programming language
Pandas - Data manipulation and analysis
NumPy - Numerical computations
Scikit-learn - Machine learning algorithms and evaluation
Matplotlib/Seaborn - Data visualization

Project Structure
├── heart_disease_prediction.ipynb    # Main notebook with analysis
├── heart.csv                        # Cleveland Heart Disease dataset
├── README.md                        # Project documentation
└── requirements.txt                 # Python dependencies

🎯 Learning Objectives
This project demonstrates proficiency in:

Supervised learning algorithm implementation
Model comparison and evaluation techniques
Healthcare data analysis
Python machine learning ecosystem
Binary classification problem solving
🔍 Key Insights
Comparative analysis of different supervised learning approaches
Understanding of model strengths and weaknesses
Feature importance in heart disease prediction
Performance trade-offs between different algorithms
🤝 Contributing
This is a learning project, but suggestions and improvements are welcome.

Fork the repository
Create a feature branch
Submit a pull request
