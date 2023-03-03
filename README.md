# Bloc_3
## Analyse prédictive de données structurées par l'intelligence artificielle.

## VIDEO PRESENTATION
[LIEN VIDEO DE PRESENTATION](https://share.vidyard.com/watch/e5zyyF8zufvZvDxxrCR2Dm?)

----------


Here you will find 3 projects:

- Walmart Sales — Supervised ML

- Conversion Rate Challenge — Supervised ML

- Uber Pickups - Unsupervised ML


# 1- Walmart : predict weekly sales

## Company's Description 📇
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

This project is a machine learning competition like the ones that are organized by https://www.kaggle.com/. 

I have worked on it during my fullstack and I submitted my model's prediction to my teacher.
The scores achieved by the different teams were  stored into a leaderboard.

## Company's Description 📇

www.datascienceweekly.org is a famous newsletter curated by independent data scientists. Anyone can register his/her e-mail address on this website to receive weekly news about data science and its applications !

## Scope of the Project 🚧

The data scientists who created the newsletter would like to understand better the behaviour of the users visiting their website. They would like to know if it's possible to build a model that predicts if a given user will subscribe to the newsletter, by using just a few information about the user. They would like to analyze the parameters of the model to highlight features that are important to explain the behaviour of the users, and maybe discover a new lever for action to improve the newsletter's conversion rate.

They designed a competition aiming at building a model that allows to predict the conversions (i.e. when a user will subscribe to the newsletter). To do so, they open-sourced a dataset containing some data about the traffic on their website. To assess the rankings of the different competing teams, they decided to use the f1-score.

## Steps

    - Create some relevant figures for EDA
    - Train at least one model that predicts the conversions and evaluate its performances (f1, confusion matrices)
    - Make at least one submission to the leaderboard
    - Analyze your best model's parameters and try to make some recommendations to improve the conversion rate in the future
    

# 3- UBER Pickups: Find hot zones for Uber pickup per day and per hour

## Company's Description 📇
Uber is one of the most famous startup in the world. It started as a ride-sharing application for people who couldn't afford a taxi. Now, Uber expanded its activities to Food Delivery with Uber Eats, package delivery, freight transportation and even urban transportation with Jump Bike and Lime that the company funded.

The company's goal is to revolutionize transportation accross the globe. It operates now on about 70 countries and 900 cities and generates over $14 billion revenue! 😮

## Scope of Project 🚧
One of the main pain point that Uber's team found is that sometimes drivers are not around when users need them. For example, a user might be in San Francisco's Financial District whereas Uber drivers are looking for customers in Castro.

(If you are not familiar with the bay area, check out Google Maps)

Eventhough both neighborhood are not that far away, users would still have to wait 10 to 15 minutes before being picked-up, which is too long. Uber's research shows that users accept to wait 5-7 minutes, otherwise they would cancel their ride.

Therefore, Uber's data team would like to work on a project where their app would recommend hot-zones in major cities to be in at any given time of day.

## Steps

    - Find hot zones using clustering algorithms
    - Create a map with hot-zones using any python library (plotly or anything else).
    - Compare results with at least two unsupervised algorithms like KMeans and DBScan.
    
## Files
You'll find these files in the repository:
One folder per project and for each:
  - Requirements.txt 
  - A notebook with the whole project (conversion rate and uber were created on colab)
  - The dataset in csv file when provided
  - For conversion rate the results of my best model prediction in a csv file


