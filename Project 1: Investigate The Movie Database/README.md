# Project: Investigate TMDb Movie Database

## About the project
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. The author has always been interested in movies and this dataset seems ideal opportunity to combine my love for Movies and Data Analytics.

## What needs to be done
Analyze data and create visualizations to share insights.

### Files
This project contains 3 files

`tmdb-movies.csv` : The dataset file containing 10k+ entries of movies downloaded from Kaggle.
- `Investigate_a_dataset.ipynb` : The investigation of the dataset has been done in this jupyter notebook file.
- `Investigate_a_dataset.html` : Folder containing HTML and PDF file of notebook.

This data set contains information about 10,000 movies collected from The Movie Database (TMDb). Contains data such as title, cast, director, runtime, budget, revenue, release year etc.

**Dataset Details**
Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
There are some odd characters in the ‘cast’ column. Nothing to care much of, I leave them as is.
The final two columns ending with “_adj" show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

**Loading Project**

Requirements:

This project requires Python 3 and the following Python libraries installed:
- Python 3.6.5
- NumPy
- Pandas
- matplotlib
- seaborn

**Limitations:**

**All results are limited to the underlying data set and no advaned statistics were performed. One of the major limitations that has to be taken into consideration is that many entries in the dataset have been removed due to missing data. Thus, the results can only be treated as indicators and are not generalizable.**
