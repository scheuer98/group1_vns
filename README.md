# group1_vns
This repo is for the final project of AM10 Visualisation and Storytelling

## What is your topic?

Cracking behaviour patterns when watchin Anime movies or series

## What issues or questions are you addressing?

We are wondering whether there are behavioural patterns within individuals when watching anime. In particular, we are wondering whether the ratings, the amount of people dropping, pausing or watching movies are correlated and ultimately whether we can predict dropping behaviour of individuals. Another interesting question might be, to what extent Anime movies are similar based on viewing patterns of individuals (non-aggregated data). This may go beyond the classical genre clustering. 

## What is the source of data you will be using?

We found a dataset on Kaggle: Anime Recommendation Database 2020. This database bases on recommendation data from 320.0000 users and 16.000 animes at myanimelist.net. The link to this data set is the following:
https://www.kaggle.com/datasets/hernan4444/anime-recommendation-database-2020

## What statistical techniques do you think you may be using?

First we are interested in classic correlation analysis of behavioural feautures and some standard hhypothesis test. Thereafter, we would like to consider constructing a prediction model to predict either the rating based on aggregate behaviour or other outcome variables, such as the dropping rate. The designated model might range from a classical OLS to a more complex Lasso model. Finally, if the analysis proves fruitful, we could turn to a clustering analysis to investigate whether certain movies are watched by similar individuals such that we can cluster movies based on selected feautures. The hope is that movies are clustered based on more features than just their genre. 
