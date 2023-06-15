Text Classification using Logistic Regression and Random Forest

This project demonstrates text classification using logistic regression and random forest classifiers. The goal is to classify text data into predefined categories based on the content.
Project Structure

The project contains the following files:

    train.csv: The dataset containing text data and corresponding labels for training the models.
    text_classification.ipynb: Jupyter Notebook file that includes the code for data preprocessing, model training, and evaluation.
    classification_report_rf.csv: The classification report for the random forest model.
    submission2.csv: The submission file containing the predicted sale prices.

Prerequisites

To run the project, make sure you have the following dependencies installed:

    pandas
    numpy
    nltk
    sklearn

Install the required libraries using the following command:

shell

pip install pandas numpy nltk scikit-learn

Additionally, download the NLTK data by running the following commands:

python

import nltk

nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')
nltk.download('punkt')

Usage

    Clone the repository to your local machine.
    Ensure that the train.csv file is located in the project directory.
    Open the text_classification.ipynb notebook using Jupyter Notebook or any compatible environment.
    Run the notebook cells sequentially to preprocess the data, train the models, and generate the classification report.
    The classification report for the random forest model will be saved as classification_report_rf.csv in the project directory.
    The predicted sale prices will be saved as submission2.csv.

Feel free to explore the code and modify it according to your requirements.
