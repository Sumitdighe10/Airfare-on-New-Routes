# Airfare-on-New-Routes

Overview

This project leverages machine learning to predict airfares based on a variety of features, such as departure and arrival airports, dates, airline preferences, and flight times. Using historical flight data, the project aims to provide accurate and actionable insights for travelers and companies looking to estimate travel costs effectively.

Model Overview

We experimented with multiple regression models including Linear Regression, Statsmodel. The final model was chosen based on its predictive performance and generalization capabilities to unseen data.

![dashboard](Screenshot%202025-03-10%20004552.png)

Data Preprocessing

Data cleaning involved handling missing values, encoding categorical variables, and normalizing numerical features to ensure optimal model performance. Feature selection was conducted through an iterative process to identify the most relevant predictors of airfare prices.
![dashboard](Screenshot%202025-03-10%20004626.png)

Performance Metrics

The models' performance was evaluated using the Root Mean Squared Error (RMSE) and R-squared (R²) metrics. These metrics were chosen to quantify the models' accuracy and the proportion of variance in airfares that can be predicted from the features.

Accuracy and Predictions Insights

Model Accuracy: Our final model, a tuned Statsmodel, achieved an RMSE of X and an R² of Y, indicating a high level of accuracy in predicting airfares.
Predictive Insights: Analysis of the model's predictions revealed several key trends, such as the significant impact of departure times and dates on prices, with early morning flights and flights booked well in advance generally being cheaper.
Usage Recommendations: Users can leverage this model to estimate airfares by inputting their desired flight parameters. For the best accuracy, ensure that the input features closely match the model's training data characteristics.

![dasboard](Screenshot%202025-03-10%20004641.png)

Getting Started

Prerequisites

Python 3.6+

Jupyter Notebook

Pandas

NumPy

Scikit-learn

Open the Airfares prediction.ipynb notebook in Jupyter Notebook or JupyterLab to view the project. The notebook is divided into several sections, including data loading, preprocessing, exploratory data analysis, model 
building, and evaluation.

Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.
