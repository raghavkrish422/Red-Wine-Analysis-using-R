# Red Wine Quality Analysis

This project analyzes the quality of red wine based on various attributes using Python and Jupyter Notebook. It includes data exploration, data preparation, modeling with two regression algorithms, model evaluation, feature importance analysis, and a conclusion summarizing key insights.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Instructions](#instructions)
  - [Project Structure](#project-structure)
  - [Data Exploration and Preparation](#data-exploration-and-preparation)
  - [Regression Modeling](#regression-modeling)
  - [Model Evaluation](#model-evaluation)
  - [Feature Importance Analysis](#feature-importance-analysis)
  - [Conclusion](#conclusion)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [License](#license)

## Project Overview

This project aims to understand and predict the quality of red wine based on its chemical attributes. It utilizes Python, Jupyter Notebook, and popular data science libraries for analysis.

## Dataset

The dataset used in this project is the "Red Wine Quality" dataset, found in the `winequality-red.csv` file. It contains various chemical and sensory attributes of red wines, along with a quality rating. This project is about predicting the quality of red wine using machine learning algorithms. The dataset used in this project is related to red and white variants of the Portuguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.). This dataset can be viewed as a classification task. The classes are ordered and not balanced (e.g. there are many more normal wines than excellent or poor ones). Also, we are not sure if all input variables are relevant. So it could be interesting to test feature selection methods.

## Instructions

### Project Structure

The project is organized into several phases using the same Jupyter Notebook: "Red Wine Quality.ipynb."

### Data Exploration and Preparation

1. Open the Jupyter Notebook.
2. Follow the code and documentation to perform data exploration and preparation.
3. Ensure the dataset is cleaned, and data is ready for modeling. This phase carries 3.5 points.

### Regression Modeling

1. Implemented two regression algorithms for wine quality prediction.
2. Trained and evaluated the models. This phase carries 6 points.

### Model Evaluation

1. Included results for three metrics (e.g., RMSE, MAE, R-squared) for each model.
2. Compared the results to identify the better-performing model. This phase carries 3 points.

### Feature Importance Analysis

1. Calculated and visualized feature importances for at least one of the regression models. This phase carries 3 points.

### Conclusion

1. Summarize key insights obtained from the analysis.
2. Include one limitation of the analysis.
3. Comment on future work that could be done to improve the analysis. This phase carries 2 points.


## Requirements

To run the project, you need the following libraries and tools installed:

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Getting Started

1. Clone this repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Open the Jupyter Notebook "Red Wine Quality.ipynb" to start your analysis.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
