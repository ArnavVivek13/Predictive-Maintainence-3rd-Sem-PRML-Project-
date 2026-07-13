# Predictive-Maintainence-3rd-Sem-PRML-Project

## Set Up a Python Project (requirements.txt)
### Note: **Do all of this in VS Code terminal**

### 1. Install Python

Make sure Python is installed:

```bash
python --version
```

or

```bash
python3 --version
```

---

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

---

### 3. Activate Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

---

### 4. Install Requirements

```bash
pip install -r requirements.txt
```

---

### 5. Running the Code

This project consists of Jupyter notebooks for different machine learning models applied to predictive maintenance.

To run the notebooks:

1. Ensure Jupyter is installed (it should be included in requirements.txt).
2. Start Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

3. Open any of the `.ipynb` files in the browser interface that opens.
4. Run the cells in the notebook to execute the code.

---

## Project Overview

This project implements various machine learning algorithms for predictive maintenance using the AI4I 2020 Predictive Maintenance Dataset. The goal is to predict machine failures based on sensor data and operational parameters.

## File Explanations

- **Decision_tree.ipynb**: Implements a Decision Tree Classifier for predictive maintenance. Uses stratified 5-fold cross-validation, hyperparameter tuning with cost-complexity pruning, and evaluates performance using F2-score and confusion matrices.

- **Kernel_SVM.ipynb**: Implements a Support Vector Machine with RBF kernel for classification. Includes data preprocessing, cross-validation, and performance evaluation.

- **KNN.ipynb**: Implements K-Nearest Neighbors algorithm for predictive maintenance. Explores different values of k and evaluates model performance.

- **Logistic_Regression.ipynb**: Implements Logistic Regression for binary classification of machine failures. Includes feature preprocessing and model evaluation.

- **Random_Forest.ipynb**: Implements a Random Forest Classifier ensemble method. Uses multiple decision trees for improved accuracy and robustness.

- **requirements.txt**: Lists all Python dependencies required for the project, including scikit-learn, pandas, matplotlib, seaborn, and Jupyter.

- **data/ai4i2020.csv**: The dataset used for training and testing the models. Contains sensor readings and operational data from industrial machines.

- **README.md**: This file, containing setup instructions and project documentation.

## Package Requirements

The following packages are required for this project. They are listed in `requirements.txt` and can be installed using `pip install -r requirements.txt`:

```
asttokens==3.0.1
certifi==2026.2.25
click==8.3.1
cloudpickle==3.1.2
colorama==0.4.6
comm==0.2.3
contourpy==1.3.2
cycler==0.12.1
dask==2026.1.2
debugpy==1.8.20
decorator==5.2.1
exceptiongroup==1.3.1
executing==2.2.1
fonttools==4.62.0
fsspec==2026.2.0
importlib_metadata==8.7.1
ipykernel==7.2.0
ipython==8.38.0
jedi==0.19.2
Jinja2==3.1.6
joblib==1.5.3
jupyter_client==8.8.0
jupyter_core==5.9.1
kiwisolver==1.5.0
locket==1.0.0
MarkupSafe==3.0.3
matplotlib==3.10.8
matplotlib-inline==0.2.1
nest-asyncio==1.6.0
numpy==2.2.6
packaging==26.0
pandas==2.3.3
parso==0.8.6
partd==1.4.2
pillow==12.1.1
platformdirs==4.9.4
prompt_toolkit==3.0.52
psutil==7.2.2
pure_eval==0.2.3
Pygments==2.19.2
pyparsing==3.3.2
python-dateutil==2.9.0.post0
pytz==2026.1.post1
PyYAML==6.0.3
pyzmq==27.1.0
scikit-elm==0.21a0
scikit-learn==1.7.2
scipy==1.15.3
seaborn==0.13.2
six==1.17.0
```