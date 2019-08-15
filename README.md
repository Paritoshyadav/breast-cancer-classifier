# Breast-cancer-classifier
Classification using Machine Learning Techniques on Breast Cancer Wisconsin Data Set (diagnosis) Using Support Vector Machines with the accuracy of 0.96

# About Dataset
This Project use  Wisconsin Data Set https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic). which consist 

**Data Set Characteristics:  Multivariate**

**Number of Instances:569**

**Area:Life**

**Attribute Characteristics:Real**

**Number of Attributes:32**

**Associated Tasks:Classification**

**Number of Web Hits: 9752918**

### Attribute Information:
- ID number 
- Diagnosis (M = malignant, B = benign) 

Ten real-valued features are computed for each cell nucleus: 

- radius (mean of distances from center to points on the perimeter) 
- texture (standard deviation of gray-scale values) 
- perimeter 
- area 
- smoothness (local variation in radius lengths) 
- compactness (perimeter^2 / area - 1.0) 
- concavity (severity of concave portions of the contour) 
- concave points (number of concave portions of the contour) 
- symmetry 
- fractal dimension ("coastline approximation" - 1)

# Goal
The objective of this model is to find whether the cancer is **malignat** or **benign**

# About Project
### Tools and method utilized:
- python
- Tableau(Optional)
- google colab/jupyter notebook
- Data manipulation using: 
  1) pandas,
  2) plotting using seaborn and matplotlib,
  3) Feature selection
  4) Grid search

# Conclusions
Once I employed all these methods, we were able to utilize various machine learning metrics. Each model provided valuable insight.
The best result is given by svm with hyperparameter using `GridSearchCV` method

### Parameter uses
- `C: 20` 
- `gamma': 0.2` 
- `kernel': 'rbf`

# classification report
|              | precision | recall | f1-score | support |
|--------------|-----------|--------|----------|---------|
| 0.0          | 0.90      | 1.00   | 0.95     | 43      |
| 1.0          | 1.00      | 0.93   | 0.96     | 71      |
| accuracy     |           |        | 0.96     | 114     |
| macro avg    | 0.95      | 0.96   | 0.95     | 114     |
| weighted avg | 0.96      | 0.96   | 0.96     | 114     |


