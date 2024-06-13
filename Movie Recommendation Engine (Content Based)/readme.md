# Movie Recommendation Engine (Content Based)

## Summary:
The Movie Recommendation Engine project is designed to provide personalized movie suggestions based on user preferences. This content-based recommendation system leverages movie metadata, particularly genres, to recommend movies similar to those a user has shown interest in.

## Detailed Description:
The project starts with extensive data preprocessing, which includes handling missing values and cleaning the dataset to ensure quality data. The core of the recommendation system relies on transforming movie genre data into numerical format using TF-IDF vectorization. This transformation allows for the calculation of cosine similarities between movies, enabling the recommendation of similar movies.

### Key Components:
**Data Preprocessing:**
- Handled missing values and cleaned the dataset for accuracy.
- Ensured data was in a suitable format for analysis.

**TF-IDF Vectorization:**
- Transformed movie genres into numerical feature vectors using TF-IDF (Term Frequency-Inverse Document Frequency).
- This method captures the importance of genre words within the dataset.

**Cosine Similarity Calculation:**
- Calculated cosine similarity between movie vectors to find movies with similar genre profiles.
- This similarity measure forms the basis for recommending movies.

### Technologies Used:
- Python: For data manipulation and processing.
- Pandas: For data cleaning and manipulation.
- NumPy: For numerical operations.
- Scikit-learn: For TF-IDF vectorization and similarity computation.

### Usage:
Clone the repository, install the required libraries, and run the script to receive movie recommendations based on your favorite genres.
