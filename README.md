# IMDb-Movie-Recommender
Machine learning program that recommends movies to users based on their favorite movies using the [IMDb public dataset](https://www.imdb.com/interfaces/).

The model finds the best matches using a content-based approach. Recommendations are given based on similar attributes across movies, such as genres, directors, writers, etc.

Full source code can be found in `movie_recommender.ipynb`.
A subset of the movie data is contained in `popular_movies_df.csv` and used by `movie_recommender_DEMO.ipynb` for demonstration purposes. You can run the notebook yourself [here](https://mybinder.org/v2/gh/SamIAm10/IMDb-Movie-Recommender/HEAD?filepath=movie_recommender_DEMO.ipynb).

## Requirements
1. NumPy
2. Pandas
3. Scikit-learn
