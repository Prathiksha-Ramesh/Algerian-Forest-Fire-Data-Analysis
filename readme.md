# Algerian Forest Fire Data Analysis

## Overview
This project involves analyzing the Algerian forest fire dataset to understand the patterns and factors contributing to forest fires. The analysis includes data preprocessing, exploratory data analysis (EDA), visualization, and predictive modeling.

## Dataset
The dataset used in this project is the 'Algerian_forest_fires_dataset_UPDATE.csv'. It contains several meteorological variables and fire weather indices (FWI) recorded daily.

### Features
- **day**: Day of the month (1-31)
- **month**: Month of the year (1-12)
- **year**: Year (2012)
- **Temperature**: Temperature in Celsius
- **RH**: Relative Humidity (%)
- **Ws**: Wind speed (km/h)
- **Rain**: Rainfall (mm)
- **FFMC**: Fine Fuel Moisture Code
- **DMC**: Duff Moisture Code
- **DC**: Drought Code
- **ISI**: Initial Spread Index
- **BUI**: Buildup Index
- **FWI**: Fire Weather Index
- **Classes**: Fire occurrence (Yes/No)

## Analysis
The analysis is performed using Python, leveraging libraries such as pandas, numpy, matplotlib, and seaborn. The following steps outline the major components of the analysis:

### 1. Data Loading
The dataset is loaded into a pandas DataFrame for processing and analysis.

### 2. Data Cleaning
- Handle missing values
- Correct data types
- Remove any duplicate entries

### 3. Exploratory Data Analysis (EDA)
- Statistical summary of the data
- Visualizations to understand distributions and relationships among variables
- Time series analysis of fire occurrences

### 4. Feature Engineering
- Creation of new features if necessary
- Scaling and normalization of data for modeling

### 5. Modeling
- Implementing various machine learning models to predict fire occurrences
- Model evaluation using appropriate metrics (e.g., accuracy, precision, recall)

## Results
The results of the analysis, including visualizations and model performance metrics, are documented within the Jupyter notebook.

## How to Run the Notebook
1. Clone the repository.
2. Ensure you have the necessary Python packages installed:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run the cells sequentially to reproduce the analysis:
   ```bash
   jupyter notebook notebook.ipynb
   ```

## License
This project is licensed under the terms of the MIT license. See the LICENSE file for details.

## .gitignore
Refer to the .gitignore file for details on files and directories to be ignored.

## Requirements
The required Python packages are listed in the requirements.txt file.

   
