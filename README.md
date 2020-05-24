# Sparkify
Capstone Project, Udacity Data Science Nanodegree

Github Repo:https://github.com/linpingyu/Sparkify

# Files Contained in this Repo
Notebook Sparkify.ipynb
data on zip file
and html file 
Readme   Readme.md

### Overview:
consider sparkfy as a popular digital music service similar to Spotify or Pandora, and that this company has provided us with a set of data regarding their users, Users stream their favorite songs using the free level which places ads between songs or using the premium plan for which they pay a monthly subscription without any advertising between songs. Users can upgrade, downgrade or completely cancel their services. Our task in this project is to develop a model that predicts which users are at risk. If we can identify users who are at risk of opting out either by downgrading the premium or canceling their service, the company can offer them incentives and discounts that potentially save millions of revenues.

### Data
User log extracted from our service.

### Packages:
PySpark, Pandas, Seaborn, Matplotlot.pylpot

### Models:
Logistic Regression, Gradient Boosted Trees, Support Vector Machines, Random Forest

### Methodology:
1. ETL
2. Define customer churn and EDA
3. Feature engineering
4. Modeling 
5. Evaluation
6. Feature import analysis

### Others:
This is mostly a practice of using spark environment to analyze large volume of data, the main part can be replicated locally by just using packages like panads and numpy. 

### summry:
As we can see from the result the predictions are enough good. The use of RandomForestClassifier let us predict users’ future actions with high accuracy. The main pain points of this analysis were feature engineering and pipeline creation as they are slightly different with pyspark-ml than with python&scikitlearn.
This analysis was done in the workspace provided by Udacity and on the data set mini_sparkify_event_data.json of small size and inspired by the materials learned during the lessons. The next is to continue the analysis on the full dataset is of size 12GB in cloud…

### My Post:
https://medium.com/@hider.tla/churn-analysis-using-pyspark-dccfea13035f
