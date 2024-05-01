# imdb_moviesanalysis
Movie Dataset Analysis

Introduction

This repository contains an analysis of a dataset consisting of 2000 movies, including IMDb ratings. The analysis includes data cleaning, visualization, and exploration of various aspects of the dataset.

Data Cleaning

- Identified and handled missing data:
  - Imputed missing values in the 'Metascore' column using the median value.
  - Dropped the 'Gross' column due to a large number of missing values (97).
- Cleaned the 'Release Year' column:
  - Removed rows with irregularities in the data, ensuring consistency.

Exploratory Data Analysis

- Distribution of IMDb ratings:
  - Utilized histograms to visualize the distribution of IMDb ratings among the movies.

- Top 10 rated movies:
  - Identified and displayed the top 10 highest-rated movies based on IMDb ratings.

- Visualizations:
  - Created scatter plots to explore relationships between variables.
  - Generated line graphs to visualize trends over time.

Conclusion

This analysis provides insights into the movie dataset, including IMDb ratings, distribution, and trends over time. Further analysis could include more advanced statistical modeling and machine learning techniques to uncover deeper insights.

Repository Structure

- `imdb_top_2000_movies`: File containing the dataset.
- `movies`: File containing Python scripts used for data analysis.
- `README.md`: This file, providing an overview of the analysis and repository contents.

Dependencies

- Juypter Notebook
- Pandas
- Matplotlib


Usage
1.Download the files
3. Run the ipynb file to reproduce the analysis and generate visualizations.
