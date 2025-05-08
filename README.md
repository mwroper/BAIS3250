# BAIS3250
Final project for data wrangling 

# Files
- **Data** folder contains all the data, with readme explaination
- **MWRoper_DW_Final.ipynb** is the final analysis conducted
- **MWRoper_Project.ipynb** is the initial web scrapping, cleaning, integrating, and first attempts at analysis.
- **MWRoper_Project_DW.pptx** is the power point for project check in

# Project: Analyzing the Relationship Between Critical Acclaim and Box Office Success in Films

This project explores the connection between a film's critical reception (IMDb ratings, Metacritic scores) and its commercial success (global box office earnings). It aims to understand if highly-rated films consistently earn more, how genre impacts profitability and ratings, and whether the relationship between critical and commercial success has changed over time.

## Data Sources

* **IMDb Top 1000 Rated Movies:** A dataset containing metadata for top-rated films (ratings, genres, runtime, etc.).
* **Box Office Mojo Top Worldwide Grossing Films:** Data scraped from [Box Office Mojo](https://www.boxofficemojo.com/) containing the top 1,000 movies ranked by lifetime global gross earnings.

## Data Dictionary

| Field          | Type    | Description                             | Dataset         |
|----------------|---------|-----------------------------------------|-----------------|
| Rank           | Numeric | Movie's rank by global gross earnings | Box Office Mojo |
| Title          | Text    | Movie title                             | Both            |
| Lifetime Gross | Text    | Worldwide earnings (e.g., "$2.9B")    | Box Office Mojo |
| Year           | Numeric | Release year                            | Both            |
| IMDB_Rating    | Numeric | IMDb user rating (0-10)                 | IMDb            |
| Genre          | Text    | Genres (e.g., "Action, Drama")          | IMDb            |
| Runtime        | Numeric | Duration in minutes                     | IMDb            |
| Certificate    | Text    | Content rating (e.g., "PG-13")          | IMDb            |

## Analysis

The analysis involves:

1.  **Data Integration:** Merging the IMDb and Box Office Mojo datasets.
2.  **Descriptive Analytics:** Calculating correlations between ratings and earnings, analyzing performance by genre, and examining trends over time.
3.  **Visualization:** Using scatter plots, bar charts, and line graphs to illustrate findings.

## Tools

* Python
* Libraries: pandas, seaborn, matplotlib, scipy

## Goal

The project aims to provide actionable insights for data-driven decision-making in film production and marketing by uncovering patterns linking artistic merit and financial success. All code, data, and visualizations are intended to be shared via Jupyter notebooks.
