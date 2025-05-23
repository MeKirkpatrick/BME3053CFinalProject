# BME3053CFinalProject

# Liver Disease Prediction Project

This project aims to develop machine learning models to predict liver disease in Indian patients exposed to air pollution. The dataset used for this project is sourced from Kaggle and contains patient records with various features.

## Demo
https://nam10.safelinks.protection.outlook.com/?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D7HroOOyBq5o&data=05%7C02%7Cm.kirkpatrick1%40ufl.edu%7C36b5fcc5ccb64d11465b08dd854d670b%7C0d4da0f84a314d76ace60a62331e1b84%7C0%7C0%7C638813289846847130%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=74pvskf%2BjnGWE54bScVxDn52ITv97RPgXarsDY3XUXM%3D&reserved=0

## Dataset

- **Source**: [Indian Liver Patient Records Dataset](https://www.kaggle.com/datasets/uciml/indian-liver-patient-records)
- **File**: `indian_liver_patient.csv` (extracted from `Group7_data.zip`)
- **Description**: The dataset contains patient records with features such as age, gender, total bilirubin, and more, along with a target variable indicating liver disease presence.

## Objectives

1. Preprocess the dataset by handling missing values and encoding categorical variables.
2. Visualize the dataset using correlation heatmaps.
3. Train and evaluate two machine learning models:
   - Logistic Regression
   - Random Forest
4. Compare the models' performance using accuracy scores and confusion matrices.
5. Identify misclassified examples and rank the models by test accuracy.

## Project Structure

- **`Project.ipynb`**: Jupyter Notebook containing the code for data preprocessing, visualization, model training, evaluation, and comparison.
- **`Group7_data.zip`**: Compressed file containing the dataset.

## Steps in the Notebook

1. **Data Loading**: Extract and load the dataset from the zip file.
2. **Data Exploration**: Print dataset characteristics (shape, columns, missing values, etc.).
3. **Data Visualization**: Generate a correlation heatmap to understand feature relationships.
4. **Data Splitting**: Split the dataset into training (80%) and testing (20%) sets.
5. **Model Training**:
   - Train a Logistic Regression model.
   - Train a Random Forest model.
6. **Model Evaluation**:
   - Evaluate models using accuracy, classification reports, and confusion matrices.
   - Visualize misclassified examples.
7. **Model Comparison**: Compare the models' performance using a bar plot and rank them by accuracy.

## Results

- The models are evaluated based on their accuracy and confusion matrices.
- The best-performing model is determined by its test accuracy.

## Starter Code Source:

https://www.kaggle.com/code/ranusharma09/starter-indian-liver-patient-records-870937e6-4 

## Dependencies

The following Python libraries are required to run the notebook:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install the dependencies using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn


