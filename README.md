# Data-Analysis-on-Netflix-Dataset

This repository contains a Jupyter Notebook that performs various data analysis tasks on a Netflix dataset. The analysis includes data cleaning, exploration, and extracting insights related to Netflix shows and movies.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The Netflix Dataset Analysis project focuses on analyzing a dataset containing information about Netflix shows and movies. The primary objectives include cleaning the data, exploring various attributes, and extracting meaningful insights about the content available on Netflix.

## Features

- **Data Loading**: Load the Netflix dataset using Pandas.
- **Data Cleaning**: Identify and handle missing values.
- **Data Exploration**: Inspect the dataset, including its structure, and display summary statistics.
- **Visualization**: Generate visualizations to understand the distribution and relationships of different attributes.
- **Violation Analysis**: Determine the frequency of different categories and genres.
- **Search Conducted Analysis**: Analyze patterns in the data related to content ratings and durations.
- **Stop Duration Analysis**: Calculate the mean duration of shows/movies and their distribution.
- **Age Distribution Analysis**: Compare different attributes using groupby and descriptive statistics.

## Dataset

The dataset used in this analysis includes the following columns:
- `Show_Id`: Unique identifier for each show.
- `Category`: Indicates whether the entry is a TV Show or a Movie.
- `Title`: Title of the show or movie.
- `Director`: Director of the show or movie.
- `Cast`: Main cast members of the show or movie.
- `Country`: Country where the show or movie was produced.
- `Release_Date`: Release date of the show or movie.
- `Rating`: Rating of the show or movie (e.g., PG-13, TV-MA).
- `Duration`: Duration of the show or movie (e.g., 90 min, 1 Season).
- `Type`: Genre or type of the show or movie.
- `Description`: Brief description of the show or movie.

## Installation

To run the notebook and perform the analysis, you'll need to have Python and Jupyter Notebook installed on your system. Additionally, you'll need to install the required Python libraries.

1. Clone this repository:
   ```bash
   git clone https://github.com/Soniya-krishikka/Data-Analysis-on-Netflix-Dataset.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Data-Analysis-on-Netflix-Dataset
   ```
3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. In the Jupyter Notebook interface, navigate to the project directory and open `Project 8 - Netflix Dataset Analysis.ipynb`.
3. Run the cells in the notebook to perform the data analysis.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please create a pull request or open an issue.
