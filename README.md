**** Movie Success Prediction using Machine Learning**

This project predicts whether a movie will be a HIT, AVG, or FLOP before its release using machine learning techniques. The prediction is based on multiple movie-related features collected from the IMDb dataset.

We compare the performance of three popular ML algorithms:

Naïve Bayes

Logistic Regression

Support Vector Machine (SVM)

** Project Objective**

The movie industry involves huge investments, and predicting a movie’s success in advance can help producers, investors, and distributors reduce risks.

The goal of this project is to:

Analyze movie features

Train ML models

Predict movie success category (HIT / AVG / FLOP)

Compare model performance using accuracy metrics

**Technologies Used**

Programming Language: Python

Libraries:

NumPy

Pandas

Matplotlib

Scikit-learn

Tkinter (GUI)

Machine Learning Algorithms:

Naïve Bayes

Logistic Regression

Support Vector Machine (SVM)

** Dataset**

Source: IMDb movie dataset

Preprocessing steps:

Handling missing values

Label encoding categorical features

Feature scaling

IMDb scores are categorized as:

FLOP → 1–3

AVG → 3–6

HIT → 6–10

⚙️ System Modules

Upload & Preprocess Dataset

Load dataset

Remove missing values

Convert IMDb scores into categories

Train-Test Split

Encode categorical features

Split data into training (80%) and testing (20%)

Model Training

Train Naïve Bayes

Train Logistic Regression

Train SVM

Prediction

Predict movie success for new test data

Performance Comparison

Accuracy

Precision

Recall

F1-Score

Graphical comparison

 **Results**

Logistic Regression showed better accuracy compared to Naïve Bayes and SVM.

The model successfully predicts movie success categories based on historical data.

** User Interface**

Built using Tkinter

Allows users to:

Upload datasets

Train models

View predictions

Compare algorithms visually

** How to Run the Project**

Clone the repository

git clone https://github.com/krushika06/movie-success-prediction.git


Navigate to the project folder

cd movie-success-prediction


Install required libraries

pip install numpy pandas matplotlib scikit-learn


Run the application

python main.py

 **Future Enhancements**

Use larger and more diverse datasets

Add deep learning models

Integrate sentiment analysis from social media

Deploy as a web application

** Author**

Krushika.Anagathala
B.Tech CSE Student
Passionate about Machine Learning & Full-Stack Development 🚀
