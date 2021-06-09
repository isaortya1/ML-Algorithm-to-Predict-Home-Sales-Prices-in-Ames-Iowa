# ML-Algorithm-to-Predict-Home-Sales-Prices-in-Ames-Iowa
I used Ames, Iowa housing data compiled by Dean De Cock at Truman State University to predict the sales price of homes in the dataset. The Ames Housing dataset was created by Dean de Cock for use in data science education. The dataset contains 2930 observations and 79 explanatory variables for the houses.
I used python pandas library to create dataframes from the dataset, remove rows with missing target variable and separate the target variables from the predictor variables. I used the scikit-learn's model selection package to separate training data from validation data, remove categorical data with relatively low cardinality, and one-hot encode the data. The model was constructed using gradient boosting from the XGBoost library. The model achieved a mean absolute error of 14810.12828 on the test data provided by the Kaggle competition, which ranked 4405 out of 67885 on the public leaderboard.

The data set used is available at the following URL:
http://jse.amstat.org/v19n3/decock.pdf
