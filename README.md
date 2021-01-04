# Deep Learning for Beginners

This repository includes all the problems I solved during my learning of DL.

Process is split into parts related to the exact real world problem. I included some papers and lots of docs, explanations.

## Environment

 * Visual Studio Code
 * Jupiter Notebooks
 * Python 3
 * Pandas
 * Scikit-Learn
 * Pytorch
 * NumPy 
 * SciPy
 * LightFM

 * Surprise


## Plan

### Movie recommendation system (MRS)  

The goal here - get recommendations for movies/series based on my interest in *Star Wars*.
I will use different approaches and compare results, and ... watch recommendations!


#### Ralated papers  
[II CF from Amazon](papers/[2003] Item-to-Item Collaborative Filtering.pdf)  

#### How to start  

Download the latest IMDB datasets from : https://datasets.imdbws.com/
and extract them into data/ folder.  

Download the latest MovieLens datasets from https://grouplens.org/datasets/movielens/
and put them into data/ folder.

#### Solutions

The following Jupiter Notebooks contain different implementations for MRS.  

[Movie Recommendation Content Based Filtering](1.0_movie_recommendation_cbf.ipynb)  

Movie recommendation system with content based filtering (CBF). It uses Cosine Similarity algorithm. Developed with pandas, numpy and scikit-learn libraries.
It's using IMDB dataset.

[Movie Recommendation User Based Collaborative Filtering](1.1_movie_recommendation_ubcf.ipynb)  

Movie recommendation system with user based collaborative filtering (UBCF). It uses Cosine Similarity algorithm. Developed with pandas, numpy and skikit-learn libraries.
It's using MovieLens dataset, as IMDB doesn't provide user ratings, only average rating values per movie.


[Movie Recommendation Item Based Collaborative Filtering](1.2_movie_recommendation_ibcf.ipynb)  

Movie recommendation system with item based collaborative filtering (IBCF). It uses Cosine Similarity algorithm. Developed with pandas, numpy and skikit-learn libraries.
It's using MovieLens dataset, as IMDB doesn't provide user ratings, only average rating values per movie.


[Movie Recommendation with Matrix Factorisation](1.3_movie_recommendation_mf.ipynb)  

Movie recommendation system with Matrix Factorisation approach. (MF). It uses SVD/SVD+ algorithms. Developed with pandas, numpy,scipy and skikit-learn libraries.
It's using MovieLens 100K dataset, as IMDB doesn't provide user ratings, only average rating values per movie. I coulnd't get it working with 20M, and 25M datasets - as it overflows my memory.

[Movie Recommendation with Deep Learning](1.4_movie_recommendation_dl.ipynb)  

[Movie Recommendation with LightFM library](1.5_movie_recommendation_lightfm.ipynb)  


[Movie Recommendation with Surprise library](1.6_movie_recommendation_surprise.ipynb)  






