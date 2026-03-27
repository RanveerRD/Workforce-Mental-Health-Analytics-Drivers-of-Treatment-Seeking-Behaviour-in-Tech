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

## 🚀 Local Setup Instructions

To run this analysis on your local machine, follow these steps:

### Prerequisites
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or Anaconda installed.
- [VSCodium](https://vscodium.com/) or VS Code.
- The **Jupyter Extension** (ms-toolsai.jupyter) installed.

## 🚀 How to Setup the Environment

Once you have cloned the repository, you must manually build the Python environment. Follow these steps:

### 1. Build the Environment
Open your terminal inside the project folder and run:
```bash
conda env create -f environment.yml
```
### 2. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/Psychological_cb.git](https://github.com/Username/Psychological_cb.git)
cd Psychological_cb
```
# Key Results
Based on the machine learning models trained and evaluated:

*   **Random Forest Classifier**: Achieved approximately 81.2% test accuracy.
*   **Support Vector Machine (SVM)**: Achieved approximately 77.5% test accuracy.
*   **Decision Tree Classifier**: Achieved approximately 80.6% test accuracy (with `criterion="entropy", max_depth=3`).
*   **K-Nearest Neighbors (KNN)**: Achieved approximately 75.6% test accuracy (with `n_neighbors=7`).

## Visualizations

*   **Age Distribution**: A `Histplot` showing the distribution and density of Age .

<img width="836" height="581" alt="Screenshot 2026-03-27 at 8 24 53 PM" src="https://github.com/user-attachments/assets/6f944ae4-c30b-4ec9-a0bb-cb3dcc570ef1" />

*   **Age Distribution by Treatment**: A `FacetGrid` showing the age distribution separated by whether individuals sought `treatment` or not.

<img width="815" height="420" alt="Screenshot 2026-03-27 at 8 25 06 PM" src="https://github.com/user-attachments/assets/51485f6c-3254-4b7b-a50e-b49d4e2a9216" />

