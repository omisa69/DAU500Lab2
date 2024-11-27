# DAU500Lab2
Principal Component Analysis (PCA) and Neural Networks

This study examines the integration of Principal Component Analysis (PCA) and neural networks for efficient classification and regression tasks using the MNIST, IRIS, Fashion MNIST, and California Housing datasets. PCA reduced the MNIST dataset’s dimensions from 784 to 154 components while retaining 95% of the variance. Kernel PCA with linear, sigmoid, and RBF kernels was explored for feature extraction.

Neural networks trained on original and PCA-transformed datasets achieved similar performance, with the PCA-transformed MNIST model attaining 97.67% validation accuracy. For classification tasks, hyperparameter tuning enhanced IRIS and Fashion MNIST performance by optimizing architectures and learning rates. Regression experiments on the California Housing dataset emphasized the role of learning rate selection and early stopping in achieving stable convergence and mitigating overfitting.

The findings demonstrate PCA’s effectiveness in reducing computational complexity without significant accuracy loss, complemented by hyperparameter tuning for improved efficiency and performance. This study highlights the synergy between PCA and neural networks as a scalable solution for high-dimensional data processing. Future work could explore advanced techniques like Transformer-based models to enhance scalability and performance in complex machine-learning tasks.
