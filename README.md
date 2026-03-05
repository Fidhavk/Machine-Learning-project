# Machine Learning Project 

*Company* : Zoople Technologies

*Name* : Fathima Fidha 

*mentor* : Jasheena 

# Project Overview
This project analyzes how different student lifestyle habits influence their academic performance. The dataset contains information about study habits, social media usage, sleep patterns, mental health, and other factors that may affect students' exam scores.
The main goal of this project is to explore relationships between student behaviors and academic outcomes using data analysis and machine learning techniques.

 # Dataset
 
student_id	
 
age

gender

study_hours_per_day	

social_media_hours	

netflix_hours	

part_time_job	

attendance_percentage	

sleep_hours	

diet_quality

exercise_frequency	

parental_education_level

internet_quality	

mental_health_rating	

extracurricular_participation

exam_score

Target Column : exam score

# Tools & Technologies 
Python

Pandas

# Models Evaluated :

Linear Regression

Support Vector Machine (SVM)

Decision Tree
 
K-Nearest Neighbors (KNN)

 Random Forest

# Steps Performed 
1. Dataset Import

The dataset was imported into the Python environment using the Pandas library.

Initial inspection of the dataset was performed using functions such as head(), info(), and describe() to understand the structure and data types.

2. Data Cleaning

Checked for missing values in all columns.

Verified and removed duplicate records if present.

Ensured each feature had the correct data type for analysis.

3. Exploratory Data Analysis (EDA)

Conducted basic analysis to understand relationships between variables.

Analyzed the distribution of study hours, sleep hours, and exam scores.

Examined the impact of social media usage and lifestyle habits on academic performance.

Generated correlation analysis to identify important features.

4. Handling Categorical Variables
Several columns in the dataset contained categorical data, which cannot be directly used in machine learning models.

These columns were converted into numerical values.

5.Label Encoding Using Map Function

Categorical features were encoded using the map() function in Python, assigning numeric values to each category. 

6.Feature Selection

Relevant features that influence exam scores were selected for analysis and modeling.

7. Model Development

Machine learning regression models were implemented to predict student exam scores based on lifestyle and academic factors.

8. Model Evaluation

Model performance was evaluated using standard regression metrics such as:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

# Model Performance Comparison- Regression Task

In my recent experiment, I evaluated multiple machine Learning models to identify the best performer.

 Linear Regression achieved a score of 92%
 
 Random Forest achieved a score of 85%

 Decision Tree achieved a score of 74%

 KNN achieved a score of 60%

 SVM achieved a score of 6%

Based on evaluation metric, Linear Regression emerged as the best performing model, offering both strong performance and better interpretability.

# Conclusion
This project demonstrates how data analysis and machine learning can be applied to understand the influence of lifestyle habits on academic performance. The findings provide valuable insights that could help educators and students make informed decisions to improve academic outcomes.
