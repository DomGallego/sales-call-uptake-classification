# Sales Call Uptake Classification

This project leverages machine learning to predict whether a sales call will be accepted based on numerous input features. The workflow—from data exploration and preprocessing to model training, evaluation, and hyperparameter tuning—is implemented in a Jupyter Notebook.

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

## Getting Started

### Prerequisites

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

> **Note:** Consider creating a `requirements.txt` to manage these dependencies.

### Installation

Clone the repository and install the required packages:

```sh
git clone <repository-url>
cd sales-call-uptake-classification
pip install -r requirements.txt
```

