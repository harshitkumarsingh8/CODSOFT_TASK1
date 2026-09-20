# Movie Genre Classification

## CodSoft Machine Learning Internship - Task 1

This project is developed as part of the CodSoft Machine Learning Internship.

The objective of this project is to classify movies into different genres based on their plot descriptions using Natural Language Processing (NLP) and Machine Learning.

## Project Overview

Movie descriptions are converted into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency). A Logistic Regression classifier is then trained to predict the genre of a movie.

## Dataset

- Dataset: Genre Classification Dataset IMDb
- Total Movies: 54,214
- Number of Genres: 27
- Input Feature: Movie Description
- Target: Movie Genre

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Google Colab

## Machine Learning Workflow

1. Dataset loading
2. Data cleaning
3. Missing value checking
4. Duplicate handling
5. Text preprocessing
6. Train-test split
7. TF-IDF vectorization
8. Logistic Regression model training
9. Model evaluation
10. Genre prediction on new movie descriptions
11. Model and vectorizer saving

## Model

### Logistic Regression

The Logistic Regression classifier is trained using TF-IDF features extracted from movie descriptions.

## Results

- Test Accuracy: **48.77%**
- Macro F1-score: **0.36**
- Weighted F1-score: **0.51**

The dataset contains 27 genres with an imbalanced distribution. Therefore, performance varies across different genres.

## Sample Predictions

The trained model was tested on new movie descriptions and successfully predicted genres such as:

- Mystery
- Sci-Fi
- Horror

The model may sometimes predict a different genre because movie descriptions can contain characteristics of multiple genres.

## Project Files

- `Movie_Genre_Classification_CODSOFT_TASK1.ipynb` - Complete Google Colab notebook
- `movie_genre_model.pkl` - Trained Logistic Regression model
- `tfidf_vectorizer.pkl` - Trained TF-IDF vectorizer

## Future Improvements

- Try other classification algorithms
- Perform hyperparameter tuning
- Improve text preprocessing
- Handle class imbalance
- Experiment with advanced NLP techniques
- Compare multiple machine learning models

## Author

**Harshit Kumar Singh**

BCA Student at Galgotias University  
Aspiring AI/ML Engineer

## Internship

**CodSoft Machine Learning Internship - September 2026 Batch**
