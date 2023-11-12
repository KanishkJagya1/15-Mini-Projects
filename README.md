# Project Repository

This repository contains various projects related to computer vision, natural language processing, and machine learning.

## Table of Contents

1. [Image-processing (Hand Sign Recognition)](./Image-processing%20(Hand%20Sign%20Recognition))
2. [Chatbot using Python, HTML, and CSS](./chatbot%20using%20python,%20Html%20and%20css)
3. [Stock Price Prediction](./stock%20price%20prediction)
4. [Twitter Sentiment Analysis](./twitter%20sentiment%20analysis)
5. [SMS Spam Detection using NLP](./SMS%20spam%20detection%20using%20NLP)
6. [Resume Reader NLP](./resume%20reader%20NLP)
7. [Movie Review System NLP](./movie%20review%20system%20NLP)
8. [Human Activity Recognition](./Human%20Activity%20Recognition)
9. [Flower Recognition](./flower%20recognition)

## Folder Details

### 1. Image-processing (Hand Sign Recognition)

- **Data:**
  - `data/`: Directory containing datasets related to hand sign images.

### 2. Chatbot using Python, HTML, and CSS

- **Excluded Files/Directories:**
  - `venv/`: Directory containing Python virtual environment files.
  - `requirements.txt`: File listing Python package dependencies.

### 3. Stock Price Prediction

- **Data:**
  - `stonks.csv`: File containing stock price data.

### 4. Twitter Sentiment Analysis

- **Data:**
  - `Sentiment.csv`: File containing sentiment analysis data related to Twitter.

### 5. SMS Spam Detection using NLP

- **Data:**
  - `summary.csv`: File containing data related to SMS messages and their classification.

### 6. Resume Reader NLP

- **Data:**
  - `UpdatedResumeDataSet.csv`: File containing a dataset of resumes for NLP tasks.

### 7. Movie Review System NLP

- **Excluded Files/Directories:**
  - `bow.pkl`: File containing a Bag of Words model for sentiment analysis.
  - `model1.pkl`: File containing a trained sentiment analysis model.
  - `IMDB-Dataset.csv`: File containing the IMDB dataset for movie reviews.

### 8. Human Activity Recognition

- **Data:**
  - `test.csv`: File containing test data for human activity recognition.
  - `train.csv`: File containing training data for human activity recognition.

### 9. Flower Recognition

- **Data:**
  - `flowers/`: Directory containing images of flowers for training a recognition model.

## Setting Up Virtual Environment

For projects that use a virtual environment, follow these steps:

1. Navigate to the project folder.
2. Open a terminal or command prompt.
3. Create a virtual environment:
    ```bash
    virtualenv venv
    ```
4. Activate the virtual environment:
    - On Windows:
      ```bash
      .\venv\Scripts\activate
      ```
    - On Unix or MacOS:
      ```bash
      source venv/bin/activate
      ```
5. Install the required modules:
    ```bash
    pip install -r requirements.txt
    ```
6. Remember to deactivate the virtual environment when you're done:
    ```bash
    deactivate
    ```

Feel free to explore each project folder for more details on algorithms, datasets, and usage instructions.
