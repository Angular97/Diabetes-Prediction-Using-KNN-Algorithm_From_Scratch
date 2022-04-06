# Diabetes-Prediction-Using-KNN-Algorithm_From_Scratch

**Supervised Problem:**

* The problem in which we are given a dataset which has target/dependent/labelled variable.
* Here we know for what we are building the model

**Classification Problem:**

* The problem where dataset contains categorical target variable.

**KNN**

* K Nearest Neighbours
* Uses similarity measure ( how much two objects are alike)
* Stores available cases and for finding label for new case, check in it's  v   neighbor, and says that I am one of them.
* Applications
 1. Recommended System (E Commerce Websites)
 2. Concept Search (Internet generates plethora of documents each day, to segeregate them we may use this algorithm)

**My Implementation**

* Algorithm
1. Find the distance between new_data_instance and all existing instances
2. Find nearest K points.
3. Among them choose which target class occurred in majority.

**Catch**
1. Choose approaprite value for K

**Steps**
1. Define Distance Metric Function (Euclidian & Manhattan)
2. Define NearestNeigbours Function
3. Define Predict Function


* X_train --> training data with features and target

* X_test  --> test data without target 
* K: K neighbors

- Total Attributes - 9
- Number of instances - 768
- Score (Accuracy) - 74.4%
