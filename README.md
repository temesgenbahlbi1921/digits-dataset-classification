# Handwritten Digits Classification

## Overview
A machine learning project that classifies handwritten digits (0–9) using the scikit-learn Digits dataset.

## Dataset
- 1,797 handwritten digit samples
- 64 pixel-intensity features per image
- 10 classes (digits 0–9)
- Dataset loaded directly from `sklearn.datasets.load_digits()`

## Machine Learning Models
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Decision Tree
- Support Vector Machine (linear SVM)

## Methodology
1. Load and explore the dataset.
2. Split the data into training and testing sets (80/20).
3. Scale features using StandardScaler.
4. Train and evaluate five classification models.
5. Compare accuracy, precision, recall, F1-score, and confusion matrices.

## Reported Results

| Model | Accuracy |
|---|---:|
| KNN | 97.5% |
| Linear SVM | 97.5% |
| Logistic Regression | 97.2% |
| Decision Tree | 84.2% |
| Naive Bayes | 76.7% |

*Results are reported in the accompanying project report.*

## Repository Structure

- `notebooks/` — Jupyter notebook
- `reports/` — Project report in PDF format
- `requirements.txt` — Python dependencies
- `.gitignore` — Files excluded from version control

## Installation

```bash
pip install -r requirements.txt
```

## Run the Project

```bash
jupyter notebook notebooks/digits.ipynb
```

Run the notebook cells in order to reproduce the analysis.

## Future Improvements
- Evaluate an RBF-kernel SVM.
- Use cross-validation.
- Explore Principal Component Analysis (PCA).
- Test ensemble models.

## Acknowledgment
Dataset provided by scikit-learn.

## Author
Temesgen Bahlbi
