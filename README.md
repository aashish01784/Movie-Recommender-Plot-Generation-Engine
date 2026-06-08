# Movie-Recommender-and-Plot-Generation-Engine
# 🎬 Movie Recommender & Plot Generation Engine

A machine learning-powered recommendation system that suggests similar movies based on metadata, genres, and content similarity while generating original movie plots using Large Language Models (LLMs).

---

## Features

### Movie Recommendation System
- Recommends movies similar to a user-provided title.
- Supports fuzzy title matching for handling spelling variations.
- Retrieves and enriches movie metadata using IMDb information.
- Uses content-based filtering to identify similar movies.
- Generates Top-N ranked recommendations.

### AI Plot Generation
- Generates original movie plots from user-selected genres.
- Utilizes Hugging Face language models for story generation.
- Creates structured narratives with characters, settings, conflicts, and resolutions.
- Supports multiple genres including Action, Comedy, Thriller, Romance, Sci-Fi, and Drama.

---

## Dataset

### MovieLens Dataset
- movies.csv – Movie titles and genre information.
- links.csv – Mapping between MovieLens and IMDb identifiers.

### Additional Metadata
- IMDb movie information
- Genre details
- Cast and crew information
- Plot descriptions

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Load MovieLens datasets.
- Clean and preprocess movie metadata.
- Extract and normalize genre information.

### 2. Feature Engineering
- Combine movie genres and metadata.
- Create textual representations of movies.
- Prepare data for similarity computation.

### 3. Recommendation Engine
- Apply fuzzy title matching using RapidFuzz.
- Compute movie similarities using vectorization techniques.
- Rank and recommend the most relevant movies.

### 4. Plot Generation
- Accept user-selected genres.
- Generate custom movie plots using Hugging Face LLMs.
- Produce coherent and genre-specific storylines.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- RapidFuzz
- IMDbPy
- Hugging Face Inference API
- Requests
- Jupyter Notebook

---

## Key Highlights

- Processed and analyzed 3,000+ movies for recommendation generation.
- Implemented content-based filtering using movie genres and metadata.
- Integrated IMDb metadata retrieval for enhanced recommendations.
- Built an AI-powered plot generation engine using Hugging Face models.
- Utilized CountVectorizer and Cosine Similarity for recommendation ranking.

---

## Project Structure

text Movie-Recommender/ │ ├── Movie_Recommender_and_Plot_Generation_Engine.ipynb ├── movies.csv ├── links.csv ├── README.md │ ├── Recommendation Module │   ├── Fuzzy Matching │   ├── Metadata Processing │   ├── Similarity Computation │   └── Recommendation Ranking │ └── Plot Generation Module     ├── Genre Processing     ├── Prompt Engineering     └── Hugging Face Integration 

## Future Enhancements

- Collaborative filtering recommendations
- Hybrid recommendation systems
- User rating integration
- Streamlit web application deployment
- Personalized recommendation profiles
- Fine-tuned language models for plot generation

---

## 👨‍💻 Author

Aashish Shriram
