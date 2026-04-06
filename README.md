This repository contains two projects that were worked on the subject of Machine Learning.
The dataset used is a collection of faces that fall into 2 categories: either pleasant or unpleasant.

First Project (ML1_5090_4969):

The objective of this project is to develop a decision system that classifies facial images into two categories (binary classification).
We explored and compared multiple classification methodologies, analyzing the impact of different approaches to handling image-based information.

We investigated two distinct pipelines for tackling this classification problem:

1. Direct Image-Based Classification using a CNN
  We trained a convolutional neural network (CNN) directly on the dataset.
  We explored different architectures and optimization techniques.
  We evaluated performance based on accuracy, precision, recall, F1 and other metrics.

3. Feature-Based Classification using a Pretrained CNN
  We used a pretrained CNN (ResNet) to extract vector representations (features) from the images.
  We constructed a feature space where each image is represented by a feature vector and
  applied and compared various traditional classification models on the extracted feature vectors,
  Then we analyzed the impact of different feature extraction strategies on classification performance.


Second Project (ML2_5090_4969):

In this project, we experimented on the Dimensionality Reduction and then Clustering of the results. The dataset used in this project is the same as the first one. We tried all possible combinations of Dimensionality Reduction algorithms (PCA, LLE, Autoencoders) and Clustering algorithms (K-means with Euclidean Distance and Cosine Similarity, Agglomerative Clustering) for the evaluation of results.
