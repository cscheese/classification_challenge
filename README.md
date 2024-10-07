## Module 13 - Classification Challenge (Spam)
#### Due Sept 6, 2024
Carolyn Scheese

### Background and Purpose 
Imagine you work for an Internet Service Provider (ISP) and you've been tasked with improving the email filtering system for its customers. You've been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. The ISP wants you to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

>You will be creating two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models you'll create will be a logistic regression model and a random forest model.

### Files 
https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv \
spam_detector.ipynb from Module 13

## Import
- import pandas as pd
- from sklearn.model_selection import train_test_split
- from sklearn.metrics import accuracy_score
- from sklearn.preprocessing import StandardScaler
- from sklearn.linear_model import LogisticRegression
- from sklearn.ensemble import RandomForestClassifier

### Before you Begin 
Create a new repository in GitHub called classification_challenge\
add the starter file spam_detector.ipynb from Module 13

### Instructions 
This challenge consists of the following subsections:
- Predict which model will perform best
- Split the data into training and testing sets
- Scale the features
- Create a Logistical Regression model. Set random_state argument to 1
- Create a Random Forest model. Set random_state argument to 1
- Evaluate the models 
