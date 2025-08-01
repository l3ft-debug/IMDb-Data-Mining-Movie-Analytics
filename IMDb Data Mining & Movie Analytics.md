Welcome to the IMDb Data Mining \& Movie Analytics project! This repository demonstrates how to extract, clean, and analyze movie data from IMDb to discover industry trends and insights.

## Overview

This project involves web scraping IMDb to collect details such as movie titles, genres, ratings, directors, actors, release years, and box office revenue. After cleaning the data, we explore patterns in genre popularity, movie ratings, and box office performance using Python and common data visualization tools.

## Features

- **Web Scraping:** Extracts movie details from IMDb.
- **Data Cleaning:** Handles missing values and corrects inconsistencies.
- **Analysis:** Performs exploratory data analytics on genres, ratings, and box office trends.
- **Visualization:** Uses Matplotlib, Seaborn, or Tableau/Power BI for clear, insightful visuals.


## Installation

1. Clone this repository:

```bash
git clone <repository_url>
cd imdb-data-mining
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```


## Usage

1. **Scrape Data:**
Run `scrape_imdb.py` to download raw movie data.

```bash
python scrape_imdb.py
```

2. **Clean Data:**
Use `clean_data.py` to preprocess the dataset.

```bash
python clean_data.py
```

3. **Analyze \& Visualize:**
Execute `analyze_visualize.ipynb` (Jupyter Notebook) to perform exploratory data analysis and generate plots.

## Project Structure

- `scrape_imdb.py` – Code for web scraping.
- `clean_data.py` – Data cleaning scripts.
- `analyze_visualize.ipynb` – EDA and visualizations.
- `README.md` – Project documentation.


## Key Insights

- What genres are rising or declining in popularity.
- How movie ratings vary by release year or other factors.
- Which attributes are linked to box office success.


## Skills Practiced

- Web Scraping (BeautifulSoup/Scrapy)
- Data Cleaning \& Preparation
- Statistical Analysis
- Data Visualization


## License

This project is for learning and portfolio purposes. Check IMDb usage policies before redistributing scraped data.

## Contact

For questions or collaboration, open an issue or reach out via email.

Happy analyzing!

