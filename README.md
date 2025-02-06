# Sales Call Uptake Classification

This project uses and compares different classical machine learning models to predict whether a sales call will be accepted based on numerous input features. The workflow—from data exploration and preprocessing to model training, evaluation, and hyperparameter tuning—is implemented in a Jupyter Notebook.

## Project Structure

- **[main.ipynb](main.ipynb):** Contains the entire analysis workflow, including:
  - Exploratory Data Analysis (EDA)
  - Data pre-processing (train-test split, categorical encoding, numerical standardization)
  - Model training (logistic regression, XGBoost, and various sklearn classifiers)
  - Model evaluation (confusion matrix, ROC curves, accuracy metrics)
  - Feature selection and model retraining
  - Integration with Weights & Biases (wandb) for experiment tracking and hyperparameter sweeps
- **[LICENSE](LICENSE):** MIT License.
- **[.gitignore](.gitignore):** Lists files and directories to ignore, including caches, virtual environments, and test artifacts.
- **[README.md](README.md):** Project documentation.

## Prerequisites

- Python 3.10 or later
- Jupyter Notebook or VS Code with Jupyter support
- Required libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - `wandb`
  - `xgboost`
  - (and any additional dependencies used in [main.ipynb](main.ipynb))



## Running the Notebook  
Open main.ipynb in Jupyter Notebook or via VS Code and execute the cells sequentially. The notebook covers:

**EDA:** Understand data characteristics.  
**Data Pre-processing:**  
- Encode categorical features (and address warnings from replace operations).  
- Standardize numerical features using StandardScaler.  
- Split data into training, validation, and test subsets.

**Model Training and Evaluation:**  
- Train multiple classifiers.  
- Evaluate models using metrics like accuracy, ROC AUC, and confusion matrices.  
- Visualize results including model comparisons and feature importance.

**Hyperparameter Tuning:**  
- Use wandb to perform hyperparameter sweeps and track experiments.

## Project Highlights  
- Comprehensive Workflow: From data ingestion to model retraining using selected features.  
- Visualization: In-depth visualizations for EDA and model performance (violin plots, histograms, ROC curves, etc.).  
- Experiment Tracking: Integration with wandb for managing model experiments and hyperparameter tuning.  
- Modular Design: Functions for encoding, scaling, and model evaluation are embedded throughout the notebook, offering flexibility for future improvements.