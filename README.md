# Penguins-Species-Classification
This repository contains a Python script for classifying penguin species using the K-Nearest Neighbors (KNN) algorithm. 

## Dataset

The dataset used in this project is the "penguins" dataset available in the Seaborn library. It includes measurements for penguins from three different species, along with additional information such as the island of residence and sex. The features used for classification are bill length, bill depth, flipper length, body mass, sex, and island.

## How It Works

# Data Loading and Preprocessing: 
The script starts by loading the "penguins" dataset from Seaborn and performing initial preprocessing, such as dropping missing values and encoding categorical variables.

# Exploratory Data Analysis (EDA): 
It then visualizes the dataset to understand the distribution of different features across penguin species.

# Feature Selection and Scaling: 
Different sets of features are selected and normalized using MinMaxScaler to ensure that distance calculations during the KNN algorithm are not biased by the scale of the features.

# Model Training and Evaluation: 
The script demonstrates the training of KNN models with different configurations, evaluating their performance on a test set.

## Result:
Using only two features:  94.9% accuracy.

Using 4 features, after normalization:  98.7% accuracy.

Using all features (8), after one hot encoding: 0.98% accuracy!
