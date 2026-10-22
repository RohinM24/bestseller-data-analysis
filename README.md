# New York Times Bestseller Data Analysis

## Overview

An exploratory data analysis and machine learning project investigating historical New York Times bestseller data. The project examines bestseller trends, explores patterns within the dataset, and applies Logistic Regression to a classification problem.

Using Python and data processing tools, this project demonstrates how historical data can be transformed into meaningful insights through data analysis, feature preparation and machine learning.

## Project Objectives

- Explore historical New York Times bestseller data.
- Investigate trends and patterns in bestseller listings.
- Clean, prepare and analyse structured data.
- Apply exploratory data analysis to understand distributions and relationships.
- Implement Logistic Regression for classification.
- Evaluate model performance using appropriate metrics.

## Dataset

The project uses the `nyt-bestsellers.csv` dataset, containing approximately 61,430 records and 12 columns.

The dataset provides historical bestseller information that can be used to investigate listing patterns and trends over time.

Before interpreting the results, the dataset's column definitions, time coverage and classification target should be reviewed to establish exactly what each observation represents.

## Tools and Technologies

- **Python:** Core programming language for data analysis and modelling.
- **Pandas:** Data manipulation and preparation.
- **NumPy:** Numerical operations and mathematical computations.
- **PySpark:** Distributed data processing and exploration.
- **Matplotlib:** Data visualisation.
- **Seaborn:** Statistical visualisation.
- **Scikit learn:** Machine learning utilities and model evaluation, where applicable.
- **Jupyter Notebook:** Interactive development and documentation.

## Workflow

### 1. Data Preparation

Load the dataset, inspect its structure, examine data types and identify missing values, duplicates and potential data quality issues.

### 2. Exploratory Data Analysis

Investigate the distribution of relevant variables, bestseller listing patterns and relationships that may inform the modelling process.

### 3. Feature Engineering

Prepare relevant features for classification, ensuring categorical variables and numerical values are represented appropriately for the selected model.

### 4. Logistic Regression

Apply Logistic Regression to the defined classification problem. The implementation explores how input features can be used to estimate class probabilities and generate predictions.

### 5. Model Evaluation

Evaluate predictions using suitable classification metrics, such as accuracy, precision, recall, F1 score and a confusion matrix, where appropriate.

The final evaluation should be interpreted in the context of the selected target variable, class distribution and validation methodology.

## Repository Structure

```text
bestseller-data-analysis/
│
├── Part_2_Logistic_Regression.ipynb
├── README.md
└── requirements.txt
```

The notebook contains the project's analysis and modelling workflow. Additional files may be added as the project develops.

## Getting Started

### Prerequisites

Python 3.12 and Jupyter Notebook are recommended.

### Installation

Clone the repository:

```bash
git clone https://github.com/RohinM24/bestseller-data-analysis.git
cd bestseller-data-analysis
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn pyspark jupyter
```

### Running the Project

1. Obtain the dataset from its original source or the authorised location specified for the project.
2. Place the dataset in the appropriate location expected by the notebook.
3. Open the notebook in Jupyter.
4. Update file paths if necessary.
5. Run the cells in sequence to reproduce the analysis.

## Key Areas of Exploration

- Historical bestseller trends
- Data cleaning and transformation
- Exploratory data analysis
- Feature engineering
- Logistic Regression classification
- Model evaluation and interpretation

## Future Improvements

- Develop additional visualisations to communicate key findings.
- Compare Logistic Regression with alternative classification algorithms.
- Improve feature selection and model validation.
- Document the final results and identify the most informative predictors.
- Develop an interactive dashboard to present the analysis.

## Author

**Rohin Maharaj**

Aspiring Data Analyst and AI Business Analyst with an interest in data analytics, machine learning and translating data into actionable insights.

Explore my GitHub profile for more data science and analytics projects.

---

*This project is intended for analytical and educational purposes. Findings and model performance should be interpreted in the context of the dataset and the classification objective.*
