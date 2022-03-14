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

### 4. Unsupervised Learning

**Football team clustering**

- Use Euclidean distance as the distance metric. First, perform one iteration of the K-means algorithm and report the coordinates of the resulting centroids. Second, use K-Means to find two clusters.
- Use Manhattan distance as the distance metric. First, perform one iteration of the K-means algorithm and report the coordinates of the resulting centroids. Second, use K-Means to find two clusters.

**K-Means Clustering with Real World Dataset**

- Implement the K-means algorithm. K-means algorithm computes the distance of a given data point pair. Replace the distance computation function with Euclidean distance, 1- Cosine similarity, and 1 – the Generalized Jarcard similarity
- Apply different distance matrices.
- Compare the results.

### 5. Machine Learning for Recommender Systems

- Compute the average MAE and RMSE of the Probabilistic Matrix Factorization (PMF), User based Collaborative Filtering, Item based Collaborative Filtering, under the 5-folds cross-validation
- Compare the average (mean) performances of User-based collaborative filtering, item-based collaborative filtering, PMF with respect to RMSE and MAE. Which ML model is the best in the movie rating data?
- 
