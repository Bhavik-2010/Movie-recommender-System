# Movie Recommender System  

This is a content-based movie recommender system built using Python, Streamlit, and The Movie Database (TMDb) API. It suggests five similar movies based on user selection.  

## Features  
- Recommends movies based on similarity.  
- Fetches movie posters using TMDb API.  
- Interactive UI with Streamlit.  

## Installation  
1. Install dependencies:  
   ```bash
   pip install streamlit pandas requests pickle5
   ```  
2. Run the app:  
   ```bash
   streamlit run app.py
   ```  

## Files  
- `app.py` – Streamlit app.  
- `movie_dict.pkl` – Movie data.  
- `similarity.pkl` – Precomputed similarity matrix.  

## Usage  
- Select a movie from the dropdown.  
- Click “Recommend” to get suggestions with posters.  

## Note  
Ensure the API key in `fetch_poster` is valid.  
