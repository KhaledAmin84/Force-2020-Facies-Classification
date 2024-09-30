# **Facies Classification Force2020**

This repository contains a Jupyter Notebook that demonstrates facies classification using various machine learning algorithms. It also incorporates data augmentation techniques and hyperparameter tuning for improved model performance.
---

## **Key Features**

- **Data Preprocessing**: Loading and processing well log data, handling missing values, and scaling features.

* Machine Learning Models:

    * Random Forest
    * XGBoost
    * K-Nearest Neighbors (KNN)
    * Decision Trees
    * Neural Networks using TensorFlow and Keras
* **Model Tuning**: Hyperparameter optimization using GridSearchCV.
* **Evaluation Metrics**: Accuracy, confusion matrix, classification report.

## **Installation**
To run this notebook, install the required libraries using the following commands:

```
pip install tensorflow
pip install xgboost
pip install lasio
pip install plotly
pip install scikit-learn
```
## **Notebook Structure**

1. **Installation and Setup**: Install necessary packages and libraries.
2. **Data Preprocessing**: Load and clean the dataset, handle missing values, and augment the data.
3. **Modeling**: Train several classifiers (Random Forest, XGBoost, Neural Networks, etc.) and evaluate performance.
Hyperparameter Tuning: Use grid search to fine-tune model parameters.
4. **Evaluation**: Use accuracy, confusion matrices, and classification reports to compare model performance.

## **Data**
Petrel ready files and standard well log las files, all csv file data. The folder is called FORCE 2020 lithofacies prediction from well logs competition (https://drive.google.com/drive/folders/0B7brcf-eGK8CRUhfRW9rSG91bW8)

## **How to Use**
1. Clone the repository:
```
git clone https://github.com/your-username/facies-classification.git
```
2. Navigate to the repository directory and open the Jupyter Notebook:
```
jupyter notebook Force2020_Facies_Classification.ipynb
```
## **Results**
* Models like RandomForest and XGBoost achieve the highest accuracy with default parameters.
* Further improvements can be achieved through grid search and fine-tuning hyperparameters.

## **License**
This project is licensed under the MIT License.


