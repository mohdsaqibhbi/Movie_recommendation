# Movie_recommendation
A Movie Recommendation system trained on Movielens data 100k using collaborative method. The implementation is done step by step in the jupyter-notebook.
![movies](readme.jpeg)

## Notebooks
- [**Data Preprocessing and EDA**](Data_Preprocessing_and_EDA.ipynb)
  This jupyter-notebook contains all the data preprocessing and EDA required.
  - Reading data into csv file.
  - Data Preprocessing.
  - EDA.
- [**Collaborative Filtering**](Collaborative_Filtering.ipynb)
  This jupyter-notebook contains the training and evaluation of the model. After the training the embeddings of users and movies are saved. Later, precision@k and     recall@k is calculated for each user.
  - Data preparation for training and validation.
  - Training and evaluating model.
  - Saving embeddings of users and movies.
  - Calculating precision@k and recall@k for each user.
- [**Recommend movies**](Recommend_movies.ipynb)
  This jupyter-notebook contains the filling of rating table for all user-movie as well as recommendation of movies to the user.
  - Filling rating table for all user-movie.
  - Recommending movies to a user.
  
## How to run
- Clone the repo using `git clone https://github.com/mohdsaqibhbi/Movie_recommendation.git`.
- Go to this directory using `cd Movie_recommendation`
- Create virtual environment.
- Install dependencies using `pip3 install -r requirements.txt`.
- Run everything step by step.
