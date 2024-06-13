# Movie Recommendation Engine (Content Based)

## Summary:
The Movie Recommendation Engine project is designed to provide personalized movie suggestions based on user preferences. This content-based recommendation system leverages movie metadata, particularly genres, to recommend movies similar to those a user has shown interest in.

## Detailed Description:
The project starts with extensive data preprocessing, which includes handling missing values and cleaning the dataset to ensure quality data. The core of the recommendation system relies on transforming movie genre data into numerical format using TF-IDF vectorization. This transformation allows for the calculation of cosine similarities between movies, enabling the recommendation of similar movies.

### Features:
- Data preprocessing to handle missing values and clean the dataset.
- Implementation of TF-IDF vectorization to convert genre text into numerical features.
- Calculation of cosine similarity to find movies with the most similar genre vectors.
- User-friendly interface for receiving movie recommendations based on input preferences.

### Technologies Used:
- Python (Pandas, NumPy)
- Scikit-learn for TF-IDF vectorization and similarity calculation

### Usage:
Clone the repository, install the required libraries, and run the script to receive movie recommendations based on your favorite genres.
