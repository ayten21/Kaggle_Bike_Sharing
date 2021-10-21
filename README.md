# Kaggle_Bike_Sharing
Rental of shared bikes
Bike sharing systems are a means of renting bicycles where the process of obtaining membership, rental, and bike return is automated via a network of kiosk locations throughout a city.
In this competition, participants are asked to combine historical usage patterns with weather data in order to forecast bike rental demand in the Capital Bikeshare program in Washington, D.C.

The goal of this challenge is to build a model that predicts the count of bike shared, exclusively based on contextual features. The first part of this challenge was aimed to understand, to analyse and to process those dataset. I wanted to produce meaningful information with plots. The second part was to build a model and use a Machine Learning library in order to predict the count.

The more importants parameters were the time, the month, the temperature and the weather.
Multiple models were tested during this challenge (Linear Regression, Gradient Boosting, SVR and Random Forest). Finally, the chosen model was Random Forest. The accuracy was measured with Out-of-Bag Error and the OOB score was 0.85.
