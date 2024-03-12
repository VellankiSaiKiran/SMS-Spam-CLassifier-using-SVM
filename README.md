# SMS Spam Classifier

This project is focused on building a classifier to distinguish between spam and non-spam (ham) SMS messages using various data preprocessing and machine learning techniques.

## Overview

The SMS Spam Classifier is developed in a Jupyter Notebook and follows a series of steps to process and analyze the text data, ultimately building a machine learning model capable of accurately classifying SMS messages. The project encompasses data loading, cleaning, feature extraction, model building, and evaluation.

## Contents

1. **Loading the Data**: Importing the dataset and initial examination.
2. **Removing Null Valued Columns**: Cleaning the dataset by removing any columns with null values.
3. **Labelling the Y Column**: Preparing the target variable for model training.
4. **Cleaning the Text Column**: Preprocessing the SMS messages, including removing special characters and stopwords.
5. **Splitting the Test and Train Data**: Dividing the dataset into training and testing sets.
6. **Tokenization and Stemming**: Breaking down the messages into tokens and reducing words to their root forms.
7. **Vectorization**: Transforming text data into numerical format using vectorization techniques for model training.
8. **Balancing the Data**: Addressing any imbalances in the dataset to improve model performance.
9. **Scaling the Data Using Min Max Scaler**: Normalizing the features to scale the data.
10. **SVM Before Feature Selection**: Training and evaluating a Support Vector Machine model before applying feature selection techniques.
11. **Feature Selection Using Variance Threshold**: Applying the Variance Threshold method to select relevant features.
12. **Model After Variance Threshold Feature Selection**: Evaluating the SVM model performance after applying Variance Threshold for feature selection.
13. **Feature Selection Using Chi-square**: Implementing Chi-square test for feature selection to improve model accuracy.
14. **Model After Chi-squared Test Feature Selection**: Assessing the impact of Chi-square feature selection on the SVM model.
15. **Conclusion**: Summarizing the findings, model performance, and potential areas for further research or improvement.

## How to Run

To run this notebook:

1. Ensure you have Jupyter Notebook or JupyterLab installed. If not, you can install it via Anaconda or pip.
2. Clone this repository or download the `SMS_Spam_Classifier.ipynb` file to your local machine.
3. Open the notebook in Jupyter and execute the cells sequentially to observe the process and results.

## Requirements

The project requires Python 3.x and the following libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- nltk

You can install these packages using pip:

```sh
pip install pandas numpy scikit-learn matplotlib seaborn nltk
