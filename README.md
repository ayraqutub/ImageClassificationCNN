# Image Classification with Convolutional Neural Networks (CNN) Using MNIST Dataset

The objective of this project was to build and train a Convolutional Neural Network (CNN) to perform image classification using the MNIST dataset, which contains 28x28 grayscale images of handwritten digits (0-9). The report is presented as a Jupyter Notebook.

CNNs are a powerful tool for image classification due to their ability to learn spatial hierarchies of features. The CNN architecture used in this report has a convolutional layer followed by a pooling layer, another set of the same, and then the final connection layer.

The key tasks were to explore different hyperparameters, including the number of filters and learning rates, and to find the best-performing model using hyperperameter exploration. Once the optimal hyperparameters were identified, the model was trained on the entire dataset and evaluated on a test set.

The CNN is formatted as an automated pipeline. It includes the expected steps of data ingestion, data preprocessing, model training, and model evaluation. Before training the final model, hyperperameter exploration is conducted to assess the combination of hyperperameters that result in the greatest accuracy. Each of these steps was modularized for better clarity and usability.
