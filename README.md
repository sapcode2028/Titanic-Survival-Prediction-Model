This project is an end-to-end Machine Learning pipeline that predicts whether a passenger survived the Titanic disaster. It uses the famous Kaggle Titanic dataset for training, applies Logistic Regression for prediction, and provides a Flask web application (hosted via ngrok) for real-time predictions through a browser interface.

Features

Data Preprocessing & Cleaning

Handles missing values in Age, Embarked, and Cabin.

Encodes categorical variables (Sex, Embarked).

Exploratory Data Analysis (EDA)

Visualizations with Seaborn & Matplotlib.

Survival distribution across gender, class, and age groups.

Model Training & Evaluation

Logistic Regression model implemented with scikit-learn.

Model saved as titanic_model.pkl using Joblib.

Accuracy evaluation on both training and test sets.

Deployment

Flask web app with an HTML form for user input.

ngrok integration to expose the app to the web.

User-friendly survival prediction results**
