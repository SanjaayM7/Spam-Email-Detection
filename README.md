# Spam Detection Project

This project demonstrates a simple spam detection system using Python and machine learning. It utilizes a Naive Bayes classifier trained on a dataset of emails to classify emails as either spam or ham (not spam).

## Dataset

The project uses the following datasets:

- **easy_ham:** A collection of legitimate emails.
- **hard_ham:** A collection of legitimate emails that are more difficult to classify.
- **spam:** A collection of spam emails.

These datasets are extracted from tar.bz2 files and preprocessed before training the classifier.

## Methodology

1. **Data Loading and Preprocessing:** The datasets are loaded, and emails are extracted from the files.
2. **Feature Extraction:** TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert the text data into numerical features.
3. **Model Training:** A Naive Bayes classifier is trained on the extracted features and labeled data.
4. **Model Evaluation:** The trained model is evaluated using metrics such as accuracy, precision, recall, and F1 score.
5. **Prediction:** The model is used to predict whether new emails are spam or ham.

## Requirements

- Python 3.x
- scikit-learn
- pandas
- email
- tarfile
- glob
- numpy

To install the necessary libraries, you can use pip:

## Usage

1. Download the datasets and place them in the project directory.
2. Run the Python script to train the model and evaluate its performance.
3. Modify the script to predict on new emails.

## Results

The model achieves a high accuracy in classifying spam and ham emails. The evaluation metrics are printed to the console.

## Contributing

Feel free to contribute to this project by improving the model, adding new features, or enhancing the documentation.
