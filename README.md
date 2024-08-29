<h1 align="center"> Python </h1>

<p align="center"> Some Movies </p>

## :rocket: About the project 

A small analysis of a kaggle dataset that contains data from Netflix, Prime Video, Hulu e Disney.

## :thinking:  Why?

Just practice my skills.

## :warning: Prerequisites

Before running the script, you need to have the following installed:

- [Python](https://www.python.org/downloads/)
- **pandas**: For data manipulation.
- **numpy**: For linear algebra operations.
- **matplotlib**: For static data visualization.
- **plotly**: For interactive data visualization.

## Code Description

- **Data Loading**: The dataset is loaded using pandas.read_csv().
- **Data Cleaning**: Unnecessary columns (Unnamed: 0, type) are dropped.
- **Platform Counts**: The number of TV shows on each platform is calculated and stored in a DataFrame.
- **Visualization**:
  - A pie chart (plotly.express) shows the distribution of TV shows across the platforms.
  - A bar chart (matplotlib.pyplot) shows the number of TV shows rated 18+ for each platform.
- **Filtering by IMDb**: The script filters and displays TV shows with an IMDb rating of 8.0 or lower.
