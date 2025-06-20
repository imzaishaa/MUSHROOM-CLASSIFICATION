# MUSHROOM-CLASSIFICATION
A machine learning project to classify mushrooms as edible or poisonous using a cleaned dataset. Includes data preprocessing, exploratory analysis, feature encoding, model training with various classifiers (e.g., Decision Tree, Random Forest), and accuracy evaluation. Built using Python, pandas, and scikit-learn.
Here’s a complete `README.md` for your **Mushroom Classification** project:

---

# Mushroom Classification

This project aims to classify mushrooms as **edible** or **poisonous** based on various features using machine learning models. The dataset used is pre-cleaned and includes categorical data describing mushroom characteristics such as cap shape, color, odor, gill size, etc.

## Features

* Data loading and preprocessing using `pandas` and `NumPy`
* Exploratory Data Analysis (EDA)
* Feature encoding (Label Encoding / One-Hot Encoding)
* Splitting dataset into training and test sets
* Model training using:

  * Decision Tree
  * Random Forest
  * Support Vector Machine (SVM)
  * Logistic Regression
* Accuracy evaluation and comparison of models

## Dataset

The dataset used is a cleaned version of the [UCI Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/Mushroom), stored as `mushroom_cleaned.csv`.

## Requirements

* Python 3.x
* pandas
* numpy
* scikit-learn
* matplotlib (optional, for visualization)
* seaborn (optional)

Install dependencies using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/mushroom-classification.git
   cd mushroom-classification
   ```

2. Open and run the Jupyter Notebook:

   ```bash
   jupyter notebook MUSHROOM_CLASSIFICATION.ipynb
   ```

## Results

The models were evaluated using accuracy metrics. Random Forest and Decision Tree provided the best results with high classification accuracy.

