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

**Regression Problems:**

[**House Price Prediction**](https://nbviewer.jupyter.org/github/chihaos1/chihaos1.github.io/blob/main/Notebooks/house-price-prediction.ipynb)\
Dataset from a competition on [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview). The goal of the project was to predict house prices based on 76 house features such as total living area and number of bedrooms. The data wrangling process involved filling missing values and transforming features. The data analysis process involved visualizing the relationships between features and target and then selecting the relevant features. The model training process involved building a linear regression model that could predict house prices with the given parameters. 

**Classification Problems:**

[**Student Achievement Rating Prediction**](https://nbviewer.jupyter.org/github/chihaos1/chihaos1.github.io/blob/main/Notebooks/student-achievement-rating-prediction.ipynb)\
Dataset from [NYC Open Data](https://data.cityofnewyork.us/Education/2017-2018-School-Quality-Reports-Elem-Middle-K-8/g6v2-wcvk). The goal of the project was to predict the student achievement rating (Not Meeting Target, Meeting Target, Approaching Target, and Exceeding Target) of a particular school based on 25 school features such as student attendance rate and economic need index. The data wrangling process involved encoding and scaling the features. The model training process involved building a k-nearest neighbors algorithm that could classify student achievement ratings based on the given parameters.

[**White Wine Quality Prediction**](https://nbviewer.jupyter.org/github/chihaos1/chihaos1.github.io/blob/main/Notebooks/white-wine-quality-prediction.ipynb)\
Dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality). The goal of the project was to predict the quality (score between 0 to 10) of white wines based on 11 features such as pH, density, and residual sugar. The project employed several machine learning (logistic regression, decision tree, XGBoost) and deep learning techniques to compared their performances. The one with the highest cross validation score was logistic regression.

# Deep Learning Projects

**Convolutional Neural Network:**

[**President Image Identifier**](https://github.com/chihaos1/President-Image-Identifier) &nbsp;&nbsp;&nbsp; [Notebook Link](https://nbviewer.jupyter.org/github/chihaos1/President-Image-Identifier/blob/main/President%20Image%20Identifier.ipynb)\
Dataset scrapped from [Getty Image](https://www.gettyimages.com/) using the ImagePipeline provided in Scrapy. The goal of the project was to build an algorithm that could identify Barack Obama, Donald Trump, and Joe Biden from the provided images. Image augmentation was used to expand training dataset and to make the model more robust. ResNet50 and VGG16 were both employed and compared and it was tested that VGG16 had better performance. 

# School Projects

[**Budget Calculator**](https://github.com/chihaos1/budget_calculator)\
Final group project for INST326: Object-Oriented Programming. The program could track users' budget and provide financial advices such as how to improve credit scores and manage savings. The project utilized the object-oriented concept to structure the codes into classes and methods, which was beneficial for developing and debugging the program.  

[**Vinyl Record Database**](https://github.com/DiegoAmores/Vinyl-Record-Database)\
Final group project for INST327: Database Design and Modeling. The database contained detailed information of 20 vinyl records such as producers, ratings, and chart placements. The process of building the database involved creating and populating tables, modeling relationships between tables, and normalizing the database to optimize performance.
