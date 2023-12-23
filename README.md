![SharedScreenshot](https://github.com/jeryrepo/ChatAnalyser/assets/142509067/d76efd26-cc6d-473e-b4ae-c6479fd284db)

# WhatsApp Chat Analysis

This project is designed to analyze WhatsApp chat logs. It performs data cleaning, sentiment analysis, and organizes the results in a structured format for further analysis or visualization.

## Features

- **Data Cleaning:** Handles ambiguous column names, date column handling, deals with missing date values, handles format issues, and standardizes the gender format.
- **Sentiment Analysis:** Uses NLTK's Vader SentimentIntensityAnalyzer to calculate the sentiment score of each cleaned message.
- **Data Extraction:** Extracts messages and dates from the chat log using regular expressions.
- **Data Processing:** Creates a pandas DataFrame with the extracted data and additional columns for the user, message, date, time, hour, year, month, day, and minute.
- **Data Analysis:** The analysis is performed using pandas, a powerful data analysis and manipulation library.
- **Dashboard Creation:** Each analysis is exported into CSV format and a dashboard is created using PowerBI for visual representation of the analysis.

## How to Use

1. Clone this repository.
2. Install the required libraries mentioned in requirements.txt.
3. Run the Python script on your WhatsApp chat log.

## Results

The script returns a pandas DataFrame with all the processed data, including the sentiment score and sentiment category for each message. The analysis is then visualized using a PowerBI dashboard.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
