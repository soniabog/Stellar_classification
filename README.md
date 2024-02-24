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
To set up and run this project, or view the Jupyter Notebook if it's not rendering directly on GitHub, follow these steps:

1. **Viewing the Notebook on nbviewer:**
   - If you're unable to render the Jupyter Notebook directly on GitHub, you can use [nbviewer](https://nbviewer.org/) to view the notebook.
   - Simply go to [nbviewer](https://nbviewer.org/), paste the URL of the repository into the search box, and navigate to the notebook file (.ipynb) you wish to view.

Please note that while nbviewer allows you to view the content of Jupyter Notebooks, to run the code and interact with the data, you'll need to follow the local setup steps.

2. **Local Setup:**
   - Clone this repository to your local machine.
   - Ensure the following Python packages are installed in your environment:
     - `pandas`
     - `seaborn`
     - `matplotlib`
     - `imbalanced-learn` (for `SMOTE`)
     - `scikit-learn` (for various preprocessing, modeling, and metrics functions)
     - `yellowbrick` (for visualization of model performance)
   - You might need to install some of these packages if they are not already installed. You can do so using pip:
     ```
     pip install pandas seaborn matplotlib imbalanced-learn scikit-learn yellowbrick
     ```
   - Navigate to the project directory.
   - Open Jupyter Notebook and run the project file (.ipynb).

## Exploratory Data Analysis
Our exploratory data analysis aims to understand the dataset's characteristics, including distribution of classes, relationship between features, and any potential patterns that can inform our model selection.

## Model Selection and Evaluation
After initial data analysis, we proceed with training the models. We evaluate their performance based on accuracy to select the best-performing model for our classification task.

## Conclusion and Future Work
This project serves as a foundation for future research in stellar classification and astronomical studies. The findings and methodologies can be extended or refined with additional data or by exploring other machine learning algorithms.

## Contributor
Sonia Bogdańska
