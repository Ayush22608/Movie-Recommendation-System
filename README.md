# Movie Recommendation System 🎥

A content-based movie recommendation system that suggests movies similar to the one you select. It uses data from TMDB (The Movie Database) and implements cosine similarity to find and rank recommendations based on movie metadata like genres, cast, crew, and keywords.

---

## Features 🌟

- **Movie Metadata**: Uses data such as genres, keywords, cast, crew, and an overview to recommend movies.  
- **Interactive Web App**: Built with [Streamlit](https://streamlit.io/) for an easy-to-use interface.  
- **Movie Posters**: Fetches and displays movie posters using TMDB API.  
- **Efficient Recommendations**: Utilizes cosine similarity for computing and ranking movie recommendations.

---

## Installation 🛠️

### Prerequisites
- Python 3.7 or higher
- Libraries: `streamlit`, `pandas`, `numpy`, `scikit-learn`, `pickle`, `ast`, `requests`

### Steps

1. Clone the repository:  
   ```bash
   git clone https://github.com/Ayush22608/movie-recommender-system.git
   cd movie-recommender-system
