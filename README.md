# Netflix Movie Data Analysis

An exploratory data analysis project using Python to investigate Netflix movies released during the 1990s.

## Project Overview

Netflix has grown from a DVD rental service into one of the world's largest entertainment platforms. This project explores Netflix movie data with a focus on movies released in the 1990s.

The analysis uses Python and Pandas to filter and investigate movie data, while Matplotlib is used to visualize movie-duration patterns.

## Objectives

- Explore Netflix movie data
- Filter the dataset to focus on movies
- Analyze movies released during the 1990s
- Investigate the distribution of movie durations
- Practice data filtering, manipulation, and visualization with Python

## Dataset

The project uses `netflix_data.csv`.

Important columns include:

| Column | Description |
|---|---|
| `show_id` | ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director |
| `cast` | Cast |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Release year |
| `duration` | Duration in minutes |
| `description` | Description |
| `genre` | Show genre |

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Analysis

The project includes:

1. Loading the Netflix dataset
2. Selecting movie titles from the dataset
3. Filtering movies released between 1990 and 1999
4. Visualizing the distribution of movie durations
5. Identifying patterns in 1990s movie data

## Visualization

The project includes a histogram showing the distribution of movie durations for movies released during the 1990s.

The analysis identified approximately **100 minutes** as the most common movie duration range.

## Key Learning

This project demonstrates practical skills in:

- Data loading
- DataFrame filtering
- Conditional selection
- Exploratory Data Analysis (EDA)
- Data visualization
- Working with real-world entertainment data

## Project Structure

```text
Netflix-Movie-Data-Analysis/
│
├── netflix_data.csv
├── netflix_movie_analysis.ipynb
├── redpopcorn.jpg
└── README.md
