# movie-recommender-system-tmdb-dataset
A content based movie recommender system using cosine similarity
## Key Features
Utilizes cosine similarity for content-based recommendations

### Feature engineering using:

#### i. Movie genres

#### ii. Cast and crew

#### iii. Keywords and overview text

#### Data cleaning and preprocessing from TMDB dataset

#### Clean and simple interface for selecting a movie and receiving recommendations

## 🛠 Technologies Used
#### Python

#### Pandas, NumPy

#### Scikit-learn (TF-IDF, CountVectorizer, cosine similarity)

#### NLTK for text preprocessing

#### TMDB 5000 Movies Dataset

## 📊 How It Works
#### Combine relevant features into a single string.

#### Vectorize the combined text using CountVectorizer.

#### Calculate the cosine similarity between all movie vectors.

#### When a user selects a movie, return the top 5 most similar movies based on the similarity score.
