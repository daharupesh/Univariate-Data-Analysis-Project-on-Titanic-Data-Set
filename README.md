# Titanic Dataset: Univariate Data Analysis

This project performs **univariate analysis** on the well-known **Titanic dataset**, using various **visualization techniques** to explore both categorical and numerical data. The analysis aims to provide insights into key variables such as **survival rates**, **passenger demographics**, and other relevant features.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Analysis Overview](#analysis-overview)
- [Libraries Used](#libraries-used)
- [Visualizations](#visualizations)
- [How to Run](#how-to-run)
- [Conclusion](#conclusion)
  

## Introduction

The Titanic dataset contains data about the passengers aboard the RMS Titanic, including information such as their age, sex, class, and whether they survived the disaster. This project focuses on **univariate analysis**, which examines each variable individually to understand its distribution and significance.

## Dataset

The dataset used is the **Titanic dataset** from Kaggle, which includes the following features:

- `Survived`: Survival status (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Sex`: Gender
- `Age`: Age in years
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Analysis Overview

This analysis includes:

- **Categorical Data Analysis**:
  - Bar charts and pie charts for variables like `Survived`, `Pclass`, `Sex`, and `Embarked`
  
- **Numerical Data Analysis**:
  - Histograms, distribution plots, and boxplots for numerical columns like `Age`

## Libraries Used

- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Visualization of data with plots
- **Seaborn**: Advanced data visualization
- **FPDF**: Generating PDF reports of the analysis

## Visualizations

The following visualizations are generated as part of the analysis:

- **Bar Charts**: For categorical variables like `Survived`, `Pclass`, `Sex`, and `Embarked`
- **Pie Charts**: For the distribution of `Sex` and `Pclass`
- **Histograms**: For the distribution of `Age`
- **Displot**: To further analyze the distribution of `Age`
- **Boxplot**: To detect outliers in the `Age` column

### Sample Visualizations

- Survival Count Bar Chart:
  ![Survived Bar Chart](images/survived_bar.png)

- Passenger Class Pie Chart:
  ![Pclass Pie Chart](images/pclass_pie.png)

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/titanic-univariate-analysis.git
   ```
2. **Install the required libraries**:
   ```bash
   pip install pandas matplotlib seaborn fpdf
   ```
3. **Run the analysis**:
   ```bash
   python univariate_analysis.py
   ```
4. **Generate PDF Report**:
   The code will generate a PDF report of the univariate analysis. This file will be saved as `titanic_univariate_report.pdf` in the root directory.

## Conclusion

This univariate analysis offers valuable insights into the Titanic dataset, laying the groundwork for more complex analyses. The visualizations help highlight patterns, especially with respect to survival rates and the impact of variables like age, class, and gender.

