# Digit Recognition SVM ( Support Vector Machine) Classifier

Dive into the Digit SVM Mastery project! Train Support Vector Machine classifiers on sklearn digits data, experimenting with kernels like rbf and linear. Achieve peak accuracy by fine-tuning through regularization and gamma parameters. Optimize with 80% of samples for training—master the art of digit recognition with SVMs!

## Description
This Python script showcases the training and optimization of a Support Vector Machine (SVM) classifier for digit recognition using the sklearn digits dataset.

### Features
- Trains SVM with linear and rbf kernels.
- Measures accuracy for each kernel.
- Utilizes GridSearchCV to optimize hyperparameters (C and gamma) for the rbf kernel.
- Demonstrates the impact of hyperparameters through a 3D plot.

### Usage
1. Ensure you have the necessary dependencies installed (`numpy`, `scikit-learn`, `matplotlib`).
2. Run the script in a Jupyter environment or any Python IDE.

### Results
- Accuracy with linear kernel: 97.5%
- Accuracy with rbf kernel: 98.33%
- Best hyperparameters: {'C': 1, 'gamma': 0.001}
- Accuracy with tuned model: 98.89%

Explore the versatility of SVMs for digit recognition and fine-tune your model for optimal performance!

*Note: The script includes an alternative method for visualizing the impact of hyperparameters using a 3D plot.*


---
