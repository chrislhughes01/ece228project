# Cardiovascular Disease Risk Prediction (ECE 228 Final Project) #

This project applies machine learning techniques to predict 10-year cardiovascular disease (CVD) risk using the Framingham Heart Study dataset. We reimplemented the MaLCaDD framework and extended it with regularized neural networks, SMOTE augmentation, and ensemble learning to better handle data imbalance and improve model performance.

## Project Overview ##

The main goal of this project was to explore and compare different approaches for CVD prediction using machine learning. We focused on:

- Reproducing and analyzing the MalCaDD framework
- Investigating class imbalance and SMOTE oversampling
- Training a custom MLP with L2 regularization and dropout
- Comparing baseline models like KNN
- Combining models using ensembling to boost F1 score and recall

## Repository Structure ##

### Main Files ###

- `framingham.csv`: The primary dataset used for training and evaluation. This dataset includes features like age, cholesterol, blood pressure, smoking status, and more.
- `FinalSubmissionScript.ipynb`: The main notebook that includes:
    - Data preprocessing
    - Feature selection and correlation
    - MLP model training and evaluation
    - Grid search over SMOTE ratios
    - Baseline model training
    - Ensemble voting implementation
    - Final test results and evaluation

### Other Notebooks (Exploration) ###

These files represent intermediate versions or different approaches we tested during development:
- `MLP.ipynb`, `MLP_heart_disease_test.ipynb`, `MLP_heart_disease_test_fram_extended.ipynb`: Early experiments with heart disease datasets and MLP variations.
- `SSDA.ipynb`, `SSDA_new.ipynb`: Prototype notebooks using semi-supervised domain adaptation, which we did not end up using in the final model.

### Other Data Files ###
- `framingham_selected.csv`, `framingham_extended.csv`: Feature-selected or extended versions of the Framingham dataset used in earlier experiments.
- `heart_disease.csv`, `heart_disease_fixed.csv`, `heart_disease_selected.csv`: Variants of the Cleveland Heart Disease dataset used in our cross-dataset testing but not included in the final model.

## How to Run ##

Repository link: https://github.com/chrislhughes01/ece228project.git

1. Clone this repository:
```bash
git clone https://github.com/chrislhughes01/ece228project.git
```

2. Open and run:
```bash
jupyter notebook FinalSubmissionScript.ipynb
```

3. Click "Kernel --> Restart Kernel and Run All Cells..."