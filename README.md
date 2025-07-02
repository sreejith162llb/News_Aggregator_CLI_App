News Aggregator CLI App

Description

A Python CLI app that pulls the latest headlines from [NewsAPI](https://newsapi.org). Users can view top headlines, filter by news category, or search by keywords directly from the terminal.

Features

- View top news headlines
- Filter by categories: business, entertainment, sports, etc.
- Search by custom keyword
- Real-time updates from NewsAPI

Technologies

- Python 3.x
- requests
- NewsAPI

Getting Started

1. # Create and activate a virtual environment
2. ```bash
3. python -m venv .venv

4. # Windows
5. .\.venv\Scripts\activate
6. # macOS/Linux
7. source .venv/bin/activate

Install dependencies

pip install -r requirements.txt

Run the app

python news_aggregator.py

Requirements

requests

✅ Also requires a free API key from https://newsapi.org.

 Replace your_api_key_here in the code with your actual API key.
