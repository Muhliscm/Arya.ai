


# Arya.ai


Data science assignment arya.ai

#### -- Project Status: [Completed]

## Project Intro/Objective
Create a binary classification model

![Data Science](https://img.shields.io/badge/%20-%20Data%20Science-blueviolet?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/%20-Machine%20Learning-important?style=for-the-badge)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)

### Methods Used

* Machine Learning
* Data Visualization
* Predictive Modeling
* Deep learning
* etc.

### Technologies
* Python
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit learn
* VScod
* Keras
* Tensorflow
* jupyter notebook
* etc. 


## Featured Notebooks/Analysis/Deliverables

-- EDA Notebook [here](https://github.com/Muhliscm/Arya.ai/blob/main/Arya.ai.ipynb)
  - Data is highly skewed
  - No null values
  - Majoriy columns have more than 50 % zeros
  - Not much details on domain specific information
  - Dependant variable have 60:40 occurance (Not much unbalanced)

-- Future selection method applied:
  * Mutual inormation gain
  * K-best - selected top 10 columns based on information gain
  
-- Feature scaling
 * Standard scaler

-- Created models 
1. Logistic regression script [here](https://github.com/Muhliscm/Arya.ai/blob/main/logistic_regression.ipynb)
2. svm script [here](https://github.com/Muhliscm/Arya.ai/blob/main/svm.ipynb)
3. Decision Tree script [here](https://github.com/Muhliscm/Arya.ai/blob/main/Decision_tree.ipynb)
4. Random forest script [here](https://github.com/Muhliscm/Arya.ai/blob/main/Random_forest.ipynb)
5.Random forest with future selection [here](https://github.com/Muhliscm/Arya.ai/blob/main/random_forest_with_future_selection.ipynb)
6. ANN [here](https://github.com/Muhliscm/Arya.ai/blob/main/ANN.ipynb)

-- Perfomance analysis :
  - Hard to apply other metics because of lack of domain information:
  
    metrics used - accuracy, confusion matrix
  
  1. Logistic regression                  : 86 %
  2. svm                                  : 90 %
  3.Decision Tree                         : 86.5%
  4.Random forest                         : 94.4%
  5.Random forest with future selection   : 92 %
  6.ANN                                  : 94.2 %

 model selected : random forest based on accuracy
 
  -- Random forest Notebook with prediction [here](https://github.com/Muhliscm/Arya.ai/blob/main/Random_forest.ipynb)
 
 predicted test results [here](https://github.com/Muhliscm/Arya.ai/blob/main/predicted_test_results.csv)
 



