🧠 Brain Tumor Detection using Deep Learning
📌 Project Overview

The objective of this project is to detect brain tumors from medical images using deep learning models. Since accuracy in medical diagnostics is critical, the goal was to build a model with minimal error margin.

Dataset: MRI images categorized into Positive (with tumor) and Negative (without tumor).

Approach: Started with a custom CNN, later improved using Transfer Learning (MobileNet).

🗂️ Dataset Preparation

Data split into:

Training → 70%

Validation → 15%

Testing → 15%

Data Augmentation: Applied zoom, shear, and horizontal flip to improve generalization.

⚙️ Initial Model Development

Architecture: Custom CNN with Convolutional, MaxPooling, Dropout, and Dense layers.

Training: Conducted on training set, validated on validation set.

Results: Achieved 93% accuracy on test data.

Limitation: A 7% error margin is unacceptable for medical applications.

🚀 Model Improvement (Transfer Learning)

Switched to MobileNet as the base model.

Frozen pre-trained layers to retain features, added custom dense layers for classification.

Callbacks: Early stopping & Model checkpointing to prevent overfitting and save best model.

📊 Results

Final Accuracy: Improved significantly with MobileNet, reducing error margin to meet medical standards.

✅ Conclusion

Successfully developed a Brain Tumor Detection model with high accuracy suitable for medical use.

Next Steps:

Experiment with other architectures (ResNet, EfficientNet).

Use larger datasets.

Apply more advanced augmentation techniques.
