**Collaborative Filtering Recommendation System (MovieLens-100k)**

An implementation of a movie recommendation engine using the classic MovieLens-100k dataset.

**Goal**: Build a model that can predict a user's rating for a movie they haven't seen and generate a list of personalized movie recommendations.

**Dataset**: The MovieLens-100k dataset, containing 100,000 ratings from 943 users on 1,682 movies.

**Methodology**: The system is based on Collaborative Filtering. It specifically uses the Singular Value Decomposition (SVD) algorithm via the surprise library to factorize the user-item interaction matrix, evaluate performance (RMSE/MAE), and generate top-N recommendations for a specific user.

**Key Technologies**: surprise library (SVD), pandas, numpy.
