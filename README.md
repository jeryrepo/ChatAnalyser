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

  ### Power BI Dashboard
1. Open Power BI.
2. Import the cleaned DataFrame from the Python script.
3. Utilize the pre-built visualizations in the Power BI dashboard file (`ChatAnalyserDash.pbix`) for comprehensive insights.
4. Customize the dashboard based on your specific analysis needs.

## Results
- user_message: The original message with user information.
- user: Extracted user information.
- message: The cleaned message content.
- date: The date of the message.
- time: The time of the message.
- hour: The hour of the message.
- year: The year of the message.
- month: The month of the message.
- day: The day of the message.
- minute: The minute of the message.
- cleaned_message: The cleaned and processed message content.
- sentiment_score: The sentiment score of the message.
- sentiment_category: The sentiment category (positive, negative, neutral) based on the sentiment score.


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
