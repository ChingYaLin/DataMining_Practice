# DataMining_Practice
This repo is for practicing data mining using different methods.

## Data
This practice using the wine quality data from UCI machine learning repository. 
[wine quality data](https://archive.ics.uci.edu/dataset/186/wine+quality)

## Create the environment for practice
```
pip install pandas numpy scikit-learn mlxtend 
matplotlib graphviz
```

## The pipeline workflow
1. data loading
2. data preprocessing: Normalization (`StandardScaler`), convert to class type (for association rules)
3. Applied on different thechnique
    * Association rule:
    * Decision Tree
    * Random Forest
    * Cluster
        * Hierarchical clustering
        * K-means
    * PCA