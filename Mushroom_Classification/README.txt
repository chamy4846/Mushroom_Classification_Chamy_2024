Mushroom Classification
This project focuses on classifying mushrooms as edible or poisonous based on several features using machine learning algorithms. 
The dataset used is the well-known Mushroom Dataset from Kaggle.

Project Overview
This repository contains the code for training and testing various classification models on the mushroom dataset. 
The primary goal is to develop a model that accurately classifies whether a mushroom is edible or poisonous based on its features such as cap shape, gill color, etc.

Key Features
Data cleaning and preprocessing
Model selection and evaluation
Performance metrics such as accuracy, precision, recall, and F1-score
Confusion matrix visualization
Feature importance analysis

Requirements
The following Python libraries are required to run this project. You can install them using pip:
pip install pandas scikit-learn matplotlib seaborn

Dependencies
pandas: For data manipulation and analysis
scikit-learn: For building and evaluating machine learning models
matplotlib: For plotting and visualizing the results
seaborn: For enhanced data visualization

Dataset
The mushroom dataset is already included in this repository in the data folder. It consists of 22 categorical features such as:
Cap shape
Cap surface
Gill color
Stalk shape
Habitat, etc.
Each sample in the dataset is labeled as either edible (e) or poisonous (p).

Results
After training various models, the best-performing model achieved 100% accuracy. 
The final output provided detailed metrics, including each model's precision, recall, and F1 score. 
Among the models tested, only the Naive Bayes algorithm had a precision of 0.856, while all other models showed 100% precision. 
Even after removing the feature **odor_n**, which had a significant impact on the classification, the model still maintained 100% accuracy. 
This result may suggest potential issues with the dataset itself.