# Amazon_Sentiment_Analysis

# Sentiment Analysis with Multinomial Naive Bayes
This project demonstrates sentiment analysis using the Multinomial Naive Bayes classifier. It analyzes the sentiment of text data, specifically Amazon product reviews, and classifies them into positive, negative, or neutral categories.

## Dataset
The dataset used in this project contains Amazon product reviews with sentiment labels. The dataset should be in CSV format with at least two columns: 'Text' containing the text of the reviews and 'Sentiment' containing the sentiment labels (e.g., 'Positive', 'Negative', 'Neutral').

## Usage
1. **Prerequisites**: Ensure you have Python and the required libraries (scikit-learn, pandas) installed.

2. **Data Preparation**:
   - Replace 'your_dataset.csv' in the code with the path to your dataset.
   - Ensure that your dataset includes 'Text' and 'Sentiment' columns.

3. **Run the Code**: Execute the Python code provided in the script for training and evaluating the Multinomial Naive Bayes model.

4. **Model Evaluation**: The code will display the accuracy of the model and a detailed classification report that includes precision, recall, F1-score, and support for each sentiment class.

5. **Experiment and Customize**: Feel free to experiment with different hyperparameters, feature extraction techniques, or other machine learning models to improve sentiment analysis performance.

## Dependencies

- Python 3.x
- scikit-learn
- pandas
