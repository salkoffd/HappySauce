# HappySauce
Final project for UCD Data Analytics

# Introduction
Are there differences in happiness between regions? Furthermore, what socio-economic factors predict happiness?
Using data from the U.S. census and the Centers for Disease Control and Prevention (CDC), we can begin to answer these questions.
Rather than relying on an arbitrary survey to assess happiness, we will use suicide rate as a proxy for decreased happiness.

# Databases
U.S. Census ACS 5-Year Detailed Tables https://api.census.gov/data/2017/acs/acs5.html  
Centers for Disease Control and Prevention, Mortality - underlying cause of death https://wonder.cdc.gov/WelcomeA.html#S

# Analysis
Individual variables will be plotted against suicide rate. After several variables are selected, they will be included in at least two models to predict suicide rate. The first model will be a multiple regression model from the scikit-learn library. The second model will be a moderately-deep neural network from the tensorflow keras library.

# Libraries
scikit-learn, tensorflow keras, pandas, matplotlib.
