Titanic Survival Prediction

This project uses machine learning techniques to predict the survival of Titanic passengers based on their features. The dataset contains various columns like Age, Sex, Fare, and Embarked, which are processed and used to train multiple machine learning models.

Overview

Data Preprocessing: Missing values are imputed and categorical features are encoded.

Feature Engineering: New features such as Age_Pclass and FamilySize are created.

Models Used: Logistic Regression, Random Forest, Gradient Boosting, XGBoost, and LightGBM.

Hyperparameter Tuning: Optimized models using RandomizedSearchCV.

Best Model

The Random Forest model achieved an accuracy of 84.92% on the test set and was used for the final predictions.

Installation

Clone the repository:

git clone https://github.com/your-username/Titanic-Survival-Prediction.git

Install dependencies:

pip install -r requirements.txt
Usage

To run the notebook or script:

python predict_survival.py
Evaluation

The models are evaluated using the following metrics:

Accuracy

Confusion Matrix

ROC Curve and AUC

Contributing

Feel free to fork the repository, create an issue, or submit a pull request.
