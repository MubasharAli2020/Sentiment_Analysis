# Movie Reviews Sentiment Analysis

This project analyzes movie reviews to determine whether they are positive or negative using Natural Language Processing (NLP) techniques. The analysis is performed using Python in Google Colab.

## Table of Contents

-   Introduction
-   Setup
-   Data Preprocessing
-   Model Training
-   Sentiment Prediction
-   Word Cloud Generation
    -   Negative Words
    -   Positive Words
-   Results
-   Deployment
-   Conclusion

## Introduction

The goal of this project is to classify movie reviews as positive or negative. We use Natural Language Processing (NLP) techniques to preprocess the text data, train a sentiment analysis model, and visualize the most common positive and negative words using word clouds.

## Setup

1.  **Environment**: The project is developed in Google Colab.
2.  **Libraries**: The following Python libraries are used:
    -   pandas
    -   numpy
    -   nltk
    -   scikit-learn
    -   wordcloud
    -   matplotlib

## Data Preprocessing

1.  **Load Data**: The movie reviews are loaded from a CSV file.
2.  **Text Cleaning**: The reviews are cleaned by:
    -   Tokenizing the text
    -   Converting to lowercase
    -   Removing punctuation and stopwords

## Model Training

1.  **Data Splitting**: The cleaned reviews are split into training and testing sets.
2.  **Vectorization**: The text data is converted into numerical format using CountVectorizer.
3.  **Classifier**: A Naive Bayes classifier is trained on the vectorized text data.
4.  **Evaluation**: The model’s accuracy is evaluated on the test set.

## Sentiment Prediction

1.  **Predict Sentiment**: The trained model is used to predict the sentiment of new reviews.
2.  **Add Predictions**: The predicted sentiments are added to the DataFrame.

## Word Cloud Generation

### Negative Words

1.  **Filter Negative Reviews**: Extract reviews predicted as negative.
2.  **Extract Negative Words**: Use the opinion lexicon to filter out negative words.
3.  **Generate Word Cloud**: Create a word cloud to visualize the most common negative words.

### Positive Words

1.  **Filter Positive Reviews**: Extract reviews predicted as positive.
2.  **Extract Positive Words**: Use the opinion lexicon to filter out positive words.
3.  **Generate Word Cloud**: Create a word cloud to visualize the most common positive words.

## Results

-   **Accuracy**: The model’s accuracy on the test set.
-   **Word Clouds**: Visualizations of the most common positive and negative words.

## Deployment

To deploy the notebook to GitHub directly from Google Colab:

1.  **Save Your Notebook**: Ensure your notebook is saved in Google Colab.
2.  **Share to GitHub**:
    -   Click on  **File**  in the top menu.
    -   Select  **Save a copy in GitHub**.
    -   Select your repository (`MubasharAli2020/Sentiment_Analysis`) and the branch (`main`  or  `master`).
    -   Enter a commit message, for example, “Add sentiment analysis notebook”.
    -   Click  **OK**  to push the notebook to your GitHub repository.

## Conclusion

This project demonstrates how to use NLP techniques to analyze movie reviews and classify them as positive or negative. The word clouds provide a visual representation of the most common words in positive and negative reviews, offering insights into the language used in different types of reviews.
