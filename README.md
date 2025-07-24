# News Aggregator

A simple Flask web application that fetches and displays news articles using the NewsAPI. Users can search for news by keyword and view the latest articles in a clean, Bootstrap-styled interface.

## Features

- Search for news articles by keyword
- Filters out articles with "removed" in the title
- Responsive design using Bootstrap

## Installation

1. **Clone the repository:**

- git clone https://github.com/yourusername/News.git cd News

2. **Create and activate a virtual environment:**

`` python -m venv .venv .venv\Scripts\activate ``

3. **Install dependencies:**

`` pip install -r requirements.txt ``

4. **Set up NewsAPI key:**
   - Add your NewsAPI key to `config.py` as `NEWS_API_KEY = "your_api_key"`

## Usage

1. **Run the application:**

`` python app.py ``

2. **Open your browser and go to:**

`` http://127.0.0.1:5000 ``

3. **Search for news:**
   - Use the search bar to enter keywords and view relevant articles.

## Configuration

- `config.py`: Store your NewsAPI key here.
- `static/`: Contains CSS and Bootstrap files.
- `templates/`: HTML templates for rendering pages.

