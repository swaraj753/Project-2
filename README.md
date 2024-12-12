# Project 2: Data Analysis and Visualization

This project analyzes and visualizes data from various sources, providing insights based on the analysis. The analysis script is named `autolysis.py`, and it processes different CSV files to generate reports and visualizations. This repository contains the necessary files, including the script, results, and visualizations, to demonstrate the analysis process.

## Files

- **autolysis.py**: The main Python script that performs data analysis.
- **goodreads/**: Directory containing analysis results related to Goodreads data.
  - `README.md`: Explanation of the analysis performed on the Goodreads dataset.
  - `*.png`: Visualizations generated from the Goodreads dataset.
- **happiness/**: Directory containing analysis results related to Happiness data.
  - `README.md`: Explanation of the analysis performed on the Happiness dataset.
  - `*.png`: Visualizations generated from the Happiness dataset.
- **media/**: Directory containing analysis results related to Media data.
  - `README.md`: Explanation of the analysis performed on the Media dataset.
  - `*.png`: Visualizations generated from the Media dataset.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Analysis Overview

### 1. Data Overview
The project includes the following datasets:

- **Goodreads Data**: A collection of information related to books, authors, and user reviews.
- **Happiness Data**: A dataset containing factors contributing to global happiness levels across countries.
- **Media Data**: A dataset related to media consumption and its effects on various demographics.

### 2. Analysis
The `autolysis.py` script performs the following tasks:
- **Data Cleaning**: Removes invalid or missing data.
- **Exploratory Data Analysis (EDA)**: Identifies trends, correlations, and outliers.
- **Visualization**: Creates charts and graphs to illustrate key insights from the data.

### 3. Insights
From the analysis, the following key insights were discovered:
- **Goodreads**: Analysis revealed trends in book ratings, the most reviewed genres, and the correlation between author popularity and book ratings.
- **Happiness**: The happiness data showed a strong correlation between GDP per capita and happiness levels, with Nordic countries consistently ranking high in happiness.
- **Media**: The media dataset indicated that media consumption significantly impacts the well-being of younger demographics, with a marked difference in preferences based on age.

### 4. Implications
The insights derived from this analysis can be applied in various fields:
- **Goodreads**: Publishers can target popular genres and authors to increase book sales.
- **Happiness**: Policymakers can focus on improving GDP per capita and overall quality of life to boost national happiness.
- **Media**: Marketers and media producers can tailor their content to younger demographics to maximize engagement and influence.

## How to Run

To run the analysis, simply execute the script with the desired dataset:

```bash
python autolysis.py [dataset.csv]
