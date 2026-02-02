# 🎬 Movie Recommendation System

A content-based Machine Learning Movie Recommendation System developed using Python. The system recommends similar movies by analyzing movie features and computing similarity scores using cosine similarity.

📌 Domain

Machine Learning – Recommendation Systems

## How It Works:
- Uses content-based filtering
- Movies are represented as vectors
- Cosine similarity is calculated between movies
- Recommends top 5 similar movies
- Movie posters are fetched dynamically using the TMDB API

## Tech Stack:
- Python
- NumPy
- Pandas
- Pickle
- TMDB API
- Cosine Similarity

📁 Project Structure

Movie_recommendation/
├── app.py
├── requirements.txt
├── setup.sh
├── Procfile
├── .gitignore
└── README.md


## Installation (Run Locally):
1. Clone the repository
   - git clone https://github.com/sk7175197-beep/Movie-Recommender-Systemn.git
   - cd Movie_recommendation

2. Create virtual environment
   - python -m venv .venv
   - source .venv/bin/activate   (Linux/Mac)
   - .venv\Scripts\activate      (Windows)

3. Install dependencies
   - pip install -r requirements.txt

4. Run the app
   - streamlit run app.py

## Features:
- Movie selection dropdown
- Top 5 similar movie recommendations
- Dynamic movie posters

## Future Improvements:
- Add movie ratings and overview
-Hybrid recommendation system
- Add collaborative filtering

## 👩‍💻 Author
**Sakshi Jha**  
🎓 B.Tech CSE (2nd Year)  
🏫 Shobhit University, Meerut

