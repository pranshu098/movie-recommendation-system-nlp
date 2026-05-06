# movie-recommendation-system-nlp
Content-based movie recommendation system using NLP, TF-IDF, and cosine similarity to suggest similar movies.

}
# 🎬 Movie Recommendation System

## 📌 Overview
This project is a Movie Recommendation System built using Natural Language Processing (NLP) techniques.

It recommends movies based on similarity of content like:
- Overview
- Genres
- Tagline
- 

## 🚀 Features
- Content-based filtering
- NLP preprocessing (stopwords removal, lemmatization)
- TF-IDF vectorization
- Cosine similarity for recommendations


## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK


## 📊 Workflow
1. Data Cleaning
2. Feature Selection
3. Text Preprocessing
4. TF-IDF Vectorization
5. Similarity Calculation
6. Recommendation Function


## 🔍 How it Works
- Combines movie text data into a single feature (tags)
- Converts text into vectors using TF-IDF
- Computes similarity using cosine similarity
- Recommends top N similar movies


## 🧪 Example
python recommend("Toy Story") 


## 📦 Files
- movie.ipynb → Main notebook
- df.pkl → Processed dataframe
- tfidf.pkl → TF-IDF model
- tfidf_matrix.pkl → Vectorized data
- indices.pkl → Movie index mapping


## ⚙️ Installation
bash pip install -r requirements.txt 


## 📌 Future Improvements
- Add web app (Streamlit / FastAPI)
- Use Deep Learning models
- Add user-based recommendation


## 👨‍💻 Author
Priyanshu
