Overview
A comprehensive comparison of three major deep learning architectures — LSTM/GRU (RNNs), DistilBERT (Transformer), and Vision Transformer (ViT) — applied to both text and image classification tasks. This lab provides a direct, apples-to-apples comparison using the same dataset across different architectures.
Problem Statement
How do classical RNNs compare to modern Transformers on the same task? And how does the Transformer architecture extend from text into images? This project answers both questions by building and benchmarking all three architectures side by side.
Project Structure
PartArchitectureTaskDatasetALSTM & GRU (RNNs)News Topic ClassificationAG NewsBDistilBERT (Transformer)News Topic ClassificationAG NewsCVision Transformer (ViT)Image ClassificationCIFAR-10D—Comparative Analysis & ReflectionAll results
Approach & Methodology

Built LSTM and GRU classifiers from scratch for 4-class news topic classification
Applied DistilBERT (pre-trained Transformer) on the same AG News dataset for direct comparison
Implemented a Vision Transformer (ViT) for image classification on CIFAR-10
Compared results across all architectures using accuracy, training time, and classification reports
Analyzed tradeoffs between RNN sequential processing and Transformer parallel attention

Technologies Used

Python
PyTorch
Hugging Face Transformers
Hugging Face Datasets
Torchvision
NumPy
Matplotlib

Datasets

AG News — 120,000 news articles across 4 categories: World, Sports, Business, Sci/Tech
CIFAR-10 — 60,000 color images across 10 object categories

Key Concepts Covered

LSTM and GRU recurrent architectures for sequential text processing
Attention mechanisms and Transformer architecture
Transfer learning with pre-trained DistilBERT
Vision Transformers (ViT) — extending Transformers to image data
Vocabulary building and text preprocessing from scratch
Direct performance comparison across architectures

How to Run

Open the .py file in Google Colab or convert to .ipynb
Go to Runtime → Change runtime type → T4 GPU for faster training
Run all cells in order from top to bottom
Estimated time: 3–4 hours on free Colab GPU

Dependencies
pip install transformers datasets accelerate torch torchvision numpy matplotlib
Learning Outcomes

Gained direct intuition for why Transformers outperform RNNs on most NLP tasks
Learned how the same attention mechanism powers both text and image models
Practiced transfer learning with Hugging Face pre-trained models
Developed skills in multi-architecture benchmarking and comparative analysis
