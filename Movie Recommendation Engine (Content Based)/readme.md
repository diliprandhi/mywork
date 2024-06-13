# Movie Recommendation Engine (Content Based)

## Summary:
The Movie Recommendation Engine is a content-based recommendation system designed to provide personalized movie suggestions based on user preferences. Utilizing a dataset of over 4,600 movies, the project employs TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to transform textual data from movie genres into meaningful feature vectors. By calculating cosine similarities between these vectors, the system identifies and recommends movies with similar genre profiles to those previously enjoyed by the user.

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
