# Life Expectancy and GDP Analysis

This project investigates the correlation between the economic output of a country (measured by GDP) and the life expectancy of its citizens. The analysis is based on data from six nations over a period of 15 years (2000-2015).

To explore the full analysis, open the `Life_Expectancy_GDP.ipynb` Jupyter Notebook, which contains detailed explanations, visualizations, and conclusions drawn from the data.

## Project Overview

The primary objectives of this project are to:

1. **Analyze Trends Over Time**:
   - Has life expectancy increased over time in the six nations?
   - Has GDP increased over time in the six nations?

2. **Explore Correlations**:
   - Is there a correlation between GDP and life expectancy in these countries?

3. **Statistical Analysis**:
   - What is the average life expectancy in these nations?
   - What is the distribution of life expectancy across these nations?

## Data Sources

- **GDP**: Data sourced from the [World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD).
- **Life Expectancy**: Data sourced from the [World Health Organization](http://apps.who.int/gho/data/node.main.688).

## Tools and Libraries

The following tools and Python libraries were used in this analysis:

- **Pandas**: For data manipulation and analysis.
- **Matplotlib** & **Seaborn**: For data visualization.
- **NumPy**: For numerical operations.
- **Jupyter Notebook**: For interactive coding and visualization.

## Project Structure

The project is structured into the following steps:

1. **Data Cleaning**:
   - Renaming columns and handling missing or inconsistent data.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizing the distribution of GDP and life expectancy.
   - Plotting trends over time using line charts.

3. **Correlation Analysis**:
   - Calculating the correlation coefficient between GDP and life expectancy.
   - Visualizing the correlation using scatter plots and correlation matrices.

4. **Conclusion**:
   - Summarizing key findings and providing insights on the relationship between GDP and life expectancy.

## Key Findings

- **Life Expectancy**: The average life expectancy ranged from mid to high 70s for countries like Chile, Germany, Mexico, and the United States, while China had a slightly lower average in the mid-70s.
- **GDP and Life Expectancy Correlation**: There is a positive correlation between GDP and life expectancy, particularly strong in countries like Chile, Germany, Mexico, and the United States. China shows an exponential relationship.
