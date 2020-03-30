# Day 8

## Topic: Clustering Documents

### What will you learn? 

Document clustering, also called text clustering, is a cluster analysis on textual documents. One of the typical usages would be document management.

### Task: 

Clustering or grouping the documents based on the patterns and similarities.

### Dataset: 

https://www.kaggle.com/dushyantv/consumer_complaints

### How can you implement it?

1. Tokenization 
2. Stemming and lemmatization 
3. Removing stop words and punctuation 
4. Computing term frequencies or TF-IDF 
5. Clustering: 

K-means/Hierarchical; we can then use any of the clustering algorithms to cluster different documents based on the features we have generated

6. Evaluation and visualization:

The clustering results can be visualized by plotting the clusters into a two-dimensional space (Plot clusters in 2D Graphs)

### Resources: 

Basic visualization and clustering in Python:

https://www.kaggle.com/dhanyajothimani/basic-visualization-and-clustering-in-python

K-means clustering in Python: 

https://towardsdatascience.com/machine-learning-algorithms-part-9-k-means-example-in-python-f2ad05ed5203

A Beginner’s Guide to Hierarchical Clustering: 

https://www.analyticsvidhya.com/blog/2019/05/beginners-guide-hierarchical-clustering/



## Topic: Implementing Multiclass Classification

### What will you learn?

To understand how to do multiclass classification for text data in Python through solving Consumer complaint classifications for the finance industry.

### Task: 

Classify Consumer Financial Protection Bureau complaints into the product category it belongs to using the description of the complaint

### Goal of the task: 

The goal of the project is to classify the complaint into a specific product category. 
Since it has multiple categories, it becomes a multiclass classification that can be solved through many of the machine learning algorithms. 
Once the algorithm is in place, whenever there is a new complaint, we can easily categorize it and can then be redirected to the concerned person. 
This will save a lot of time because we are minimizing the human intervention to decide whom this complaint should go to. 
Use a visualization matrix to prepare actual vs predicted.

### Dataset: 

https://www.kaggle.com/subhassing/exploring-consumer-complaint-data/data

### Resources: 

Multiclass and MultiLabel Algorithm: 

https://scikit-learn.org/stable/modules/multiclass.html#multilabel-classification-format

Multi-Class Text Classification with Scikit-Learn:

https://towardsdatascience.com/multi-class-text-classification-with-scikit-learn-12f1e60e0a9f

Plot a confusion Matrix: 

https://www.kaggle.com/grfiv4/plot-a-confusion-matrix
