# RiyaDadlani_dsc New Coders Survey Analysis
This project applies machine learning techniques to analyze the 2021 freeCodeCamp New Coder's Survey dataset. By leveraging exploratory data analysis, cluster analysis, and classification models, I aim to gain insights into the characteristics of new coders and predict their income levels.


The project involves three main tasks:

Exploratory Data Analysis (EDA): Understand the dataset and its features.
Cluster Analysis: Group new coders into clusters and understand the characteristics of each cluster.
Classification: Build machine learning models to predict whether a developer earns a high income based on their information.

Setup Instructions


Prerequisites


Python 3.x


Jupyter Notebook or any other IDE for running Python code


Git


Installation

Clone the repository:
git clone https://github.com/riyadadlani02/RiyaDadlani_dsc.git
cd RiyaDadlani_dsc


Create a virtual environment:

python3 -m venv venv
source venv/bin/activate


Install the required packages
pip install -r requirements.txt

Download the dataset:
Download the dataset from Kaggle and place the CSV file in the project directory.The dataset is available on Kaggle: https://www.kaggle.com/datasets/fccuser/2021-new-coder-survey


Open the Jupyter Notebook:
Navigate to the project directory and open the notebook file (DSC.ipynb).
Run the cells in the notebook sequentially to perform data analysis, clustering, and classification.


Main Components

Data Preprocessing and EDA:

Load and inspect the dataset.
Handle missing values and outliers.
Map income ranges to numerical values.
Perform basic statistical analysis and visualization.


Cluster Analysis:

Select relevant features for clustering.
Standardize the features.
Apply KMeans clustering algorithm.
Visualize the clusters.


Classification:

Define the target variable (Income Category: high income vs low income).
Split the data into training and testing sets.
Build and train a logistic regression model.
Evaluate the model using classification metrics.



Conclusion


This project provides insights into the state of new coders, their learning patterns, and income levels. By clustering and classifying the data, we can better understand the different groups of new coders and the factors that influence their income levels.


Contributions

Feel free to open issues or submit pull requests if you have any suggestions or improvements.
