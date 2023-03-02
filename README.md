# Bloc_3
Analyse prédictive de données structurées par l'intelligence artificielle.

Video


Here you will find 3 projects:

- Walmart Sales — Supervised ML

- Conversion Rate Challenge — Supervised ML

- Uber Pickups - Unsupervised ML


# 1- Walmart : predict weekly sales

Company's Description 📇
Walmart Inc. is an American multinational retail corporation that operates a chain of hypermarkets, discount department stores, and grocery stores from the United States, headquartered in Bentonville, Arkansas. The company was founded by Sam Walton in 1962.

## Scope of the Project 🚧
Walmart's marketing service has asked you to build a machine learning model able to estimate the weekly sales in their stores, with the best precision possible on the predictions made. Such a model would help them understand better how the sales are influenced by economic indicators, and might be used to plan future marketing campaigns

## Steps 
    - Create some visualizations
    - Train at least one linear regression model on the dataset, that predicts the amount of weekly sales as a function of the other variables
    - Assess the performances of the model by using a metric that is relevant for regression problems
    - Interpret the coefficients of the model to identify what features are important for the prediction
    - Train at least one model with regularization (Lasso or Ridge) to reduce overfitting
    
    
# 2- Conversion Rate Challenge: Predict website newsletter conversion

In this project, you will participate to a machine learning competition like the ones that are organized by https://www.kaggle.com/. You will be able to work with jupyter notebooks as usual, but in the end you'll have to submit your model's predictions to your teacher/TA, so your model's performances will be evaluated in an independent way. The scores achieved by the different teams will be stored into a leaderboard 🏅🏅
Description of a machine learning challenge 🚴🚴

    In machine learning challenges, the dataset is always separated into to files :
        data_train.csv contains labelled data, which means there are both X (explanatory variables) and Y (the target to be predicted). You will use this file to train your model as usual : make the train/test split, preprocessings, assess performances, try different models, fine-tune hyperparameters etc...
        data_test.csv contains "new" examples that have not be used to train the model, in the same format as in data_train.csv but it is unlabeled, which means the target Y has been removed from the file. Once you've trained a model, you will use data_test.csv to make some predictions that you will send to the organizing team. They will then be able to assess the performances of your model in an independent way, by preventing cheating 🤸
    Your model's predictions will be compared to the true labels and releases a leaderboard where the scores of all the teams around the world are stored
    All the participants are informed about the metric that will be used to assess the scores. You have to make sure you're using the same metric to evaluate your train/test performances !

Company's Description 📇

www.datascienceweekly.org is a famous newsletter curated by independent data scientists. Anyone can register his/her e-mail address on this website to receive weekly news about data science and its applications !

Project 🚧

The data scientists who created the newsletter would like to understand better the behaviour of the users visiting their website. They would like to know if it's possible to build a model that predicts if a given user will subscribe to the newsletter, by using just a few information about the user. They would like to analyze the parameters of the model to highlight features that are important to explain the behaviour of the users, and maybe discover a new lever for action to improve the newsletter's conversion rate.

They designed a competition aiming at building a model that allows to predict the conversions (i.e. when a user will subscribe to the newsletter). To do so, they open-sourced a dataset containing some data about the traffic on their website. To assess the rankings of the different competing teams, they decided to use the f1-score.

Deliverable 📬
To complete this project, your team should:

    Create some relevant figures for EDA
    Train at least one model that predicts the conversions and evaluate its performances (f1, confusion matrices)
    Make at least one submission to the leaderboard
    Analyze your best model's parameters and try to make some recommendations to improve the conversion rate in the future
    

# 3- UBER Pickups: Find hot zones for Uber pickup per day and per hour

Company's Description 📇
Uber is one of the most famous startup in the world. It started as a ride-sharing application for people who couldn't afford a taxi. Now, Uber expanded its activities to Food Delivery with Uber Eats, package delivery, freight transportation and even urban transportation with Jump Bike and Lime that the company funded.

The company's goal is to revolutionize transportation accross the globe. It operates now on about 70 countries and 900 cities and generates over $14 billion revenue! 😮

Project 🚧
One of the main pain point that Uber's team found is that sometimes drivers are not around when users need them. For example, a user might be in San Francisco's Financial District whereas Uber drivers are looking for customers in Castro.

(If you are not familiar with the bay area, check out Google Maps)

Eventhough both neighborhood are not that far away, users would still have to wait 10 to 15 minutes before being picked-up, which is too long. Uber's research shows that users accept to wait 5-7 minutes, otherwise they would cancel their ride.

Therefore, Uber's data team would like to work on a project where their app would recommend hot-zones in major cities to be in at any given time of day.

Scope of this project 🖼️
To start off, Uber wants to try this feature in New York city. Therefore you will only focus on this city.


Deliverable 📬
To complete this project, your team should:

    Have a map with hot-zones using any python library (plotly or anything else).
    You should at least describe hot-zones per day of week.
    Compare results with at least two unsupervised algorithms like KMeans and DBScan.
