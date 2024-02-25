# Predicting the species of flower for a given input Image

I focused on developing a machine-learning model capable of predicting the species of a flower from an image. Utilizing the Flowers-17 dataset, which comprises 17 flower categories with 80 images per category, I embarked on a comprehensive analysis to achieve accurate classification results.

## Steps

Data Preparation: I initiated the project by importing the dataset images and their corresponding labels, organizing the data to facilitate efficient processing and analysis.
Model Development: I employed a multi-model approach for the dataset classification, incorporating logistic regression, K-Nearest Neighbors (K-NN), and a neural network architecture with two hidden layers. This diversified strategy allowed for a thorough evaluation of each model's effectiveness in image classification tasks.
Performance Evaluation: The models were rigorously tested using a split of 20% test images and 80% training images. I assessed their performance through confusion matrices, enabling a detailed comparison of accuracy and misclassification rates.
Clustering Analysis: Additionally, I applied K-means clustering to the image dataset to explore data grouping and determine the optimal number of clusters, providing insights into the inherent data structure.
Practical Application Test: To validate the models' applicability, I created and utilized a new test dataset consisting of 10 images. This exercise tested the models' ability to generalize and accurately predict flower species in unseen data.
