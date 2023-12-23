# WhatsApp Chat Analysis

This project is designed to analyze WhatsApp chat logs. It performs data cleaning, sentiment analysis, and organizes the results in a structured format for further analysis or visualization.

## Features

- Data Cleaning: Handles ambiguous column names, date column handling, deals with missing date values, handles format issues, and standardizes the gender format.
- Sentiment Analysis: Uses NLTK's Vader SentimentIntensityAnalyzer to calculate the sentiment score of each cleaned message.
- Data Extraction: Extracts messages and dates from the chat log using regular expressions.
- Data Processing: Creates a pandas DataFrame with the extracted data and additional columns for the user, message, date, time, hour, year, month, day, and minute.

## How to Use

1. Clone this repository.
2. Install the required libraries.
3. Run the Python script on your WhatsApp chat log.

## Dependencies
Before running the script, ensure you have the following dependencies installed:
- pandas
- nltk
- matplotlib
- wordcloud
- emoji
- seaborn

## Results

The script returns a pandas DataFrame with all the processed data, including the sentiment score and sentiment category for each message.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
