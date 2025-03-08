## Population Distribution Visualization

## Overview
This project visualizes the distribution of the world's population using a bar chart. The dataset is sourced from the World Bank:

[World Bank Population Data](https://data.worldbank.org/indicator/SP.POP.TOTL)

## Dataset Description
The dataset includes total population figures for different countries over multiple years. Key attributes:
- **Country Name**: Name of the country.
- **Country Code**: Unique identifier for the country.
- **Year**: Year of the recorded population data.
- **Population Count**: Total population for the given country and year.

## Objective
The objective is to visualize population distribution by:
- Displaying a bar chart of the top 20 most populous countries for a given year.
- Identifying trends in population sizes.

## Tools & Libraries
The following tools are used:
- **Python** (for data processing and visualization)
- **Pandas** (for handling dataset operations)
- **Matplotlib** (for generating bar charts)

## Steps to Run the Project
1. Ensure you have the required libraries installed (`pandas`, `matplotlib`).
2. Load the dataset using Pandas.
3. Filter the data for the desired year.
4. Sort the data and extract the top 20 most populous countries.
5. Generate a horizontal bar chart using Matplotlib.
6. Display or save the visualization.

## Expected Output
- A horizontal bar chart showing the top 20 most populous countries in a selected year.
- Insights into how population sizes compare across different nations.

## Usage
Run the provided Python script (`task_1.py`) in a compatible environment. Modify the year parameter to visualize different time periods.

## License
This project is open-source and follows the data usage policies of the World Bank.

