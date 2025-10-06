# DECISION-TREE-IMPLEMENTATION
COMPANY : CODTECH IT SOLUTIONS

NAME : Yanaganti Anjali

INTERN ID : CT06DY2092

DOMAIN : Machine Learning

DURATION : 6 WEEKS

MENTOR : NEELA SANTOSH
# DESCRIPTION
This project presents a supervised machine learning approach to classify breast cancer tumors as malignant or benign using a Decision Tree Classifier. The model is implemented in Python using the Scikit-learn library and trained on the built-in Breast Cancer Wisconsin Diagnostic Dataset, a well-known benchmark dataset in the medical and machine learning community.

A decision tree is a flowchart-like structure in which each internal node represents a test on a feature, each branch represents an outcome of the test, and each leaf node represents a class label. This type of model is highly interpretable and easy to visualize, making it ideal for healthcare-related problems where transparency is important.

🧬 Dataset Information The dataset used in this project is loaded using Scikit-learn’s load_breast_cancer() function. It contains 569 samples with 30 numerical features derived from digitized images of breast mass cell nuclei. Each sample is labeled as either:

0: malignant (cancerous) 1: benign (non-cancerous) Features include mean, standard error, and worst-case values for measurements such as radius, texture, perimeter, area, smoothness, compactness, and more.

The dataset is already cleaned and does not require any missing value handling, allowing a smooth workflow directly from feature extraction to model training.

# RESULTS
The decision tree was able to achieve high accuracy on the test set, demonstrating its ability to generalize well on new data. The visualization provides transparency into how the model makes predictions, which is crucial in sensitive applications like medical diagnosis.
