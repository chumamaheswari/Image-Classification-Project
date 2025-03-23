# Image Classification Using Python  
This project implements and compares three image classification models:  
- **Multiclass SVM**  
- **Softmax Classifier**  
- **Two-layer Neural Network**  

## Dataset  
A subset of CIFAR-10 (3 classes) is used for training and testing.  

## Implemented Models  
- **SVM**: A linear SVM model trained on flattened image data.  
- **Softmax Classifier**: Logistic regression with a Softmax function.  
- **Two-layer Neural Network**: A simple neural network trained using PyTorch.  

## Installation  
Run the following command to install dependencies:  
```bash
pip install numpy matplotlib scikit-learn pandas torch torchvision