### Exercises with Pandas

This repository contains two Jupyter notebooks developed as part of a data analysis exercise using Python and Pandas for the LEDE Program. The goal was to practice data exploration, filtering, analysis, and visualization techniques.

## 1 - Animals analysis

In this notebook, a small dataset containing information about animals (dogs and cats) was analyzed.

## Tasks completed

- Loaded the dataset from a CSV file using Pandas.
- Explored the dataset structure, including:
    - Number of rows and columns.
    - Column names.
    - Data types.
- Examined sample records from the dataset.
- Identified the longest animals by sorting the data.
- Calculated summary statistics such as:
    - Median length.
    - Standard deviation of length.
- Counted the number of animals by category.
- Filtered records based on conditions, including:
    - Dogs only.
    - Animals longer than a specified length.
- Created a new column converting length from centimeters to inches.
- Compared average lengths of cats and dogs.
- Used `groupby()` to calculate average lengths by animal type.
- Produced three visualizations using Matplotlib, including:
    - Histogram of animal lengths.
    - Horizontal bar chart showing animal lengths.
    - Bar chart comparing the number of cats and dogs.

## 2 - Billionaires analysis

In this notebook, a dataset containing information about billionaires was analyzed.

## Tasks completed

- Loaded data from Excel (using the `openpyxl` library) and JSON files.
- Explored the dataset structure, including:
    - Shape.
    - Columns.
    - Data types.
- Identified the wealthiest individuals through sorting.
- Analyzed gender distribution among billionaires.
- Calculated:
    - Percentage of billionaires by gender.
    - Median net worth by gender.
    - Average age of billionaires.
    - Average age of self-made versus inherited-wealth billionaires.
- Examined sources of wealth and the most common companies represented.
- Analyzed the relationship between citizenship and total wealth.
- Identified the youngest and oldest individuals in the dataset.
- Created visualizations using Matplotlib, including:
    - Histogram of billionaire ages.
    - Scatter plot of age versus net worth.
    - Horizontal bar chart of the wealthiest individuals.
- Imported and previewed a JSON version of the dataset.