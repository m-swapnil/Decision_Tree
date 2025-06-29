# Loan Default Prediction Using Decision Tree
##### This project aims to build an end-to-end Machine Learning pipeline to predict loan defaults and deploy it via a Flask web application. It follows the CRISP-ML(Q) methodology, focusing on minimizing loan defaulters while maximizing profitability for the bank.

## 🚀 Business Objective 

##### Problem: Significant proportion of customers are defaulting on loans.
##### Goal: Minimize loan defaulters while maximizing bank profit.

## Success Criteria:

##### Reduce loan defaulters by at least 10%
##### Achieve ML accuracy over 92%
##### Save the bank more than 1.2 million USD

## 📁 Dataset

#### Source: Bank’s historical loan data
#### Size: 1000 customers
#### Features: 16 input variables + 1 output variable (loan default status)

## 🛠️ Project Workflow (CRISP-ML(Q))

#### Business Understanding
#### Analyze default problem
#### Define objectives and constraints

## Data Collection

#### 1000 records with 17 columns
#### Data Preparation & EDA
#### Used Sweetviz and D-Tale for automated EDA
#### Imputation (mean strategy)
#### Scaling (MinMaxScaler)
#### OneHot Encoding
#### Outlier handling (Winsorization)

## Model Building

#### Decision Tree with hyperparameter tuning (GridSearchCV)
#### Achieved ~92% accuracy

## Model Evaluation

#### Business, ML, and economic success criteria
#### Stratified sampling to balance classes

## Model Deployment
#### Flask web app with file upload

#### Prediction results stored in PostgreSQL

## Model Monitoring & Maintenance
#### Predictions saved to MS SQL / PostgreSQL for further monitoring

## 💻 Tech Stack
#### Python (pandas, sklearn, matplotlib, seaborn, joblib, pickle)

#### PostgreSQL (data storage)
#### SQLAlchemy (ORM)
#### Flask (deployment)
#### Sweetviz, D-Tale (EDA automation)
#### Graphviz (model visualization)

## 📝 Key Features

#### ✅ End-to-end ML workflow (CRISP-ML(Q))
#### ✅ Data cleansing, encoding, outlier treatment
#### ✅ Cross-validation and hyperparameter tuning
#### ✅ Flask-based user interface for file upload and predictions
#### ✅ Automatic saving of predictions to the database
#### ✅ Business and economic success criteria evaluated

## ⚙️ Setup Instructions

#### Clone the repo
#### git clone https://github.com/yourusername/loan-default-dt-flask.git
#### cd loan-default-dt-flask
#### Install dependencies
#### pip install -r requirements.txt
#### Setup PostgreSQL
#### Create a database called loandefault
#### Update your credentials in the Python code (or use environment variables for security)

#### Run the Flask app
#### python app.py
#### Navigate to http://127.0.0.1:5000/
#### Upload a CSV or Excel file and get predictions on loan default risk.

## 🗂️ Project Structure
##### loan-default-dt-flask/
##### │
##### ├── credit.csv
##### ├── app.py
##### ├── DT.pkl
##### ├── imp_enc_scale
##### ├── winsor
##### ├── Report1.html
##### ├── templates/
##### │   ├── index.html
##### │   └── new.html
##### ├── requirements.txt
##### └── README.md

## 🏆 Results
#### ✅ Achieved over 92% accuracy on test data
#### ✅ Reduced estimated loan default rate by ~10%
#### ✅ Model is ready for deployment and business monitoring

## 🙌 Acknowledgements
#### CRISP-ML(Q) methodology
#### scikit-learn documentation
#### Flask documentation
#### Graphviz for visualization
#### PostgreSQL community

##### Feel free to ask if you want me to adjust or expand this further .
