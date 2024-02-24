# Stellar Classification Project

## Overview
This project focuses on the classification of celestial objects using data from the Sloan Digital Sky Survey. With a dataset containing detailed observations of galaxies, stars, and quasars, the goal is to develop a machine learning model that can accurately predict the class of new space objects based on their attributes.

## Data Source
The dataset utilized for this project is available on Kaggle: [Stellar Classification Dataset - SDSS17](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17/data).

## Project Aim
The aim of this project is to explore different machine learning classification techniques to find the most effective model for predicting the class of celestial objects. By conducting extensive exploratory data analysis and applying various classification algorithms, we aim to achieve high accuracy in our predictions. This work can be crucial for advancing astronomical research and enhancing our understanding of the universe.

## Classification Models Evaluated
We evaluated three different classification models to determine their effectiveness in predicting celestial object classes:
- **K-Nearest Neighbors (KNN):** Algorithm that classifies objects based on the majority class among its nearest neighbors.
- **Decision Tree:** A model that uses a tree-like graph of decisions and their possible consequences, including chance event outcomes, resource costs, and utility.
- **Random Forest:** An ensemble learning method for classification that operates by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes of the individual trees.

## Getting Started
1. Clone this repository to your local machine.
2. Ensure the following Python packages are installed in your environment:
   - `pandas`
   - `seaborn`
   - `matplotlib`
   - `imbalanced-learn` (for `SMOTE`)
   - `scikit-learn` (for various preprocessing, modeling, and metrics functions)
   - `yellowbrick` (for visualization of model performance)
3. You might need to install some of these packages if they are not already installed. You can do so using pip: pip install pandas seaborn matplotlib imbalanced-learn scikit-learn yellowbrick
4. Navigate to the project directory.
5. Open Jupyter Notebook and run the project file (.ipynb).

## Exploratory Data Analysis
Our exploratory data analysis aims to understand the dataset's characteristics, including distribution of classes, relationship between features, and any potential patterns that can inform our model selection.

## Model Selection and Evaluation
After initial data analysis, we proceed with training the models. We evaluate their performance based on accuracy to select the best-performing model for our classification task.

## Conclusion and Future Work
This project serves as a foundation for future research in stellar classification and astronomical studies. The findings and methodologies can be extended or refined with additional data or by exploring other machine learning algorithms.

## Contributor
[Sonia Bogdańska]
