# Movie-Recommendation-System
Takes input from user and recommends similar movies.
This project Movie recommendation system is completely done in python and I used libraries such as pandas, matplotlib, seaborn for analysis and visualisation.
I used movielens 100k dataset from  google.
The main plot of the project lies in finding the correlation of any particular movie, which is given by user with other movies in the dataset.
Then filtering out some of them on the basis of num of ratings for a movie because a movie should not be recommended blindly on the basis of correlation value.
It also depends on the number of reviews aswell because judging correlation among 100 points and 5 points gives us wrong recommendations.
Inorder to satisfy the property of highest correlation and with some threshold num of ratings, I filtered out possibilities from obtained correlations.
These movies after filtration are the finall recommended movies.
