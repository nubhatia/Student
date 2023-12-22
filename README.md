## Student Performance Indicator ML Project

### Life Cycle of Machine Learning Project

- Understanding the Problem Statement
- Data Collection
- Data Checks
- Exploratory Data Analysis (EDA)
- Data Pre-processing
- Model Training
- Choose the Best Model


### 1) Problem Statement

- This project explores how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.


### 2) Data Collection

- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
- The data consists of 8 column and 1000 rows.

### 3) Deployment
- Utilizing Elastic Beanstalk on AWS for streamlined application deployment.
- Implementing CodePipeline for automated continuous integration and delivery.

### 4) To Run (Flask API)
- Install the dependencies using "pip install -r requirements.txt"
- Run the application using  "python application.py"
- Open your web-browser and navigate to "http://127.0.0.1:5000/predictdata"
- Select the values from dropdown menus.
- Press the "Predict your Maths score" button