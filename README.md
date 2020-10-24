# Machine Learning Project: Iris Flower classification with Visual Representation

This program applies basic machine learning (classification) concepts on Iris Data to predict the species of a new sample of Iris flower.

# Introduction
The dataset for this project is downloaded from kaggle.com. The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.

The data set consists of 150 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor).
Four features were measured from each sample (in centimetres):
Length of the sepals
Width of the sepals
Length of the petals
Width of the petals

# Working of the iris_decision_tree_classifier:

The program takes reads dataset using pandas function and is stored in a variable Iris.
The dataset is splitted in test-train sets.
The program then creates a decision tree based on the Train-dataset for classification.
The Decision tree is then visualized with Text representation and image visualization.
The image visualization is then saved in decision_tree.png file.
The Model is then tested on Test-dataset and accuracy is measured.
Based on the accuracy, the Model is ready to use on new Dataset for classification.
