# UnsupervisedML-MyopiaClusters

![](https://img.shields.io/badge/scikit_learn-1.0.2-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/plotly-5.11.0-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/pandas-1.3.5-informational?style=plastic&logo=appveyor)
![](https://img.shields.io/badge/matplotlib-3.5.3-informational?style=plastic&logo=appveyor)

![alt text](https://github.com/LynHJ/UnsupervisedML-MyopiaClusters/blob/d8281ef3033a2080101c464bfe3b299dad52e955/Image/myopia.jpg)

## Background

The purpose of this project is demonstrate how to use unsupervised machine learning skill to classify a data set regarding to myopia. 

## Aanalsis

<img src='https://github.com/LynHJ/UnsupervisedML-MyopiaClusters/blob/d8281ef3033a2080101c464bfe3b299dad52e955/Image/2clusters.png' width= 70% class="center">  

### Summary:

After executing PCA and t_SNE to apply dimensionality reduction, unfortunately, the result showed there were no distinct clusters. Then I will try the K-means method to get the best number of clusters(the elbow).  

<img src='https://github.com/LynHJ/UnsupervisedML-MyopiaClusters/blob/d8281ef3033a2080101c464bfe3b299dad52e955/Image/The%20elbow.png' width= 50% ><img src='https://github.com/LynHJ/UnsupervisedML-MyopiaClusters/blob/d8281ef3033a2080101c464bfe3b299dad52e955/Image/3clusters.png' width= 50% />   

### Summary:

As the combination of PCA and t_SNE could not help me to classify the data into a few clusters, I tried to use another combination, K-means and PCA. Instead of doing too much dimensionality reduction, use K-means to determine the best number of clusters for the data set and then use PCA to generate 3 principle components. From the output above, there are three distinctive clusters.  

## Content:
```
Project
├── Image 
│   ├── 2clusters
│   ├── 3clusters
│   └── The elbow
├── Myopia Clusters.ipynb
├── README.md
├── Resources
│   └── myopia.csv
└── requirements.txt
```

## Installation

pip install -r requirements.txt














