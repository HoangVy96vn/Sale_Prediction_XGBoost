# Sale_Prediction_XGBoost
Sale Prediction by XGBoost

This includes models with 2 dataset. At first, I planned to train model with only data about time. 
We all know in business, we have several features driving sale, not only time. But as too many feature add burden to our model (actually when I tried with too many features, the model took too much time for running), we need to choose right features. I started with only time.

From the first prediction, we can see that XGBoost performed very vell, but as value distributes on wide range, model accuracy is not good.
I used second dataset with information of price and currency. From 2nd prediction, we found importance of price feature, also improve accuracy of the model
