# Housing Market Prediction

## Overview

This project develops two machine learning models to predict key outcomes in the housing market: estimating house prices and determining if a house will sell within 30 days. It serves as a comprehensive case study in the machine learning workflow, from data cleaning and exploratory data analysis (EDA) to model training, evaluation, and comparison. The project uses regression and classification techniques to derive insights and make predictions based on a real-world dataset.

## Features

* **Data Preparation:** Robust data cleaning and transformation to prepare the raw dataset for analysis. This includes handling missing values and engineering new features.
* **Exploratory Data Analysis (EDA):** In-depth analysis to understand relationships between variables, identify outliers, and visualize data distributions.
* **Regression Modeling:** Implementation of a regression model to accurately predict house prices, with an emphasis on LASSO regularization to improve model performance and prevent overfitting.
* **Classification Modeling:** Development of a classification model to predict the likelihood of a house selling within 30 days.
* **Model Comparison:** A detailed comparison of model performance metrics (e.g., Accuracy, Precision, Recall, F1-Score, AUC-ROC) to assess the effectiveness of each model.

## Project Structure

* **`Clean_Data.csv`**: The raw dataset used as the basis for the project.
* **`Final Python Code.ipynb`**: The Jupyter Notebook containing all the code for data processing, model training, and evaluation. This is the core of the project.
* **`Final Report.pdf`**: A detailed report outlining the methodology, findings, and conclusions of the machine learning project.
* **`ML Project Notes.txt`**: A text file with miscellaneous notes and thoughts from the development process.

## Requirements

* **Python 3.x**
* **Jupyter Notebook** or another compatible IDE (e.g., VS Code, PyCharm)
* **Required Python Libraries:**
    * `pandas`
    * `numpy`
    * `matplotlib`
    * `seaborn`
    * `scikit-learn`

You can install the required libraries using pip:
`pip install pandas numpy matplotlib seaborn scikit-learn`

## Installation & Usage

1.  **Clone the repository:**
    `git clone https://github.com/your-username/housing-market-prediction.git`
    `cd housing-market-prediction`

2.  **Open the Jupyter Notebook:**
    `jupyter notebook "Final Python Code.ipynb"`

3.  **Run the cells** in the notebook to replicate the data analysis and model training steps.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
