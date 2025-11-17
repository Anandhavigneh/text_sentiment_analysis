Overview

This project demonstrates a basic sentiment analysis script using the TextBlob library in Python. The script analyses a given text input and determines whether the sentiment is positive, negative, or neutral.

How It Works

The script imports TextBlob from the textblob library.

A sample text string is defined.

TextBlob analyses the text and calculates its sentiment polarity.

Based on the polarity value, the script prints one of the following:

positive sentiment

negative sentiment

neutral sentiment

Sentiment Polarity

Polarity ranges from -1.0 to 1.0

Positive values indicate positive sentiment

Negative values indicate negative sentiment

Zero indicates neutral sentiment

Requirements

Install the required library before running the script:

pip install textblob


You may also need to download TextBlob's corpora:

python -m textblob.download_corpora

Running the Script

Run the Python file using:

python python.py


The output will display the sentiment classification based on the text provided in the script.

File Description

python.py
Contains the sentiment analysis logic using TextBlob.