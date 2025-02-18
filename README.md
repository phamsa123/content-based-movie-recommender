# Movie Recommendation System

## Overview
This is a content-based movie recommendation system that suggests movies based on user preferences. The system uses TF-IDF vectorization and cosine similarity to find similar movies based on their descriptions.

## Dataset
- The dataset used in this project is sourced from IMDb's Top 1000 Movies dataset.
- It contains movie titles, genres, IMDB ratings, and plot descriptions.
- The dataset file is included in this repository (`imdb_top_1000.csv`).
- How to Load: The dataset is automatically loaded into the system using `pandas`.

## Setup
Before running the system, install the required dependencies:
pip install -r requirements.txt
OR, install manually:
pip install pandas scikit-learn numpy ipywidgets

# How to Run Jupyter Notebook
- Open the Jupyter Notebook:

- Run all the cells in the notebook.
- Use the interactive widget to enter a movie description and get recommendations.
- How to Run (Python Script - CLI)
- Alternatively, you can run it as a script from the command line:

- python recommend.py "I love thrilling action movies set in space, with a comedic twist."
- Example Output
# User Input:
"I love thrilling action movies set in space, with a comedic twist."
# Top Recommended Movies:
Rank	Title	Genre	IMDB Rating	Description
1	Guardians of the Galaxy	Action, Sci-Fi	8.1	A fun space adventure with action and comedy.
2	Star Wars	Sci-Fi, Action	8.7	A classic space battle with adventure and humor.
3	The Fifth Element	Sci-Fi, Comedy	7.7	A futuristic action-comedy in space.

# Demo Video
A short video demonstrating the system is available here (Replace # with your video link).

# Technologies Used
Python
Pandas (for data processing)
Scikit-learn (for TF-IDF and cosine similarity)
Jupyter Notebook / CLI
IPython Widgets (for interactive input)
