# Brain Tumor Prediction using CNN

## Introduction
Brain tumor prediction is a critical task in medical image analysis. Early and accurate diagnosis is crucial for effective treatment and improved patient outcomes. Traditional machine learning classifiers struggle to efficiently analyze complex medical imaging data due to their limited ability to extract meaningful features. This project leverages deep learning, specifically Convolutional Neural Networks (CNN), to automate feature extraction and improve classification accuracy. By comparing CNN performance with traditional models, we aim to highlight the advantages of deep learning in medical image analysis. This project uses Convolutional Neural Networks (CNN) to classify brain tumors and compares its performance with traditional classifiers.



## Dataset
MRI images of three tumor types:
1. Glioma
2. Meningioma
3. Pituitary

## Implementation
The implementation follows a structured pipeline:
1. **Data Preprocessing:** MRI images are normalized, resized, and augmented to enhance model generalization.
2. **Model Selection:** Several classifiers, including Logistic Regression, Decision Trees, Random Forest, and Naïve Bayes, are trained and evaluated.
3. **CNN Architecture:** The CNN model consists of multiple convolutional layers, ReLU activations, pooling layers, and fully connected layers optimized using TensorFlow and Keras.
4. **Training and Evaluation:** The dataset is split into training and testing sets. Model performance is assessed using accuracy, precision, recall, and confusion matrices.
5. **GUI Development:** A user-friendly interface is built to allow users to upload MRI scans and receive predictions instantly.
- Comparison with Logistic Regression, Decision Trees, Random Forest, and Naïve Bayes
- GUI for user-friendly interaction

## Results
The CNN model demonstrated a significant improvement over traditional classifiers. Key findings include:
- **CNN achieved 90% accuracy**, whereas Logistic Regression, Decision Trees, and Naïve Bayes performed significantly worse due to their inability to extract spatial features.
- **Confusion Matrix Analysis:** CNN exhibited higher precision and recall for all tumor classes, minimizing false positives and false negatives.
- **Comparison with Traditional Models:** Random Forest showed moderate performance but lacked the feature extraction capabilities inherent in CNN.
- **Robustness and Generalization:** The CNN model generalized well to unseen test data, proving its applicability in real-world medical diagnosis scenarios.





