# Spotify Songs Data Analysis

Data analysis project on a Spotify tracks dataset. The goal is to explore audio features, understand what drives track popularity, and train a simple model to predict popularity scores.

---

## Project overview

Using a track‑level Spotify dataset, this notebook:

- Cleans and prepares audio feature and popularity data.
- Explores relationships between audio features and `track_popularity`.
- Builds a correlation matrix and visualizations.
- Uses `SelectKBest` to rank important features.
- Trains and evaluates a regression model for popularity.

---

## Dataset

**File:** `spotify_songs.csv`  

Each row represents a single track and includes:

- **Track metadata:** `track_id`, `track_name`, `track_popularity`
- **Audio features:** `danceability`, `energy`, `acousticness`, `loudness`, `speechiness`, `instrumentalness`, `liveness`, `valence`, `tempo`, `key`, `mode`

Used purely for educational and portfolio purposes.

---

## Notebook

**File:** `Spotify-data-analysis.ipynb`

Main steps:

1. Load and inspect data with pandas.
2. Perform EDA and correlation heatmap.
3. Run `SelectKBest` to score features.
4. Train a `LinearRegression` model and evaluate with RMSE.

---

## How to run

```bash
git clone https://github.com/Utham-ds/Spotify-Song-Data-Analysis.git
cd Spotify-Song-Data-Analysis

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

jupyter notebook
```
## Author
Utham Kumar Mohanlal
