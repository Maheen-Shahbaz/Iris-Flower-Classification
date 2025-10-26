# Iris Flower Classification

## Project Overview
This project classifies **Iris flowers** into three species:  
- `setosa`  
- `versicolor`  
- `virginica`  

Based on four features:  
- Sepal length (cm)  
- Sepal width (cm)  
- Petal length (cm)  
- Petal width (cm)  

We use **machine learning** to predict the species. The notebook demonstrates the **complete workflow** from loading data to model evaluation.


## Dataset
- File: `iris.csv` (included)  
- Source: [Kaggle Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)  
- 150 samples with 5 columns:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
  - `species` (target)

> Note: The notebook automatically handles variations in column name (e.g., `class` → `species`) so it works with different CSV versions.


## Notebook Overview
The notebook `Iris_Flower_Classification.ipynb` is divided into **clear cells**:

1. **Import Libraries** – all required Python libraries  
2. **Load Dataset** – read CSV and standardize column names  
3. **Explore Data** – check info, summary, class distribution, pairplot  
4. **Preprocess Data** – feature scaling, train-test split  
5. **Train Models** – Logistic Regression (baseline), Random Forest (advanced)  
6. **Evaluate Models** – accuracy, confusion matrix, classification report  
7. **Feature Importance** – Random Forest visualization  
8. **Conclusion** – key insights and most important features

## Requirements
Python >=3.8 with the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

## How to Run

1. Clone or download the repository.
2. Make sure `iris.csv` is in the same folder as the notebook.
3. Open `Iris_Flower_Classification.ipynb` in **Jupyter Notebook** or **VS Code**.
4. Run all cells sequentially to reproduce results.



