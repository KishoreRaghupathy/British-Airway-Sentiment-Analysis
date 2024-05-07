# British Airways Reviews Sentiment Analysis

This Python project scrapes airline reviews for British Airways from `airlinequality.com`, processes the review text, and analyzes sentiment using natural language processing (NLP) techniques. The analysis determines whether the sentiments of the reviews are positive, negative, or neutral.

## Features

- **Web Scraping**: Automatically scrape reviews from multiple pages.
- **Text Processing**: Clean and preprocess text data for analysis.
- **Sentiment Analysis**: Evaluate the sentiment of each review using the VADER sentiment analysis tool.
- **Data Visualization**: Visual representation of sentiment analysis results.
- **Data Storage**: Store processed data in a CSV file for further analysis.

## Installation

To run this project, you will need Python installed on your machine. Additionally, the following Python libraries are required:

- `requests`
- `BeautifulSoup` from `bs4`
- `pandas`
- `nltk`
- `matplotlib`
- `wordcloud`
- `vaderSentiment`

You can install these packages using pip:

```bash
pip install requests beautifulsoup4 pandas nltk matplotlib wordcloud vaderSentiment
```

Ensure you have the necessary NLTK data:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('omw-1.4')
nltk.download('averaged_perceptron_tagger')
```

## Usage

1. **Scraping Reviews**: The script starts by scraping reviews from the specified number of pages.
2. **Processing Text**: Cleans and preprocesses the text data to remove unwanted characters and split text.
3. **Analyzing Sentiment**: Uses VADER to analyze the sentiment of each processed review.
4. **Visualizing Data**: Plots pie charts and word clouds to represent the sentiment analysis results visually.
5. **Storing Results**: Outputs the results to a CSV file named `reviews_data1.csv`.

To run the script, navigate to the project directory and execute:

```bash
python script_name.py
```

Replace `script_name.py` with the name of your Python script.

## Results

The output will be a CSV file containing the reviews, their processed forms, sentiment scores, and sentiment classifications (Positive, Neutral, Negative). Additionally, visualizations like pie charts and word clouds will be displayed during the script execution, illustrating the distribution of sentiments and the most frequent words in the reviews.

## License

This project is free to use and modify for any personal or educational purposes.
