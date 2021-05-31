# Data Science Portfolio by Chi-Hao Sheng
A collection of projects ranging from data collection to model deployment that utilized various machine learning and deep learning techniques. 

# End-to-End Projects
Projects that combined my interests with data science concepts. The entirety of the projects involved data collection, data analysis, model training, and model deployment.

[**Battlefield V Analysis and Prediction**](https://github.com/chihaos1/Battlefield-V-Analysis-and-Prediction) &nbsp;&nbsp;&nbsp; [Final Website Link](https://battlefieldv-stats-prediction.herokuapp.com/)\
Analyzed players' statistics to evaluate players' performance by predicting their Score Per Minute (SPM).
* Scrapped over 18,000 player statistics from [Battlefield Tracker](https://battlefieldtracker.com/) using Python and Scrapy. 
* Used data wrangling techniques to clean the collected data.
* Created a linear regression model (MAE ~ 40 SPM) to predict player's Score Per Minute.
* Built a web API using Flask with data visualization graphed by Chart.js.
* Deployed the model on the web API using Heroku. 

[**Premier League Position Prediction**](https://github.com/chihaos1/Premier-League-Position-Prediction) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Final Website Link](https://plposprediction-api.herokuapp.com/)\
Analyzed the statistics of English Premier League teams from the past 28 years to predict the position they would be able to achieve at the end of the season. 
* Scrapped about 500 team statistics from [Wikipedia](https://en.wikipedia.org/wiki/1992%E2%80%9393_FA_Premier_League#League_table) using Python and Scrapy.
* Created a linear regression model (MAE ~ 1 Position) to predict a team's league position. 
* Built a web API using Flask. 
* Deployed the model on the web API using Heroku. 

# Machine Learning Projects
Notebooks that centered on analyzing datasets with various regression and classification techniques.

**Regression Problems:**

[**House Price Prediction**](https://nbviewer.jupyter.org/github/chihaos1/Notebooks/blob/main/house-price-prediction.ipynb)\
Dataset from a competition on [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview). The goal of the project was to predict house prices based on 77 house features such as total living area and number of bedrooms. The data wrangling process involved filling missing values and transforming features. The data analysis process involved visualizing the relationships between features and target and selecting the relevant features. The model training process involved building a linear regression model that could predict house prices with the given parameters. 

**Classification Problems:**

[**Student Achievement Rating Prediction**](https://nbviewer.jupyter.org/github/chihaos1/Notebooks/blob/main/student-achievement-rating-prediction.ipynb)\

