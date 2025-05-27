# content-based-movie-recommender
A content-based movie recommender system that suggests similar movies based on user-selected input. It uses natural language processing techniques such as TF-IDF and DistilBERT to analyze movie features like plot summaries, genres, and keywords. Built with Python and deployed using Streamlit for an interactive web experience.
📌 Overview

With the overwhelming number of movies released each year, finding a movie that suits your taste can be challenging. This recommendation system solves that problem by allowing users to select a movie and receive personalized recommendations based on the movie's content, not user ratings or popularity alone.

The system uses a combination of TF-IDF, Word2Vec, and DistilBERT embeddings to understand the semantic meaning of movie metadata and generate similarity scores using cosine similarity. It is deployed using Streamlit, offering an intuitive and interactive web interface.

🚀 Features

Recommend movies based on plot, genres, keywords, and more
Combines traditional and deep learning NLP techniques:
TF-IDF Vectorization
Word2Vec Embeddings
DistilBERT (Transformer-based) Embeddings
Interactive user interface built with Streamlit
Displays movie posters, overviews, ratings, and release years
User-friendly dropdown to select any movie from the dataset
Error handling for invalid selections
Feedback collection mechanism to evaluate recommendation performance
🧠 Technologies Used

Component	Tool/Library
Language	Python 3.x
Web Framework	Streamlit
NLP Techniques	TF-IDF, Word2Vec, DistilBERT
Vector Similarity	Cosine Similarity
Data Handling	Pandas, NumPy
Visuals & UI	Streamlit, TMDb API
Deployment	VS Code, GitHub
