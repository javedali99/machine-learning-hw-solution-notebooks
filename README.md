# Machine Learning Homework Solution Notebooks (UCF CAP5610)

### 1. Data Preprocessing and Analyze by pivoting features of Titanic dataset

   - Titanic dataset: https://www.kaggle.com/c/titanic/data
   
### 2. Analyze the Titanic data and find whether the individuals from the test dataset had survived or not 

**Feature Engineering**

   - Select a set of important features `VarianceThreshold` Feature Selection using `sklearn.feature_selection`
   - SelectKBest Univariate Feature Selection
   - SelectFromModel for Logistic Regression
   - Recursive Feature Selection

**Build Random Forest and Decision Tree Models**

- Build Random Forest and Decision Tree models with the Titanic dataset
- Apply the five-fold cross validation of the Decision Tree and the Random Forest learning algorithms to the Titanic data to extract their average classification accuracies.
- Learn a Decision Tree model with the Titanic data using Gini Index and plot the Decision Tree.


### 3. Support Vector Machines

- Construct a support vector machine that computes the kernel function.
-  Learning SVMs on the Titanic dataset. 
-  Five-fold cross validation classification accuracies on Titanic training set, with respect to the `linear`, `quadratic`, and `RBF` kernels.
-  Tuning the hyperparameters and applying `GridSearchCV` for each SVM kernels
