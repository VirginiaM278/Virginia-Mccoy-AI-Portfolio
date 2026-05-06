Overview
Built a diffusion model from scratch that generates realistic handwritten digit images. This project demonstrates how modern generative AI works by teaching a model to gradually remove noise from an image until it produces a clear, recognizable result.
Problem Statement
How does AI generate images from nothing? This project answers that by implementing a diffusion model — the same core technology behind tools like DALL-E and Stable Diffusion — trained to generate handwritten digits from pure random noise.
Approach & Methodology

Implemented a diffusion model using PyTorch
Trained on the MNIST handwritten digits dataset
Modeled the forward diffusion process: gradually adding noise to images
Trained the model to learn the reverse process: removing noise step by step
Visualized the transformation from random noise → recognizable digit images
Used reproducible random seeds for consistent results

Technologies Used

Python
PyTorch
NumPy
Matplotlib
Pillow (PIL)
einops (tensor manipulation)
torchvision

Dataset

MNIST — 70,000 grayscale images of handwritten digits (0–9)
Standard benchmark dataset for generative models
Works on free Google Colab GPU tier (~30 minutes training time)

Key Concepts Covered

Forward and reverse diffusion processes
Noise scheduling and timestep embeddings
U-Net-style architecture for denoising
Generative AI vs. discriminative AI
GPU-accelerated training with CUDA
Image generation evaluation

How to Run

Open the .ipynb file in Google Colab
Go to Runtime → Change runtime type → GPU
Run all cells in order from top to bottom
Training takes approximately 30 minutes on a free Colab GPU

Dependencies
pip install torch torchvision einops matplotlib pillow numpy
Learning Outcomes

Understood how diffusion models work as the backbone of modern generative AI
Gained hands-on experience building and training a generative model from scratch
Learned the mathematical intuition behind adding and removing noise from data
Connected diffusion concepts to real-world tools like DALL-E and Stable Diffusion
