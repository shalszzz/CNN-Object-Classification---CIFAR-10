# CNN-Object-Classification---CIFAR-10


Project Overview

This project implements a lightweight Convolutional Neural Network (CNN) for image classification on the CIFAR-10 dataset. The model achieves 80.03% test accuracy using only ~1.2 million parameters, making it efficient for resource-constrained environments.

CIFAR_10.ipynb and cifar_10.py are the code in notebook form and script form respectively

best_model.pth — Model: Trained CNN weights achieving 80.03% accuracy on CIFAR-10; compact file size (~3.2 MB) suitable for quick loading and inference.

model_comparison.csv — Data: Comparison table evaluating CNN vs Random Forest vs SVM, including overall accuracy metrics and training time analysis.

per_class_accuracy.csv — Data: Detailed per-class performance showing accuracy for all 10 categories along with the most frequent misclassification patterns.

confusion_matrix.png — Image: Heatmap visualization highlighting correct predictions and areas where classes are commonly confused by the model.

learned_filters.png — Image: First-layer convolutional filter visualization displaying learned features such as edge detectors, color blobs, and texture patterns.

training_curves.png — Image: Accuracy-vs-epoch plot illustrating learning progression from roughly 45% to 80.03% across 30 training epochs.

accuracy_vs_loss.png — Image: Dual-axis chart showing the inverse relationship between rising accuracy and decreasing loss during training.




