🎬 Movie Recommendation System

A content-based movie recommender system that suggests similar movies using Sentence-BERT embeddings and a deep learning Autoencoder. The system learns semantic relationships between movies using metadata, including overview, keywords, cast, and genres.

🚀 Features

✔ Content-based recommendations
✔ Semantic understanding via SBERT
✔ Latent feature learning using Autoencoder
✔ Cosine similarity matching
✔ Works without user rating data
✔ Easy to extend and deploy

🧠 Models Used
Component	Model
Text Embedding	Sentence-BERT (all-MiniLM-L6-v2)
Dimensionality Reduction	Neural Autoencoder (Keras)
Similarity Search	Cosine Similarity

📂 Dataset
Uses TMDB Movie Dataset, consisting of:
tmdb_5000_movies.csv
tmdb_5000_credits.csv

Contains fields like:
Overview
Keywords
Genres
Cast
Crew


**IMPORTANT:** The `similarity.pkl` file is available via Google Drive (see `artifacts/` folder).





Sample embeddings with t-SNE:
<img width="1093" height="713" alt="image" src="https://github.com/user-attachments/assets/d2518627-2fd7-4aba-9ebb-7e4c0ee74b57" />

Autoencoder Training Progress:
<img width="1121" height="491" alt="image" src="https://github.com/user-attachments/assets/98ee3848-82be-4946-9b09-75d0c37d59dc" />

Movie Clusters:

<img width="822" height="678" alt="image" src="https://github.com/user-attachments/assets/bfe5436c-0074-41e5-8bd1-46ba3b70a11d" />



Working:

<img width="483" height="180" alt="image" src="https://github.com/user-attachments/assets/6bbbf031-6e2b-4168-b040-76a4d4ec331f" />









> ⚠️ **Important:** The `similarity.pkl` file is provided via Google Drive.  
> Check the link inside the `artifacts/` folder.

