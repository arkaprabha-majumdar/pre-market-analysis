# Stock Market News - Daily Sentiment Analysis

## Overview

I have been trading in Indian markets for quite some time, and one daily task on the weekdays is looking at the news to look for positive/negative sentiments that can affect prices. So I made this.
This Python script automatically fetches news articles related to factors that can influence the stock market, such as global news, crude oil prices, gold prices, and US bond updates, using the News API. It then performs sentiment analysis on the articles, categorizing them as positive or negative, and visualizes the sentiment distribution as a histogram. Additionally, the script provides updated percentage changes in international stock indices like the Dow Jones.

## Features

- Automatic retrieval of news articles using the News API.
- Sentiment analysis to classify articles as positive or negative.
- Visualization of sentiment distribution as a histogram.
- Real-time percentage change updates for international stock indices.
- Easy-to-use and customizable code for your needs.

## Requirements

Before running the script, ensure you have the following dependencies installed:

- Python 3
- [News API](https://newsapi.org/) account with API key
- Required Python packages (install with `pip install`):
  - requests
  - newsapi-python (pip install newsapi-python)
  - nltk
  - matplotlib

## Usage

1. Clone this repository to your local machine.
2. Install the required packages using `pip install`.
3. Replace `YOUR_API_KEY` in the script with your News API key.
4. Customize the keywords and sources as needed to target specific news topics.
5. Run the script using `python main.py`.

## Sample Output

After running the script, you will see the following outputs:

- A histogram showing the sentiment distribution of fetched news articles.
- Real-time updates on the percentage changes in international stock indices like the Dow Jones.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [News API](https://newsapi.org/) for providing access to news articles.
- [NLTK](https://www.nltk.org/_modules/nltk/sentiment/vader.html) for sentiment analysis.
- [matplotlib](https://matplotlib.org/) for data visualization.

## Author

[ARKAPRABHA MAJUMDAR](https://www.linkedin.com/in/arkaprabha-majumdar/)

## Contact

For any questions or suggestions, please feel free to contact me on LinkedIn.

Happy analyzing!
