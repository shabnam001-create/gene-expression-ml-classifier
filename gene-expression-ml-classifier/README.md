**Gene Expression Classification using Machine Learning**



**Overview**



This project implements a machine learning pipeline to classify tumor samples as benign or malignant based on cellular features.



**Dataset**

\-Breast Cancer Dataset

\-Features represent cellular morphology (size, shape, chromatin, etc.)

**Workflow**

\-Data preprocessing (handling missing values)

\-Feature scaling

\-Model training (Random Forest)

\-Evaluation:

\-Accuracy

\-ROC Curve (AUC score)

\-Feature importance analysis

**Results**

\-Accuracy: \~97–98%

\-AUC Score: \~0.99

**Key Insights**

\-Important features:

&#x09;Cell size

&#x09;Bare nuclei

&#x09;Cell shape

These align with known biological indicators of cancer.

**Tools Used**

Python

Pandas, NumPy

Scikit-learn

Matplotlib

**How to Run**



\-Install dependencies:



pip install -r requirements.txt



\-Run the notebook:



notebooks/ml\_analysis.ipynb



**Author**



Shabnam Devi

