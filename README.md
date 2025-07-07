# spotify_song_recomendation
# 🎧 Music Recommendation System using Spotify Dataset

This project builds a basic content-based music recommendation system using data from Spotify. The system recommends similar songs based on audio features like energy, tempo, valence, danceability, etc.

## 🎯 Objectives

- Load and preprocess a Spotify music dataset.
- Explore and analyze audio features.
- Build a content-based recommendation system using cosine similarity.
- Recommend songs based on user input (track name).

## 📁 Project Files

- `music-recommendation-system-using-spotify-dataset.ipynb` – Main notebook containing the full analysis and model.
- `spotify_data.csv` – Dataset containing song metadata and audio features.
- `recommendation_output/` – (Optional) folder to store outputs or result logs.

## 🧰 Libraries & Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib & Seaborn (for visualization)

## ⚙️ How the System Works

- The dataset includes numeric features like energy, danceability, loudness, and more.
- Cosine similarity is calculated between feature vectors.
- Given a song name, the system recommends the top N most similar songs based on feature similarity.

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/spotify-music-recommender.git
   cd spotify-music-recommender
   ```

2. **Install dependencies**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

3. **Run the notebook**:
   ```bash
   jupyter notebook music-recommendation-system-using-spotify-dataset.ipynb
   ```

## 🧪 Example Output

- Input: `'Blinding Lights'`
- Recommendations:
  - `'Save Your Tears'`
  - `'In Your Eyes'`
  - `'Can't Feel My Face'`

(*Note: The above is an example. Actual results depend on the dataset used.*)

## 📊 Features Used for Similarity

- Acousticness  
- Danceability  
- Energy  
- Instrumentalness  
- Liveness  
- Loudness  
- Speechiness  
- Tempo  
- Valence

## 📌 Dataset Source

Spotify Dataset via [Kaggle - Top Spotify Songs](https://www.kaggle.com/) or similar public sources.

---

## 🤝 Contributions

Feel free to open an issue or pull request to improve the recommendation logic or UI.

## ⭐️ Support

If you like this project, please consider giving it a ⭐️ on GitHub!

---

**Author**: [Your Name or GitHub Handle]  
**License**: MIT (or your preferred license)
