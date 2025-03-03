# Airplane Crashes Dataset Analysis

## Overview
This project involves the analysis of the **Airplane Crashes Dataset** sourced from Kaggle. The dataset contains historical records of airplane crashes, including details such as date, location, operator, fatalities, and more. The goal of this project is to perform data cleaning, handle missing values, apply feature extraction, and conduct both univariate and multivariate analysis to uncover insights and patterns in the data.

## Dataset
The dataset used in this project is **Airplane Crashes Since 1908**, which can be found on [Kaggle](https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908). It includes information about airplane accidents, such as:
- Date of the crash
- Location
- Operator
- Flight number
- Route
- Type of aircraft
- Registration number
- Aboard and fatalities count
- Summary of the incident

## Project Steps
1. **Data Loading and Inspection**:
   - Load the dataset into a pandas DataFrame.
   - Inspect the structure, columns, and basic statistics of the data.

2. **Handling Missing Values**:
   - Identify columns with missing values.
   - Apply appropriate techniques to handle missing data (e.g., imputation, dropping rows/columns).

3. **Feature Extraction**:
   - Extract useful features from existing columns (e.g., extracting year).
   - Create new features that may provide additional insights (e.g., survival rate).

4. **Univariate Analysis**:
   - Perform univariate analysis on individual features to understand their distributions and characteristics.
   - Visualize distributions using histograms, bar plots, and box plots.

5. **Multivariate Analysis**:
   - Explore relationships between multiple features using correlation matrices, pair plots, and other visualization techniques.
   - Identify trends and patterns in the data.

6. **Insights and Conclusions**:
   - Summarize key findings from the analysis.
   - Provide actionable insights and recommendations based on the data.

## Tools and Libraries
- **Python**: Primary programming language.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Matplotlib** and **Seaborn**: Data visualization.

## Repository Structure
Airplane-Crashes-Analysis/
├── Airplane_Crashes_Analysis.ipynb # Jupyter notebook with analysis
├── README.md # Project overview
└── requirements.txt # Python dependencies

## How to Run the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/sama-sameh/Airplane-Crashes-Analysis.git

## Install dependencies:
pip install -r requirements.txt

## Future Work
- Incorporate external datasets (e.g., weather data) to enhance analysis.
- Build predictive models to estimate crash severity or survival rates.
- Perform deeper geographical analysis using mapping tools.

## Contribution
Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and suggestions are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.