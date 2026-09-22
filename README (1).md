# Diabetic Patient Readmission Prediction

## Project Overview

This project focuses on analyzing diabetic patient data and predicting hospital readmission. It includes exploratory data analysis (EDA), data preprocessing, feature engineering, encoding, handling class imbalance, and the implementation and comparison of multiple machine learning models.

The objective is to identify patterns in diabetic patient and hospital encounter data and evaluate different machine learning approaches for predicting readmission.

## Dataset

**Dataset:** Diabetes Prediction Dataset

**Source:** [Kaggle - Diabetes Prediction Dataset](https://www.kaggle.com/datasets/nguynnhkhang/diabetes-prediction-dataset)

The project uses the `diabetic_data.csv` file from the dataset. It contains patient and hospital encounter information, including demographic details, hospital information, laboratory results, medications, and readmission status.

> **Note:** The dataset is not included in this repository. Please download it from the Kaggle link above before running the notebook.

## Technologies Used

* **Python** - Programming language
* **Pandas** - Data manipulation and analysis
* **NumPy** - Numerical operations
* **Matplotlib** - Data visualization
* **Seaborn** - Exploratory data analysis and visualization
* **Scikit-learn** - Machine learning models and evaluation
* **Imbalanced-learn (imblearn)** - SMOTE for handling class imbalance
* **XGBoost** - Gradient boosting classification

## Machine Learning Models

The project evaluates multiple machine learning approaches:

* **Logistic Regression**

  * Class-weighted Logistic Regression
  * Logistic Regression with SMOTE
  * SMOTE with uniform threshold tuning
  * SMOTE with class-specific threshold tuning
* **Decision Tree Classifier**
* **Random Forest Classifier**
* **XGBoost Classifier**
* **Support Vector Machines (SVM)**

  * Fast Linear SVM
  * Polynomial kernel
  * RBF kernel
  * Sigmoid kernel

## Model Evaluation

The models are compared using:

* Accuracy
* Precision
* Recall
* F1-score
* AUC

Based on the comparative results in the project notebook, **XGBoost** achieved the highest reported accuracy of **0.5711** and weighted AUC of **0.6475** among the models tested.

The **Fast Linear SVM** also showed competitive performance, with an accuracy of **0.5521** and weighted AUC of **0.6270**.

The kernel-based SVM models showed lower performance and encountered convergence warnings, indicating that further tuning or different scaling approaches could be explored.

## Project Structure

```text
Diabetic-Patient-Readmission-Prediction/
│
├── Nandana_DiabeticReadmission.ipynb
├── requirements.txt
├── Nandana_ProjectReport.docx
└── README.md
```

## Setup and Run Instructions

### 1. Clone the Repository

```bash
git clone <your-github-repository-link>
cd <your-repository-name>
```

### 2. Install the Required Libraries

Make sure Python is installed, then run:

```bash
pip install -r requirements.txt
```

### 3. Download the Dataset

Download the `diabetic_data.csv` file from the [Kaggle dataset](https://www.kaggle.com/datasets/nguynnhkhang/diabetes-prediction-dataset).

Place the dataset in the location expected by the notebook.

### 4. Run the Project

Open the `.ipynb` file using:

* Jupyter Notebook / JupyterLab
* Google Colab
* VS Code with the Python extension

Run the notebook cells sequentially.

## Project Files

* **Code File:** Jupyter Notebook containing the complete project implementation
* **Requirements File:** List of Python libraries required to run the project
* **Project Report:** Detailed documentation of the project
* **README:** Project overview, dataset information, technologies, setup instructions, and results

## Author

**Nandana M**

B.Sc. (Hons) Data Science & Analytics


