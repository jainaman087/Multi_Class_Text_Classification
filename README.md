# Consumer Complaint Analysis


## Overview

This Jupyter Notebook contains scripts and analysis for exploring consumer complaints data and implementing machine learning models for classifying consumer complaints into predefined product categories.





## Installation

- Python 3.x
- pandas
- numpy
- wordcloud
- matplotlib
- seaborn
- fuzzywuzzy
- python-Levenshtein
- scikit-learn
- nltk
- xgboost
## File Structure

Consumer_Complaints_EDA_and_Multi_Class_Text_Classification.ipynb: Main Python script

### Explanation of Python Scripts-

### Sections-
### 1. Exploratory Data Analysis (EDA):

In this section, we perform exploratory data analysis on the consumer complaints dataset. We visualize various aspects of the data to gain insights and understand patterns.

### 2. Pattern Matching

This section focuses on pattern matching techniques applied to consumer complaints narratives and their corresponding product categories. We utilize fuzzy string matching algorithms to find similarities between product names and complaint narratives.

### 3.  Machine Learning Approaches

In this section, we implement two machine learning approaches for classifying consumer complaints into predefined product categories.


## Exploratory Data Analysis (EDA)- 
- We start by importing necessary libraries and reading the dataset.
- We perform data cleaning tasks such as removing duplicates and handling missing values.
- Visualizations include time series plots of complaints over time, distribution of complaints by product and state, correlation matrix, and more.
- We also generate word clouds to visualize common words in consumer complaint narratives, and analyze the relationship between product categories and consumer responses.


## Pattern Matching-
- We utilize fuzzy string matching techniques to find similarities between product names and consumer complaint narratives.
- Word clouds are generated based on the matched words between product names and complaint narratives to visualize commonalities.


## Machine Learning Approaches:- 
### Approach 1:
- Classifying consumer complaint narratives into predefined product categories using various machine learning models.
- Models include RandomForest, LinearSVC, MultinomialNB, and LogisticRegression.
- Text Preprocessing have been incorporated.
- Performing a cross-validation analysis.
- Evaluation metrics include accuracy scores, classification reports, confusion matrices, and cross-validation analysis.


### Approach 2:
- Classifying consumer complaints using Decision Tree Classifier, Random Forest Classifier, and XGBoost Classifier.
- Text vectorization techniques are employed to convert textual data into numerical format for model training.
- Accuracy scores are computed for each model to evaluate performance.

## Conclusion
This analysis provides valuable insights into consumer complaints data and demonstrates the effectiveness of machine learning models in classifying complaints into predefined product categories. By leveraging EDA techniques, pattern matching, and machine learning algorithms, organizations can better understand consumer grievances and improve customer satisfaction.



