# Parkinson's Disease Detection

## Introduction
This project aims to detect Parkinson's disease using machine learning techniques. Parkinson's is a neurodegenerative disorder affecting movement, and early detection can significantly impact treatment outcomes.

## Dataset
The dataset used in this project is sourced from Kaggle and includes acoustic features extracted from phonemic recordings of individuals with and without Parkinson's disease. It also contains demographic information and a label indicating the presence of the disease

## Dependencies
- Python 3
- Jupyter Notebook
- Libraries: numpy, pandas, scikit-learn, seaborn, matplotlib

## Usage
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd Parkinson-Disease-Detection`
3. Install dependencies
4. Open and run the Jupyter Notebook: `jupyter notebook notebook.ipynb`

## Methods
1. **Exploratory Data Analysis (EDA):** Visualized feature distributions, checked skewness, and explored correlations.
2. **Data Preprocessing:** Removed irrelevant columns, scaled features, and split data for training and testing.
3. **Modeling:** Trained a Random Forest Classifier, evaluated performance using accuracy and recall scores, and visualized results with a confusion matrix.

## Results
The Random Forest Classifier achieved over 80% accuracy in detecting Parkinson's disease based on acoustic features.
