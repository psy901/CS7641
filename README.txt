Name: Sang Yun Park
GTid: 902762410
userid: spark359

Instructions to run the code.

1. Install Weka
2. Download the dataset from the git repository > data directory (https://github.com/psy901/hw3.git)
  - For breast cancer data, use data/BreastCancer/breast-cancer.arff
  - For optical digits data, use data/Digits/optdigits.arff

3. Use below reference to use different clustering and dimension reduction methods

Clustering:
  K-Means
	Weka > Cluster > SimpleKMeans
  Expectation Maximzation
	Weka > Cluster > EM

Dimension Reduction
  PCA
	Weka > Filter > PrincipalComponents
  ICA
	Weka > Filter > IndependentComponents
  Randomized Projection
	Weka > filter > RandomizedProjection
  Information Gain
	Weka > Select Attribute > InfoGainAttributeEval

Neural Net
  Weka > Classify > MultilayerPerceptron

Add Cluster
  Weka > Filter > AddCluster
  