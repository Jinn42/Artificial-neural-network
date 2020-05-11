# Adult Census Income Classification with EBM&SVM



## Overview

The prediction task is to determine whether a person makes over 50K a year according to other explanatory variables. The data is sourced from ‘UCI ML Repository — adult dataset’. People are divided into two groups by the salary(<=50 and >50). The influence on each variable on the salary is explored by applying EBM and SVM and then the performance of both methods are evaluated by time of training, confusion matrix as well as accuracy score.  
The performance comparaison result of these two methods is: From the aspect of training time, with same training data, the SVM is faster than EBM. While in terms of accuracy, EBM has better performance than EBM.


## Data set description:

The data source is ‘https://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.date'. The extraction was done by Barry Becker from the 1994 Census database. A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0)).
The data set includes different explanatory variables of 32561 adult ("Age", "WorkClass", "fnlwgt", "Education", "EducationNum",  "MaritalStatus", "Occupation", "Relationship", "Race", “Gender",  "CapitalGain", "CapitalLoss", "HoursPerWeek", "NativeCountry", “Income”), among those variables, the object variable is “Income”, which is classified into two conditions: ‘<=50’ and ‘>50’
Methods:

## Description of EBM:
InterpretML is an open-source python package for training interpretable machine learning models and explaining blackbox systems. One of the training method concerned in the project is ‘Explainable Boosting Machine(EBM)’ from the python package ‘interpret.glassbox’, which simplifies the interpretation of training  result and analysis of impact of variables on the result.
EBM has both high accuracy and interpretability. EBM uses modern machine learning techniques like bagging and boosting to breathe new life into traditional GAMs (Generalized Additive Models). This makes them as accurate as random forests and gradient boosted trees, and also enhances their intelligibility and editability.

## Description of SVM:
In machine learning, support-vector machines (SVMs, also support-vector network) are supervised learning models with associated learning algorithms that analyze data used for classification and regression analysis. Given a set of training examples, each marked as belonging to one or the other of two categories, an SVM training algorithm builds a model that assigns new examples to one category or the other, making it a non-probabilistic binary linear classifier (although methods such as Platt scaling exist to use SVM in a probabilistic classification setting).

More detailed discriptions are added in the file "project discription"
