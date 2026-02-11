CNN Image Classification with Grad-CAM on CIFAR-10

This project investigates image classification using Convolutional Neural Networks on the CIFAR-10 dataset. The goal is not only to achieve strong classification performance but also to interpret model decisions using Grad-CAM visualization.

Overview
Three different models were implemented and compared: a basic CNN built from scratch, a deeper VGG-style CNN, and a pretrained ResNet18 model. The project analyzes how architectural depth and residual connections impact performance and convergence.

Methodology
The dataset was preprocessed using normalization and data augmentation techniques such as random horizontal flipping and random cropping. Models were trained using the Adam optimizer with cross-entropy loss. Performance was evaluated using accuracy, precision, recall, and F1-score.

Model Comparison

Basic CNN achieved solid baseline performance

VGG-style CNN improved feature extraction and overall accuracy

Pretrained ResNet18 achieved the highest accuracy and fastest convergence

Interpretability with Grad-CAM
Grad-CAM was applied to visualize which regions of the image influenced the model’s predictions. Heatmaps confirmed that correctly classified images often relied on meaningful object regions. Misclassified examples were also analyzed to identify common failure cases.

Results
ResNet18 achieved the best performance among the three models. Deeper architectures and pretrained models significantly improved classification accuracy and generalization.

Tools and Technologies
Python
PyTorch
Torchvision
NumPy
Matplotlib
Jupyter Notebook

Project Files

CNN_Image_Classification_GradCAM_CIFAR10.ipynb

CNN_Image_Classification_GradCAM_Report.pdf

How to Run
Open the Jupyter Notebook file and run the cells sequentially after installing the required libraries.

Purpose
This project explores CNN architectures, transfer learning, and model interpretability in computer vision tasks.

Author
Albatul Altoum