# IMDb Data Mining & Movie Analytics

This project demonstrates how to mine, clean, analyze, and visualize movie data from IMDb using Python. It is designed for aspiring data analysts to showcase their skills in data wrangling, exploratory analysis, and visualization.

## Project Structure

- **imdb_data_mining_upload.ipynb**  
  Google Colab/Jupyter Notebook for interactive analysis.  
  **Features:**
  - Lets you upload your own IMDb dataset (`Top_1000_IMDB_Movies.csv` or similar)
  - Cleans and preprocesses the data (handles missing values, standardizes genres, ratings, box office)
  - Performs exploratory data analysis (EDA) on genres, ratings, box office, etc.
  - Visualizes insights using matplotlib and seaborn

## Getting Started

### 1. Upload Your Dataset

- The notebook is designed to work with a CSV file containing IMDb movie data.
- Example columns: `Name of movie`, `Year of relase`, `Genre`, `Movie Rating`, `Gross collection`, `Director`, `Star`, etc.
- Use the file upload cell in the notebook to select your CSV file.

### 2. Data Cleaning & Preparation

- The notebook will automatically:
  - Standardize genre names
  - Convert ratings and box office to numeric formats
  - Handle missing or inconsistent values

### 3. Analysis & Visualization

- Explore trends in genre popularity, ratings over time, and highest-grossing movies.
- Visualize key findings with bar plots, line plots, and scatter plots.
- Extend the notebook with your own analyses (e.g., director stats, genre trends by decade).

## Example Visualizations

- **Top Genres:** Bar chart of most frequent genres in the dataset
- **Ratings Over Time:** Line plot of IMDb ratings by year
- **Highest-Grossing Movies:** Horizontal bar chart of movies by box office collection
- **Rating vs Box Office:** Scatter plot showing correlation

## How to Use

1. **Open the notebook** in Google Colab or JupyterLab.
2. **Upload your IMDb CSV dataset** using the upload cell.
3. **Run all cells** to clean, analyze, and visualize the data.
4. **Modify or extend the notebook** for deeper insights.

## Requirements

- Python 3
- pandas
- matplotlib
- seaborn

All required packages are installed automatically in Google Colab.

## For Your Portfolio

- Document your workflow clearly in the notebook.
- Save and share your findings, code, and visualizations.
- Export cleaned data for use in Tableau, Power BI, or other BI tools.

## License

This project is released under the MIT License.

---

**Created by Jateen Ramteke**
