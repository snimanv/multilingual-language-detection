## Multilingual Language Detection
This project is a multilingual language detection system that uses a Naive Bayes algorithm (MultinomialNB) to identify the language of a given text. The project includes a Flask application for easy interaction with the language detection model.

## Files and Folders
**templates/:** Contains the HTML and CSS files for the Flask web application.

index.html: The main interface for user interaction.

styles.css: The stylesheet for the web interface.

**Language Detection.csv:** The dataset containing text in multiple languages and their corresponding language names.

**Language Detector.ipynb:** Jupyter notebook used for training the language detection model.

**app.ipynb:** Jupyter notebook for creating and testing the Flask application.

**model.pkl:** The trained Naive Bayes model saved as a pickle file.

**tfidf_vectorizer.pkl:** The TF-IDF vectorizer used for text transformation saved as a pickle file.

**README.md:** This readme file.

## Model Training
The language detection model is trained using the Naive Bayes algorithm (MultinomialNB) on a dataset (Language Detection.csv) which contains columns of text in multiple languages and their corresponding language names. The model uses a TF-IDF vectorizer for text transformation.

## Flask Application
A Flask application is provided to interact with the language detection model. Users can input text through a web interface, and the application will detect and display the language of the text.
