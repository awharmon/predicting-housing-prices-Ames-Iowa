Introduction
In this report, the housing data from Ames, Iowa is used to create a linear regression model which predicts the housing prices of homes sold from 2006 to 2010.  The two datasets provided where train.csv and test.csv.  The train.csv was used to create and train the linear regression models through train-test-splits, feature engineering, standardization, regularization, and the manipulation of various hyperparameters.  The test.csv contained no Sale Price data and was used to generate predictions to be submitted to Kaggle.com.  These predictions were judged on their RMSE scores based on a small portion of the data until the competition was closed, at which point the predictions were scored against the full true set of Sale Prices.  The models I created placed me 25th out of 122 participants, with only a ~6,000 difference in RMSE score from first place.

Organization
The report is comprised of two notebooks in which I took the data from the start and created models.  The two notebooks represent the main difference in approaches but contain iterations within.  Additionally, all of my submissions can be found in the repository (with timestamps).