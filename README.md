# Breast Cancer Prediction: a beginner machine learning project

A beginner-friendly machine learning project that predicts whether a breast tumor is **malignant** or **benign** from measurements of cell nuclei.

## Dataset

This project uses the **Breast Cancer Wisconsin (Diagnostic)** dataset, available directly in scikit-learn (`sklearn.datasets.load_breast_cancer`) and on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic).

- 569 samples
- 30 numeric features (radius, texture, perimeter, area, smoothness, etc.)
- 2 classes: malignant (0) and benign (1)

## Project steps

1. Load and explore the data
2. Clean and preprocess (scaling, train/test split)
3. Train a **Logistic Regression** classifier
4. Evaluate with accuracy, precision, recall, F1-score and a confusion matrix

## Installation

```bash
git clone https://github.com/bouguerraimen/Cancer-Prediction.git
cd Cancer-Prediction
python -m venv venv
venv\Scripts\activate        # Windows
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage

Run the main script or open the notebook:

```bash
jupyter notebook "Breast Cancer Prediction.ipynb"
```

## Results

| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 93%      |


