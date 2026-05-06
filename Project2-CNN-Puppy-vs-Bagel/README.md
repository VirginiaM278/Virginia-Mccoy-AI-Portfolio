Overview
Built a Convolutional Neural Network (CNN) to classify images as either a puppy or a bagel — inspired by the famous viral internet meme. This project explores CNN architecture, transfer learning, and fine-tuning using real-world image data.
Problem Statement
Can an AI learn to tell the difference between a curled-up puppy and a bagel? This fun but technically challenging binary classification problem demonstrates the power of CNNs and transfer learning on custom image datasets.
Approach & Methodology

Built a CNN from scratch using TensorFlow/Keras for binary image classification
Applied transfer learning using pre-trained models: ResNet50, VGG16, and MobileNetV2
Used ImageDataGenerator for data loading and augmentation
Fine-tuned pre-trained models to improve performance on the custom dataset
Evaluated results using accuracy scores, confusion matrices, and classification reports

Technologies Used

Python
TensorFlow / Keras
NumPy
Matplotlib & Seaborn
Scikit-learn
Pillow (PIL)
Kaggle API (for dataset download)

Dataset

Puppy or Bagel Dataset from Kaggle
Link: https://www.kaggle.com/datasets/returnofsputnik/puppy-or-bagel
Binary classification: puppy images vs. bagel images

Key Concepts Covered

Convolutional layers, pooling layers, and feature maps
Building a CNN architecture from scratch
Transfer learning with pre-trained ImageNet models
Fine-tuning strategies for custom datasets
Data augmentation to improve model generalization

How to Run

Open the .ipynb file in Google Colab
Connect to Google Drive when prompted
Download the dataset from Kaggle using the link above
Run all cells in order from top to bottom

Dependencies
pip install tensorflow numpy matplotlib scikit-learn kaggle pillow seaborn
Learning Outcomes

Learned how CNNs extract spatial features from images through convolution
Gained practical experience applying transfer learning to save training time
Understood how to fine-tune pre-trained models for custom classification tasks
Practiced evaluating image classification models with industry-standard metrics
