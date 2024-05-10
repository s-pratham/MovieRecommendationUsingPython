# Movie Recommendation System Using Python

This repository contains a movie recommendation system developed using Python and machine learning techniques. The project involves:

- **Data Preparation and Exploratory Data Analysis (EDA):**
  - Utilizing pandas, numpy, seaborn, and matplotlib for data loading, cleaning, visualization, and analysis.
  - Handling missing values and basic statistical analysis.

- **Demographic Filtering:**
  - Implementing a basic demographic filtering method to recommend movies based on popularity and average ratings.
  
- **Content-Based Filtering:**
  - Building a content-based recommendation system to recommend movies based on movie descriptions (overviews).
  - Utilizing TF-IDF vectorization and cosine similarity to compute movie similarities.

## Project Structure

- **Notebooks:**
  - `Movie_Recommendation_System.ipynb`: Jupyter notebook containing the complete project code with detailed explanations and visualizations.

- **Data Files:**
  - `anime.csv`: Dataset containing anime information.
  - `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`: Datasets containing movie information used for content-based filtering.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Movie-Recommendation-System.git
   cd Movie-Recommendation-System
   ```

2. Open and run the `Movie_Recommendation_System.ipynb` notebook in Jupyter or any preferred environment.

## Results

- **Top Rated Movies:** 
  - Visualizations of top-rated movies based on weighted rating.

- **Popular Movies:**
  - Visualizations of most popular movies based on popularity score.

- **Content-Based Recommendations:**
  - Recommendations for specific movies based on movie overviews.

## Acknowledgments

- Datasets sourced from: [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/data)

---

This version assumes that users will have the necessary Python environment with pandas, numpy, sklearn, seaborn, and matplotlib installed already.
