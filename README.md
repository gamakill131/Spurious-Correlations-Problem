# Spurious-Correlations-Problem
We have a sample task just to help us understand if you're familiar with Pytorch etc. and how comfortable you are with machine learning in general.

Deep neural networks often exploit non-predictive features that are spuriously correlated with class labels, leading to poor performance on groups of examples without such features. Using the SpuCo Package (SpuCo Documentation), we'd like you to implement a simple method to remedy spurious correlations in SpuCoMNIST (use default parameters to initialize the dataset).

The method (George) we'd like you to implement has a 3 step pipeline:
1. Train a model using ERM
2. Cluster inputs based on the output they produce for ERM
3. Retrain using "Group-Balancing" to ensure in each batch each group appears equally.
