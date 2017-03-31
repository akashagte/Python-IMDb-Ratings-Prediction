# Python-IMDb-Prediction-Engine
Created a simple Prediction Engine based on IMDb ratings and social media presence

Human behaviour has been a subject of fascination for many years and it is even more interesting when it comes to predicting Movie Ratings based on the responses of thousands of individuals on platforms like the IMDb.

The initial objective from this project was to learn in-depth regarding the implementation of Machine Learning algorithms through Python and the IMDb Ratings database gave a perfect and unique opportunity to learn the same. 

The data was equally fascinating since the target variable 'Rating' was Continuous and Ordinal at the same time:
1. The Ordinal part of the variable came from the fact that IMDb Ratings are in the range of 0-10, with 10 being the best
2. The values within these 10 categories are continuous for a single interval

Hence to make the prediction more robust for Recommendation purposes, I decided to test 2 types of Machine Learning models:
1. Regressors: to account for the changes in continuous data
2. Classifiers: to factor in the Ordinal behaviour of the 'Rating' attribute

The ultimate goal through this Project was:
"To enable Prediction of QUALITY OF FRESH CONTENT (movies in this case) based on Social Media attributes such as Facebook Likes for Movie, number of Votes given, popularity of cast members and recognition of Director by the masses"

Such an exercise was necessary since these factors are more crucial than ever given the huge number of corporate dollars spent on Promoting movies both in the Televised as well as Social Media; and also the fact that Networks/Production Houses have to generate fresh content at a rapid pace.

The generated models strive to predict the Movie Ratings with perfect accuracy, but since human behaviour is a complicated subject there are some assumptions which I made:
1. Predictions within the range of +/-1.0 star for the Linear Models were considered Accurate
2. Target variable 'Rating' was classified further into A--D categories signifying the quality of the movie, "A" being Excellent

End Result: Achieved 79% Accuracy
