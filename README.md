# Credit-Card-Fraud-Detection
Throughout the financial sector, machine learning algorithms are being developed to detect fraudulent transactions. 
In this project, that is exactly what we are going to be doing as well. 
Using a dataset of nearly 28,500 credit card transactions and multiple unsupervised anomaly detection algorithms, we are going to identify transactions with a high probability of being credit card fraud.
In this project, we will build and deploy the following two machine learning algorithms:
⦁	Local Outlier Factor (LOF)
⦁	Isolation Forest Algorithm.

Local Outlier Factor (LOF)
The anomaly score of each sample is called Local Outlier Factor. It measures the local deviation of density of a given sample with respect to its neighbors. It is local in that the anomaly score depends on how isolated the object is with respect to the surrounding neighborhood.

Isolation Forest Algorithm
The IsolationForest âisolatesâ observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature.
Since recursive partitioning can be represented by a tree structure, the number of splittings required to isolate a sample is equivalent to the path length from the root node to the terminating node.
