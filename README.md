# Exploring NYC Public School Test Result Scores

This project analyzes the SAT test performance of public schools in New York City. Using Python and pandas, the notebook explores the relationships between math, reading, and writing scores to identify high-performing schools and trends across different boroughs.

## Overview

Every year, American high school students take the SATs, which are standardized tests intended to measure literacy, numeracy, and writing skills. There are three sections—reading, math, and writing—each with a maximum score of 800 points. These tests are extremely important for students and colleges, as they play a pivotal role in the admissions process.

This analysis answers three key questions:
1. Which schools have the best math results?
2. What are the top 10 performing schools based on total SAT scores?
3. Which NYC borough has the highest standard deviation in their combined SAT scores?

## Key Findings

The analysis in `notebook.ipynb` produces several dataframes highlighting specific insights:

- **Best Math Schools**: Identifies schools with an average math score of at least 640.
- **Top 10 Schools**: A ranking of the top 10 schools by total SAT score (Math + Reading + Writing).
- **Borough Statistics**: Aggregates data by borough to calculate the number of schools, average SAT scores, and standard deviation, revealing which borough has the most variation in school performance.

## Files in this Repository

- `notebook.ipynb`: A Jupyter Notebook containing the data analysis code using pandas.
- `schools.csv`: The dataset containing SAT scores and location data for NYC public schools.
- `schoolbus.jpg`: An image asset used in the notebook presentation.

## Technologies Used

- **Python**
- **pandas**: For data manipulation and aggregation.
- **Jupyter Notebook**: For interactive coding and data visualization.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/DavitEgoian/Exploring-NYC-Public-School-Test-Result-Scores.git
   ```
2. Install the required dependencies (pandas, notebook).
3. Open `notebook.ipynb` in Jupyter Notebook or JupyterLab to view and execute the cells.
