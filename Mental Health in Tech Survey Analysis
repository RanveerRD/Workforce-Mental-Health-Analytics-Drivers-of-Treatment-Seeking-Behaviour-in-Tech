 Mental Health in Tech Survey Analysis

This project aims to predict whether individuals in the tech industry will seek treatment for mental health conditions based on a survey dataset. Various machine learning classification models are applied and evaluated to achieve this prediction.

## Project Objective

The primary goal of this project is to build and compare different machine learning models to predict the likelihood of a person seeking mental health treatment, using insights gathered from a tech workplace survey.

## Dataset

The project uses the `survey.csv` dataset, which contains anonymous responses from a mental health in tech survey. Key features include:

*   **Age**
*   **Gender**
*   **Family History** (of mental illness)
*   **Self-employed status**
*   **Benefits** (mental health benefits provided by employer)
*   **Care Options** (employer options for mental health care)
*   **Anonymity** (of mental health discussions at work)
*   **Leave** (ease of taking medical leave for mental health)
*   **Work Interfere** (how much mental health interferes with work)
*   **Treatment** (target variable: whether the individual sought treatment or not)

## Data Preprocessing and Cleaning

Before model training, the raw data undergoes several preprocessing steps:

1.  **Handling Missing Values**: Missing integer values (e.g., in Age) are imputed, and missing string values (e.g., in `self_employed`, `work_interfere`) are filled with appropriate defaults or 'Don't know'.
2.  **Gender Standardization**: Various forms of gender input are standardized into 'female', 'male', and 'trans'.
3.  **Age Transformation**: Ages are cleaned (e.g., handling outliers) and categorized into age ranges.
4.  **Categorical Encoding**: All categorical features are converted into numerical representations using `LabelEncoder` for compatibility with machine learning algorithms.

## Methodology

The project follows a standard machine learning workflow:

1.  **Exploratory Data Analysis (EDA)**: Initial analysis of the dataset to understand distributions and relationships between features (not explicitly shown in the provided code, but usually a part of such projects).
2.  **Feature Selection**: A subset of relevant features is chosen for model training.
3.  **Data Splitting**: The dataset is split into training (70%) and testing (30%) sets to evaluate model performance on unseen data.
4.  **Model Training and Evaluation**: Several classification algorithms are trained on the preprocessed data and evaluated using appropriate metrics (e.g., accuracy, precision, recall).

### Models Used

*   **Random Forest Classifier**
*   **Support Vector Machine (SVM)**
*   **Decision Tree Classifier**
*   **K-Nearest Neighbors (KNN)**

### Evaluation Metrics

Each model's performance is assessed using:

*   **Accuracy Score**
*   **Precision Score** (for SVM)
*   **Recall Score** (for SVM)

## Results (Based on provided execution)

| Model                  | Test Accuracy |
| :--------------------- | :------------ |
| Random Forest          | ~81.2%        |
| SVM (Linear Kernel)    | ~77.5%        |
| Decision Tree          | ~80.7%        |
| KNN (n_neighbors=7)    | ~76.2%        |

*(Note: Exact metrics might vary slightly based on `random_state` and specific model parameters.)*

## How to Run the Code

To replicate the analysis, you would typically:

1.  **Mount Google Drive**: Ensure your Google Drive is mounted and `survey.csv` is located at `/content/drive/MyDrive/Finding/survey.csv`.
2.  **Install Libraries**: Ensure all necessary libraries (pandas, numpy, matplotlib, seaborn, scikit-learn) are installed in your environment.
3.  **Execute Cells**: Run the cells sequentially as presented in the Jupyter/Colab notebook.

```python
# Example of loading data
import pandas as pd
train_df = pd.read_csv('/content/drive/MyDrive/Finding/survey.csv')
```
