# 🎬 Letterboxd Movie Classification & Analysis
This project explores and classifies movies based on user ratings and metadata collected from the Letterboxd movie platform. It focuses on analyzing viewer behavior, exploring genre trends, and building a machine learning model to predict whether a movie will be rated highly or not.

## Dataset
### From kaggle made by Sahil Islam007: [kaggle](https://www.kaggle.com/datasets/sahilislam007/letterbox-movie-classification-dataset)

### Description made by datasets author

- Film_title String The title of the movie.
- Director String The primary director(s) of the movie. Multiple directors are listed together.
- Average_rating Float The average user rating for the movie (on a scale of 1 to 5).
- Genres List A list of genres associated with the movie (e.g., ['Horror', 'Drama']).
- Runtime Float The runtime of the movie in minutes.
- Original_language String The runtime of the movie in minutes.
- Description String A brief synopsis or description of the movie’s plot or theme.
- Studios List A list of production studios associated with the movie.
- Watches Integer The total number of times the movie has been watched by users.
- List_appearances Integer The number of times the movie appears in user-curated lists.
- Likes Integer The total number of likes the movie has received from users.
- Fans Integer The number of users who have marked themselves as fans of the movie.
- Lowest★ Integer The number of 1-star ratings the movie has received.
- Medium★★★ Integer The number of 3-star ratings the movie has received.
- Highest★★★★★ Integer The number of 5-star ratings the movie has received.
- Total_ratings Integer The total number of ratings (across all star levels) for the movie.


### Dataset licence: CC0


## 📌 Project Goals
- Perform Exploratory Data Analysis (EDA) on Letterboxd movie data.

- Clean and preprocess metadata and ratings for classification.

- Use machine learning models to predict whether a movie is "liked" (e.g., average rating ≥ 3.5).

- Visualize relationships between movie attributes (genres, release year, etc.) and user ratings.

## 📁 Project Structure
```
Letterbox_Movie_Classification_Analysis.ipynb  # Main Jupyter notebook with code and explanations

README.md                                      # Project overview and instructions
```
## 🧪 Features & Analysis
- EDA on:

  - Popular genres

  - Yearly trends in film ratings

  - Distributions of average ratings

- Data preprocessing:

  - Handling missing values

  - Encoding categorical variables (e.g., genre, director)

- Classification using:

  - Logistic Regression

  - Decision Trees

  - Random Forest

  - Model evaluation with accuracy, confusion matrix, etc.

## 📊 Technologies Used
- Python 3

- Pandas, NumPy

- Matplotlib, Seaborn

- Scikit-learn

- Jupyter Notebook
