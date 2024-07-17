# Cirrhosis Disease Prediction in ILPD

## 1. Introduction

This Jupyter Notebook aims to develop predictive models for to detect cirrhosis using the [Indian Liver Patient Dataset](https://archive.ics.uci.edu/dataset/225/ilpd+indian+liver+patient+dataset). The notebook covers various stages of data preprocessing, exploratory data analysis (EDA), model building, hyperparameter tuning, and model evaluation. This data set contains records of 416 patients diagnosed with liver disease and 167 patients without liver disease. This information is contained in the class label named 'Selector'.  There are 10 variables per patient: age, gender, total Bilirubin, direct Bilirubin, total proteins, albumin, A/G ratio, SGPT, SGOT and Alkphos. Of the 583 patient records, 441 are male, and 142 are female. 

## Table of Contents

1. [Introduction](#Introduction)
2. [Data & Preprocessing](#Data-&-Preprocessing)
3. [Exploratory Data Analysis (EDA)](#Exploratory-Data-Analysis-(EDA))
4. [Model Building](#Model-Building)
5. [Model Evaluation](#Model-Evaluation)
6. [Conclusion](#Conclusion)
7. [Installation](#Installation)

## 2. Data & Preprocessing

- **Main Characteristics**: Description of the dataset, including features and target variable.
- **Handling Missing Values**: Techniques used to handle missing data.
- **Data Cleaning and Preprocessing**: Steps to clean and preprocess the data, including feature engineering, encoding, normalization, and data splitting.

## 3. Exploratory Data Analysis (EDA)

- **Insights**: Key insights from EDA, including feature distributions and correlations.
- **Visualizations**: Important visualizations to understand the dataset better.

## 4. Model Building

- **Model Selection**: Overview of chosen models (Logistic Regression, SVM, Random Forest) and reasons for selection.
- **Hyperparameter Tuning**: Details on hyperparameter tuning using GridSearchCV.

## 5. Model Evaluation

- **Evaluation Metrics**: Metrics used to evaluate the models, such as F1 score, precision, recall, and AUC ROC.
- **Comparison**: Detailed comparison of model performance based on evaluation metrics.

## 6. Conclusion

Summary of the analysis and model results, including recommendations for further tests and potential future work.

## 7. Installation

To run this Jupyter Notebook, you need to install the required libraries. Follow the steps below:

1. **Clone the repository** (if applicable) or download the notebook to your local machine.

2. **Navigate to the directory** containing the `requirements.txt` file.

3. **Create a virtual environment** (optional but recommended):

   bash
   ```
   python -m venv env
   ```

 3.5 Activate the virtual environment:

On Windows:

bash
```
.\env\Scripts\activate
```
On macOS and Linux:

bash
```
source env/bin/activate
```

4. **Install the required libraries using requirements.txt:**

bash
```
pip install -r requirements.txt
```
5. Start Jupyter Notebook:

bash
```
jupyter notebook
```

5. Open the Notebook: Navigate to the directory where the notebook is located and open it.
