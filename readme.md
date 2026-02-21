
The following files can be found in the repository which shows results drawn from the model

best_model.pth:	Model	Trained CNN weights achieving 80.03% accuracy on CIFAR-10 (~3.2 MB)
model_comparison.csv:	Data	Comparison table of CNN vs Random Forest vs SVM with accuracy and training times
per_class_accuracy.csv:	Data	Per-class accuracy breakdown and most common misclassifications for all 10 categories
confusion_matrix.png:	Image	Heatmap visualization showing correct predictions and confusion patterns between classes
learned_filters.png:	Image	Visualization of first-layer convolutional filters showing edge detectors, color blobs, and texture patterns learned by the network
training_curves.png:	Image	Accuracy vs epoch plot showing model learning progression from 45% to 80.03% over 30 epochs
accuracy_vs_loss.png:	Image	Dual-axis plot showing inverse relationship between increasing accuracy and decreasing loss during training
