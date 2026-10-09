# Machine Learning

Coursework from the Machine Learning and Deep Learning modules of the Data Science postgraduate program at Instituto Tecnológico de Costa Rica (ITCR), 2023. Notebooks are written in Spanish.

| Notebook | Problem | Techniques |
|---|---|---|
| `Data Preprocessing.ipynb` | Clean and prepare a tabular dataset | Mean imputation, IQR outlier treatment, one-hot encoding |
| `Quiz 1 Data Preprocessing.ipynb` | Exploratory analysis and preprocessing | Categorical encoding, missing-value imputation, scaling |
| `Decision trees & Random Forest.ipynb` | Binary classification (diabetes dataset) | Decision trees, random forest, multilayer perceptron (PyTorch) |
| `Regression Analysis DL.ipynb` | Predict abalone age ([Abalone dataset](https://www.kaggle.com/rodolfomendes/abalone-dataset)) | MLP regression and single-layer perceptron in PyTorch, Ridge regression |
| `Deep Learning CNN.ipynb` | Classify facial emotions ([Human Face Emotions](https://www.kaggle.com/datasets/sanidhyak/human-face-emotions)) | Convolutional neural network (PyTorch, torchvision) |
| `AAPL Time Series Analyis Model Comp.ipynb` | Model Apple stock closing prices | Decomposition, ADF stationarity test, model comparison (statsmodels, XGBoost) |
| `Final Project Comparison Between Regression Algortihms.ipynb` | Predict house prices in Sydney ([dataset](https://www.kaggle.com/datasets/mihirhalai/sydney-house-prices)) | Comparison of regression algorithms (scikit-learn, PyTorch) |

## Stack
Python, pandas, NumPy, scikit-learn, PyTorch, statsmodels, XGBoost, matplotlib, seaborn.

## Running the notebooks
Datasets are not included in this repository; download them from the linked sources and update the file paths in the first cells.

```bash
pip install pandas numpy scikit-learn torch torchvision statsmodels xgboost matplotlib seaborn jupyter
jupyter notebook
```
