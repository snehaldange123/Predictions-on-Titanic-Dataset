# Predictions on Titanic Data

# Prediction on Titanic Dataset by using Logistic Regression  and Decision Tree model

- The project aims to create prediction models for the Titanic dataset using Logistic Regression and Decision Tree algorithms. The Titanic dataset contains information about passengers on the Titanic, including features such as age, gender, ticket class, and whether they survived the disaster.
- The goal is to build models that predict whether a passenger survived or not based on these features. Logistic Regression is a linear model suitable for binary classification tasks, while Decision Trees are non-linear models that can capture complex relationships between features.
- The project will involve data preprocessing, exploratory data analysis (EDA), model selection, training, evaluation, and comparison of Logistic Regression and Decision Tree models. The performance of each model will be assessed using metrics such as accuracy, precision, recall, and F1-score. Additionally, visualizations will be provided to illustrate the results and insights gained from the analysis.

## Dataset

 the dataset used for this project is the Titanic dataset,which contains 891 records and 12 columns and including its source, features, and target variable (survived/not survived).

## Requirements

Python 3.x
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

## Approach 

1. Data Preprocessing : Handling missing values , Encoding categorical variables,Feature scaling or normalization

2.Model Selection :
-  Explanation of Logistic Regression and Decision Tree algorithms.
- Suitability of each model for binary classification tasks like survival prediction

3. Model Training : 
 - Splitting the data into training and testing sets
 - Model fitting using the training data

4. Model Evaluation : Accuracy, precision, recall, F1-score,ROC curve and AUC score

5. Results and Comparison : 
-Which model performs better for the Titanic survival prediction task
- Insights gained from the analysis

## Files Included
Prediction On Titanic Data.ipynb 

Titanic-Dataset.csv


## Usage : 

clone the repository
install the required dependencies mentioned in the requirements.
Open the Jupyter Notebook Prediction On Titanic Data.ipynb 
Follow the instructions provided in the notebook to run the code cells.

## Conclusion

Logistic Regression:

Achieved 78.77% accuracy.
Fairly good precision, recall, and F1-score.
Key features: passenger class, gender.

Decision Tree Model:

Achieved 78.21% accuracy.
Fairly good precision, recall, and F1-score.
Key features: age, number of family members.

model is performing good for both classes.
