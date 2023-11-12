# Project Repository

This repository contains various projects related to computer vision, natural language processing, and more. Each project is stored in its respective folder. Below is an index providing an overview of each project.

## Index

| No. | Project Name                                         | Description                                            | Datasets and Models                                        |
| --- | ---------------------------------------------------- | ------------------------------------------------------ | ----------------------------------------------------------- |
| 1   | [Human Activity Recognition](./Human%20Activity%20Recognition) | Human activity recognition using sensor data.         | [Train Dataset](./Human%20Activity%20Recognition/train.csv), [Test Dataset](./Human%20Activity%20Recognition/test.csv) |
| 2   | [Image-processing (Hand Sign Recognition)](./Image-processing%20(Hand%20Sign%20Recognition)) | Hand sign recognition using image processing.         | [Hand Sign Images](./Image-processing%20(Hand%20Sign%20Recognition)/data) |
| 3   | [Live-subtitle Recorder](./Live-subtitle%20Recorder) | A project related to live subtitle recording.         | _(Add any specific details about the project)_              |
| 4   | [Python Calculator GUI](./Python%20Calculator%20GUI) | A simple calculator with a graphical user interface. | _(Add any specific details about the project)_              |
| 5   | [SMS Spam Detection using NLP](./SMS%20spam%20detection%20using%20NLP) | SMS spam detection using natural language processing. | [Summary Dataset](./SMS%20spam%20detection%20using%20NLP/summary.csv) |
| 6   | [Chatbot using Python, HTML, and CSS](./chatbot%20using%20python,%20Html%20and%20css) | A chatbot implementation using Python, HTML, and CSS. | [Virtual Environment](./chatbot%20using%20python,%20Html%20and%20css/venv), [Requirements File](./chatbot%20using%20python,%20Html%20and%20css/requirements.txt) |
| 7   | [Face Landmark Detection](./face%20Landmark%20detection) | Detection of facial landmarks.                        | [Raw Implementation](./face%20Landmark%20detection/raw.ipynb) |
| 8   | [Face Detection](./face%20detection)                 | Face detection using OpenCV.                          | _(Add any specific details about the project)_              |
| 9   | [Flower Recognition](./flower%20recognition)         | Recognition of flower species.                        | [Flower Images](./flower%20recognition/flowers)            |
| 10  | [Movie Review System using NLP](./movie%20review%20system%20NLP) | Sentiment analysis on movie reviews.                  | [IMDB Dataset](./movie%20review%20system%20NLP/IMDB-Dataset.csv), [Bag of Words Model](./movie%20review%20system%20NLP/bow.pkl), [Trained Model](./movie%20review%20system%20NLP/model1.pkl) |
| 11  | [Resume Reader using NLP](./resume%20reader%20NLP) | Extracting information from resumes using NLP.        | [Resume Dataset](./resume%20reader%20NLP/UpdatedResumeDataSet.csv) |
| 12  | [Spelling Correction using Python](./spelling%20correction%20using%20python) | A project related to spelling correction using Python. | _(Add any specific details about the project)_              |
| 13  | [Stock Price Prediction](./stock%20price%20prediction) | Predicting stock prices.                              | [Stock Prices Dataset](./stock%20price%20prediction/stonks.csv) |
| 14  | [Twitter Sentiment Analysis](./twitter%20sentiment%20analysis) | Analyzing sentiment on Twitter.                       | [Sentiment Dataset](./twitter%20sentiment%20analysis/Sentiment.csv) |
| 15  | [Weather Prediction](./weather%20prediction)         | _(Add a brief description of the project)_           | _(Add any specific details about the project)_              |

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

- **data:**
  - This directory contains datasets related to hand sign recognition.

### 2. Chatbot using Python, HTML, and CSS

- **venv:**
  - Excludes the virtual environment directory for the chatbot project.

- **requirements.txt:**
  - Excludes the `requirements.txt` file, which lists the required Python packages for the chatbot.

### 3. Stock Price Prediction

- **stonks.csv:**
  - Excludes the `stonks.csv` file, which contains stock price data for the stock price prediction project.

### 4. Twitter Sentiment Analysis

- **Sentiment.csv:**
  - Excludes the `Sentiment.csv` file, which contains sentiment analysis data related to Twitter for the Twitter sentiment analysis project.

### 5. SMS Spam Detection using NLP

- **summary.csv:**
  - Excludes the `summary.csv` file, which contains data related to SMS messages and their classification for the SMS spam detection project.

### 6. Resume Reader NLP

- **UpdatedResumeDataSet.csv:**
  - Excludes the `UpdatedResumeDataSet.csv` file, which contains a dataset of resumes for NLP tasks in the resume reader project.

### 7. Movie Review System NLP

- **bow.pkl:**
  - Excludes the `bow.pkl` file, which likely contains a Bag of Words model for sentiment analysis in the movie review system project.

- **model1.pkl:**
  - Excludes the `model1.pkl` file, which likely contains a trained sentiment analysis model for the movie review system project.

- **IMDB-Dataset.csv:**
  - Excludes the `IMDB-Dataset.csv` file, which contains the IMDB dataset for movie reviews in the movie review system project.

### 8. Human Activity Recognition

- **test.csv:**
  - Excludes the `test.csv` file, which contains test data for human activity recognition.

- **train.csv:**
  - Excludes the `train.csv` file, which contains training data for human activity recognition.

### 9. Flower Recognition

- **flowers/:**
  - Excludes the `flowers/` directory, which likely contains images of flowers for training a recognition model in the flower recognition project.

## Setting Up Virtual Environment

For projects that use a virtual environment, follow these steps:

1. Navigate to the project folder.
2. Open a terminal or command prompt.
3. Create a virtual environment:
    ```bash
    python -m venv venv
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

