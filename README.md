# Deep Learning for Beginners

This repository includes all the problems I solved during my learning of DL.

Process is split into parts related to the exact real world problem, and every problem has all the requered resources,
documents and shows the whole learning path from the idea, to the final implementation.

I tried to put as much time as possible to every problem, and provide solutions in both PyTorch and NumPy.

## Environment

 * Visual Studio Code
 * Jupiter Notebooks
 * Python 3
 * Pandas
 * Scikit-Learn
 * Pytorch
 * NumPy 

## Plan

### Movie recommendation system (MRS)  

Download the latest IMDB datasets from : https://datasets.imdbws.com/
and extract them into data/ folder.  

Download the latest MovieLens datasets from https://grouplens.org/datasets/movielens/

The following Jupiter Notebooks contain different implementations for MRS.  


[Movie Recommendation Content Based Filtering](1.0_movie_recommendation_cbf.ipynb)  

Movie recommendation system with content based filtering (CBF) developed with pandas, numpy and scikit-learn libraries.
It's using IMDB dataset.

[Movie Recommendation User Based Collaborative Filtering](2.0_movie_recommendation_ubcf.ipynb)  

Movie recommendation system with user based collaborative filtering UBCF deveoped with pandas, numpy and skikit-learn libraries.
It's using MovieLens dataset, as IMDB doesn't provide user ratings, only average rating values per movie.





