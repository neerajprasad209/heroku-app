
# Credit Card Default Prediction 

Financial threats are displaying a trend about the credit risk of commercial banks as the incredible improvement in the financial industry has arisen. In this way, one of the biggest threats faced by commercial banks is the risk prediction of credit clients. The goal is to predict the probability of credit default based on credit card owner's characteristics and payment history.

Use of various classification models like Decision Tree, Random Forest, XGBoost, MLPClassifier was done. XGBoost was selected as best model from above. The XGBoost model provided 82.63% accuracy in training. Testing accuracy for model was 82.3%. 80% data was used for training and 20% data was used for testing.
After Providing various details the model will predict whether customer will default next month or not. This project also provides the probability of default.

## Data Source

In our dataset we have 25 columns which reflect various attributes of the customer. The target column is default.payment.next.month , which reflects whether the customer will default next month or not. Our aim is to predict the probability of default given the payment history of the customer. I have built my model using a public dataset available on kaggle.

URL - https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset

## WebSite URL

My WebApp URL - https://credit-card-prediction-app-b25350855058.herokuapp.com/

## Software Requirements 

1) Python 3.10.7
2) Visual Studio Code
3) Git Cli
4) Jupyter Notebook
5) Heroku account
6) GitHub account

## Approach

Below are steps taken to build this project
1) Create Repository on GitHub with gitignore as pyhton.
2) Clone Repository from GitHub to Local using git clone command in VS Studio Code
3) Create a virtual environment inside working foleder named venv use command - python -m venv "path/venv"
4) Create a requirements.txt file which contains all libraries that are required to run this project.
5) Read Dataset using pandas library
6) Start Exploratory data analysis
7) Start building various models like Decision Tree Classifier, Random Forest Classifier, XGBoost Classifier, KNN Classifier, MLP Clasiifier
8) Tune the models with cross validation using GridSearchCV
9) Select best model and make pickle file.
10) Create app.py file which used dash library for front-end design.
11) Test the app.py on local system.
12) Create Procfile for deployement in Heroku platform.
13) Add, Commit and Push all files from Local to GitHub
14) Deploy to Heroku and Link the GitHub Repository

## Documentation

1) [Detailed-Project-Report](https://drive.google.com/file/d/1Uaa8f8sR0gkJY9PK_xt3bswuf-XAt1cv/view?usp=drive_link)
2) [High-Level-Design-Document](https://drive.google.com/file/d/1J-jRZ-SRwQjJi0eqkjo0ZmEvqqhBA0yO/view?usp=drive_link)
3) [Low-Level-Design-Document](https://drive.google.com/file/d/1pCtLrQoTme0pLjSLqtfDQuEb0hfU02Cy/view?usp=drive_link)
4) [Architecture](https://drive.google.com/file/d/15rZY9-HKWtl8vhHM5g4krBHy3V8AOn39/view?usp=drive_link)
5) [Wireframe](https://drive.google.com/file/d/1vRIHXOgqgsttgM3d8A3ePKJ0Bfm6bz4k/view?usp=drive_link)

# Project Demo

[Youtube-Link](https://www.youtube.com/watch?v=SQjVszfayhY)

## Author Linkedin URL 

Linkedin URL - https://www.linkedin.com/in/neeraj-prasad-86a89b202/

## Author

[@neerajprasad209](https://github.com/neerajprasad209)












