# Project Name: Mental Health in Tech Survey Analysis

## Miniconda 3, Python 11 Environment
 
 Version 1.0 Primary Libraries Installed:
 
    [scikit-learn               1.8.0
    
     seaborn                    0.13.2
     
     xgboost                    3.2.0
     
     pandas                     3.0.1
     
     numpy                      2.4.3
     
     matplotlib                 3.10.8
     
     statsmodels                0.14.6]

## Overview
This project focuses on predicting whether individuals in the tech industry will seek treatment for mental health conditions. It utilizes a survey dataset and applies various machine learning classification models to achieve this prediction. The analysis includes data preprocessing, feature selection, and model evaluation.

## Setup Instructions
To run this project, you will need a Google Colab environment and ensure your Google Drive is mounted.

1.  **Mount Google Drive**: Ensure your Google Drive is mounted and `survey.csv` is located at `/content/drive/MyDrive/Finding/survey.csv`.
2.  **Install Libraries**: The necessary libraries (pandas, numpy, matplotlib, seaborn, scikit-learn) are typically pre-installed in Google Colab. If not, you may need to install them using `!pip install [library_name]`.
3.  **Execute Cells**: Run all the cells sequentially in the Jupyter/Colab notebook.

## Key Results
Based on the machine learning models trained and evaluated:

*   **Random Forest Classifier**: Achieved approximately 81.2% test accuracy.
*   **Support Vector Machine (SVM)**: Achieved approximately 77.5% test accuracy.
*   **Decision Tree Classifier**: Achieved approximately 80.7% test accuracy (with `criterion="entropy", max_depth=3`).
*   **K-Nearest Neighbors (KNN)**: Achieved approximately 76.2% test accuracy (with `n_neighbors=7`).

## Visualizations

*   **Age Distribution**: A `Histplot` showing the distribution and density of Age .
   <img width="1005" height="701" alt="download" src="https://github.com/user-attachments/assets/82b1bfe7-1b1f-4b9b-924a-cf96f51e7f03" />

*   **Age Distribution by Treatment**: A `FacetGrid` showing the age distribution separated by whether individuals sought `treatment` or not.
   <img width="989" height="515" alt="download (1)" src="https://github.com/user-attachments/assets/6ceddf7d-6033-436b-a7b2-59df73743805" />

