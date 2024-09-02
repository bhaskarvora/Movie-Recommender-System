# Movie-Recommender-System
A Movie Recommender System using Cosine Similarity Algorithm

This project is a Movie Recommender System that suggests movies based on a selected movie's similarity to others. The system utilizes a machine learning model to determine the similarity between movies, allowing users to receive personalized movie recommendations. The application fetches movie details, including posters, from the TMDB (The Movie Database) API and displays them in a user-friendly interface using Streamlit.

# Functionality:
1. Movie Selection: Users can select a movie from a dropdown menu.
2. Recommendation: Upon selecting a movie, the app suggests five similar movies.
3. Poster Display: The application retrieves and displays the posters of the recommended movies.

# Steps Involved:
1. Data Loading: Load preprocessed movie data and a similarity matrix from pickle files.
2. Fetching Movie Poster: Use the TMDB API to fetch movie posters for the recommended movies.
3. Recommendation Algorithm: Calculate the similarity between the selected movie and other movies to generate recommendations.
4. User Interface: Use Streamlit to create an interactive interface where users can select a movie and view recommendations.


# Tech Stack

1. Python: 
2. Pandas :
3. Numpy : For numerical operations.
4. Streamlit: For building the web application and user interface.
5. Pickle: For loading pre-trained machine learning models and datasets.
6. TMDB API : Used to fetch movie details such as posters and metadata.
7. Machine Learning : Similarity Matrix where Precomputed similarity matrix stored as a pickle file to find movies similar to the one selected by the user.
   
![Screenshot 2024-09-01 221222](https://github.com/user-attachments/assets/42bccfcb-c52b-4a93-b4d8-d165bfb61550)
