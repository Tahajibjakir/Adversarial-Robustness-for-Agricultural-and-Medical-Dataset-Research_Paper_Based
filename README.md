# Adversarial-Robustness-for-Agricultural-and-Medical-Dataset-Research_Paper_Based
This project presents a deep learning-based image classification system designed to be robust against adversarial attacks,
applied across two critical domains: medical diagnosis and agricultural disease detection. Using CNN architectures, the model
classifies brain tumors from MRI scans and detects diseases in betel leaf images with high accuracy. To improve reliability in
real-world scenarios, adversarial training techniques like the Fast Gradient Sign Method (FGSM) are employed, making the model
resilient to maliciously perturbed inputs. The system is evaluated through extensive metrics, including confusion matrices, 
accuracy/loss plots, and classification reports, demonstrating strong generalization and minimal overfitting. This work 
highlights the importance of adversarial robustness for secure and trustworthy AI deployment in healthcare and agriculture.

## Screenshot of Adversarial vs Natural Betel Leaf image
![Image](https://github.com/user-attachments/assets/d7cf66bc-ffd8-410c-82a9-11e12ae4a494)

## Features
• Robust classification of brain tumors from MRI scans

• Accurate detection of betel leaf diseases in agricultural images

• Adversarial training using FGSM to enhance model security

• High accuracy on both clean and adversarial data

• Comprehensive evaluation with confusion matrices and classification reports

• CNN-based architecture tailored for each dataset

• Minimal overfitting with stable training and validation performance

## Model Details
The project uses Convolutional Neural Networks (CNNs) tailored for two different image classification tasks:
Brain tumor detection and betel leaf disease classification. The models are trained on domain-specific datasets
with a focus on balancing high accuracy and adversarial robustness.

🏗️ Architecture Highlights
Base Architecture: Custom CNN with multiple convolutional, pooling, and dense layers

Activation Functions: ReLU for hidden layers, Softmax for output

Loss Function: Categorical Cross-Entropy

Optimizer: Adam

Regularization: Dropout layers to reduce overfitting

🔄 Training Strategy
Datasets are split into training, validation, and test sets

Data preprocessing includes resizing, normalization, and augmentation

Training with both natural and adversarial examples (generated via FGSM)

Performance monitored via accuracy/loss curves and classification metrics

🧪 Adversarial Training
FGSM (Fast Gradient Sign Method) is used to generate adversarial examples

Adversarial images integrated into training batches

Helps improve the model’s resilience against perturbations without degrading accuracy on clean data


## Methodology Flowchart
![Image](https://github.com/user-attachments/assets/71fe8991-ab9c-46ed-96ea-4993f21b1bed)

## Installation
No permission right now.

## Contact / Credits

Developed by Tahajib Jakir Khan  
📧 tahajibjakirkhan00@gmail.com 
📎 [LinkedIn](https://www.linkedin.com/in/tahajib-jakir-khan-53b30822b/)


