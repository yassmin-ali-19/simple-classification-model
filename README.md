# Breast Cancer Classification Project
**📌 Overview**

This project aims to classify breast cancer tumors as benign or malignant using machine learning techniques. The dataset is analyzed, visualized, preprocessed, and then modeled to evaluate classification performance.

**📂 Project Structure**
* Breast_Cancer_Classification_Project.ipynb → Jupyter Notebook containing the full workflow:

* Data loading and cleaning

* Exploratory data analysis (EDA)

* Feature preprocessing and scaling

* Train-test split

* Model training and evaluation

**🛠️ Technologies Used**

* Python 3.x

* Libraries:

* pandas → data manipulation

* numpy → numerical computations

* matplotlib, seaborn → data visualization

* scikit-learn → preprocessing, train-test split, classification models, evaluation

**📊 Dataset**

The dataset contains various cell nucleus features computed from digitized images of breast cancer biopsies.
Key features include:

* radius_mean, texture_mean, perimeter_mean, area_mean, etc.

* Target: Diagnosis (M = Malignant, B = Benign)

**🚀 Workflow**

1. Data Investigation → Checking dataset shape, missing values, unique classes.

2. Data Visualization → Correlation heatmaps, feature distributions.

3. Data Preprocessing → Handling missing values, encoding labels, feature scaling.

4. Train-Test Split → Stratified sampling to maintain class balance.

5. Model Training → Logistic Regression, etc.

6. Evaluation → Accuracy, ROC curve, AUC score, confusion matrix.

**📈 Results**

* The model classifies tumors with high accuracy.

* ROC curve and AUC score were computed to evaluate model performance.

* Analysis of false positives vs false negatives is included, with discussion of medical consequences.

**⚠️ Medical Context**

 * False Positive → Healthy patient misclassified as having cancer → unnecessary stress and tests.

* False Negative → Cancer patient misclassified as healthy → more dangerous, as treatment may be delayed.

* In this project, minimizing false negatives is the main priority.

**▶️ How to Run**

1. Clone this repository or download the notebook.

2. *Install dependencies:*

`` pip install pandas numpy matplotlib seaborn scikit-learn ``


3. Open the notebook in Jupyter:

`` jupyter notebook Breast_Cancer_Classification_Project.ipynb``


4. Run all cells to reproduce the workflow.
