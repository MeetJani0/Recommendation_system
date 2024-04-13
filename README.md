# Movie Recommender System
## Overview
- This repository contains a movie recommendation system built using TMDB's 5000 movies dataset.
- The recommendation system is based on content-based filtering, leveraging movie metadata to suggest similar movies based on user preferences.

## Features
- Utilizes TMDB's 5000 movies dataset
- Content-based recommendation model
- Recommendation engine suggests similar movies based on user preferences
## Installation
- To run the movie recommendation system locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies by running pip install -r requirements.txt.
3. Place the movies_dict.pkl and similarity.pkl files in the project directory.
4. Run the Movie_Recommender_system.py script to start the recommendation system.
## Usage
1. Run the Movie_Recommender_system.py script.
2. Input your preferred movie title.
3. Receive recommendations based on the content of the input movie.
## Dataset
- The dataset used in this project is the [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) from Kaggle, which includes information about 5000 movies.
## Model
- The recommendation system is built on a content-based model, which analyzes movie metadata such as genres, keywords, and overview to suggest similar movies.

## Files
- movies_dict.pkl: Contains movie ID, title, tags, and other metadata after preprocessing.
- similarity.pkl: Contains the similarity (distance) between two movies after preprocessing.
- Movie_Recommender_system.py: Script to deploy the movie recommender system.
- Movie_Recommender_system.ipynb: Jupyter notebook containing the content-based recommendation model.
# Deployment
## Local Deployment
- To deploy the movie recommender system locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies.
3. Place the movies_dict.pkl and similarity.pkl files in the project directory.
4. Run the Movie_Recommender_system.py script to start the recommendation system.

## Cloud Deployment
- To deploy the movie recommender system on a cloud host, follow these general steps:

1. Set up a virtual environment on your cloud host.
2. Transfer the repository files to your cloud host environment.
3. Install the required dependencies within your cloud host environment.
4. Place the movies_dict.pkl and similarity.pkl files in the project directory on your cloud host.
5. Configure any necessary environment variables.
6. Run the Movie_Recommender_system.py script or deploy as a web service according to the cloud host's guidelines.
7. For detailed instructions on deploying to specific cloud hosts such as AWS, Google Cloud Platform, or Azure, refer to their respective documentation.

## Credits
- TMDB for providing the dataset.
- @MeetJani0 for developing the recommendation system.
