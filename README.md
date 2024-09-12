# Titanic Data Analysis Project

## Overview
This project contains a synthetic data analysis based on the famous Titanic dataset. It uses Python and various data analysis libraries to gain insights from generated data that mimics the Titanic passenger information.

## Contents
- `titanic_analysis.ipynb`: Jupyter Notebook with the main analysis code
- `requirements.txt`: List of required Python packages
- `README.md`: This file with project information

## Features
- Generation of a synthetic dataset similar to the Titanic dataset
- Visualization of various aspects of passenger data
- Statistical analyses and correlation investigations

## Libraries Used
- pandas: For data manipulation and analysis
- seaborn: For statistical data visualization
- matplotlib: For additional plotting functions
- numpy: For numerical operations

## Main Analyses
1. Survival rate analysis
2. Passenger class distribution
3. Survival rate by passenger class
4. Age distribution of passengers
5. Survival rate by gender
6. Fare distribution
7. Correlation heatmap of variables

## Installation and Execution
1. Clone this repository
2. Create and activate the Conda environment:
    ```bash
      conda env create -f environment.yml
      conda activate titanic-analysis
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Open `titanic_analysis.ipynb` in Jupyter Notebook or JupyterLab
5. Run the cells sequentially to reproduce the analysis

## Code Quality
- This project uses Flake8 for linting. Run flake8 in the project directory to check for code style issues.
- The code is formatted using Black. Run black . to format the code.

## Continuous Integration
This project uses GitHub Actions for CI/CD. The workflow includes:

- Running tests
- Linting with Flake8
- Checking code formatting with Black

## Results
The analysis provides insights into various factors that might have influenced survival on the Titanic, based on a synthetic dataset. The visualizations and statistical evaluations help identify patterns and relationships in the data.

## Future Improvements
- Implement more advanced statistical tests
- Add machine learning models for prediction
- Expand the documentation with more detailed explanations of findings

## Version
Current version: [Content of VERSION file]

## Note
This dataset is synthetic and for demonstration purposes only. For a genuine analysis of the Titanic disaster, authentic historical data should be used.