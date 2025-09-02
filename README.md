# COVID-19 Prediction using Deep Learning Models
# Problem Statement:
The COVID-19 pandemic highlighted the urgent need for reliable and scalable diagnostic tools. While RT-PCR tests are accurate, they are slow and resource-heavy. Chest X-ray (CXR) imaging, when combined with deep learning, provides a rapid and cost-effective alternative for early detection.

# Dataset:
Chest X-ray dataset was collected from Kaggle containing images labeled as COVID-19, Pneumonia, and Normal.
Preprocessing steps included resizing all images, pixel normalization, and data augmentation (rotation, flipping, zooming) to enhance robustness.

# Model Development:
Implemented and compared five deep learning architectures:
1. VGG16 – Transfer learning with deep feature extraction.
2. ResNet50 – Introduced residual connections for better gradient flow.
3. DenseNet121 – Improved feature reuse with dense connections.
4. MobileNetV2 – Lightweight and efficient, suitable for deployment.
5. Custom CNN – A self-designed convolutional neural network tuned for this dataset.

# Training Details:
Optimizer: Adam with learning rate scheduling.
Loss Function: Categorical Cross-Entropy.
Dataset split: 80% training, 10% validation, 10% testing.
Applied dropout and early stopping to prevent overfitting.

# Results:
The Custom CNN achieved the highest test accuracy of 89%, surpassing heavier transfer learning models.
Findings demonstrated that lightweight CNNs, when properly tuned, can outperform large pretrained networks on domain-specific datasets with limited samples.

# Key Contributions:
Built an end-to-end pipeline for COVID-19 prediction from chest X-rays.
Conducted comparative analysis of five deep learning models.

Showcased the effectiveness of simple CNN architectures for real-world healthcare applications.

Established a foundation for rapid, low-cost diagnostic systems in medical imaging.
