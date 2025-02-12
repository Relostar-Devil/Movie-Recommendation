# Netflix-Prize-Recommendation-SVD

## Overview
Using Singular Value Decomposition (SVD), this project builds a collaborative filtering recommendation system based on the Netflix Prize dataset. It predicts user ratings and generates personalized movie recommendations by decomposing the user-movie ratings matrix into latent features.

## Dataset
- **combined_data_1.txt:** Contains the historical user ratings.
- **movie_titles.csv:** Provides movie title information.  
Both files are sourced from the Netflix Prize data on Kaggle.

- Datasets Links:
  
  [https://www.kaggle.com/datasets/netflixinc/netflixprizedataresource=download&select=combined_data_1](https://www.kaggle.com/datasets/netflixinc/netflixprizedataresource=download&select=combined_data_1)
  
  [https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data?resource=download&select=movie_titles.csv](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data?resource=download&select=movie_titles.csv)

## Methodology
- **Data Loading:** Import data using Pandas from text and CSV files.
- **Data Preprocessing:** Clean and merge datasets to form a unified user-movie ratings matrix.
- **SVD Modeling:** Decompose the ratings matrix to extract latent factors for users and movies.
- **Evaluation:** Compare predicted ratings with actual ratings to assess model performance.
- **Visualization:** Use Matplotlib to visualize data distributions and model insights.

## Conclusion
This repository demonstrates an effective application of SVD for building a recommendation system using the Netflix Prize dataset, providing insights into collaborative filtering and latent factor analysis.
