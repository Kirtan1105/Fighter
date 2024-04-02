# Titanic Survival Prediction 
This project performs data preprocessing on the Titanic dataset to predict passenger survival using machine learning.
# Getting Started
Download the Titanic file from the Kaggle.com 
# Prerequisites
open an google account in colaboratory i.e www.colab.research.google.com
Ensure you have Python installed along with the following libraries:
- Pandas
- NumPy
- Scikit-learn
You can install the required packages using pip:
pip install pandas numpy scikit-learn
Its an cloud base coding.

# Installing
git clone https://github.com/kirtan1105/titanic-survival-prediction.git
Navigate to the project directory:
"cd titanic-survival-prediction"
Install the required packages
"pip install -r requirements.txt"

# Running the Tests
The project includes a RandomForestClassifier for predicting survival. To ruIf you wish to deploy the model, you can use the trained RandomForestClassifier. You may need to save the model using joblib or pickle for future use.n the tests:

Ensure you have completed the "Installing" steps.
Run the following command:

"python titanic_survival.py"

This will train the model and print the mean test scores with various parameters.

# Breakdown of Tests

Data Preprocessing: The code performs data cleaning steps including handling missing values, dropping unnecessary columns, and encoding categorical variables.
Model Training: The RandomForestClassifier is used for training the model to predict survival.

# Deployment

If you wish to deploy the model, you can use the trained RandomForestClassifier. You may need to save the model using joblib or pickle for future use.

# Author

https://github.com/Kirtan1105

# license
Open source

# Acknowledgement
The Titanic dataset is obtained from Kaggle: Titanic: Machine Learning from Disaster

Template for README.md obtained from PurpleBooth



