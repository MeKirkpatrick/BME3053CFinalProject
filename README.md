# BME3053CFinalProject

# Liver Disease Prediction Project

This project aims to develop machine learning models to predict liver disease in Indian patients exposed to air pollution. The dataset used for this project is sourced from Kaggle and contains patient records with various features.

## Demo
INCLUDE LINK TO VIDEO DEMO HERE

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

## Starter Code Source:

https://www.kaggle.com/code/ranusharma09/starter-indian-liver-patient-records-870937e6-4 
