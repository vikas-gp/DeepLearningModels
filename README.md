# Deep Learning Project  
## Image Classification and Image Generation using ANN, CNN, Transfer Learning and GANs

---

## Project Overview

This project presents a structured study of deep learning models for image classification and image generation.
The work progresses from basic neural networks to advanced architectures, focusing on how model design and training strategies affect performance and generalization.

The project is divided into four stages:
- Artificial Neural Networks (ANN)
- Convolutional Neural Networks (CNN)
- Transfer Learning Models
- Generative Adversarial Networks (GANs)

---

## Datasets Used

- MNIST Dataset – Used for ANN models (digit classification)  
- CIFAR-10 Dataset – Used for CNN models (object classification)  
- Oxford Flowers 102 Dataset – Used for transfer learning  
- CelebA Dataset – Used for GAN models (face generation)  

---

## Technologies Used

- TensorFlow / Keras – ANN and CNN models  
- PyTorch – Transfer Learning and GAN models  
- Ultralytics YOLOv8 – Classification model  

---

## Models Implemented

### ANN
- Baseline ANN  
- Regularized ANN (Dropout + Early Stopping)

### CNN
- Baseline CNN  
- Regularized CNN (Batch Normalization + Dropout)  
- Grayscale + Data Augmentation Model  
- Deeper CNN with Global Pooling  
- Learning Rate Experiment  

### Transfer Learning
- ResNet50 (Feature Extraction + Fine-tuning)  
- Vision Transformer (ViT-B16)  
- YOLOv8 Classification Model  

### GAN
- Base GAN (Fully Connected)  
- DCGAN (Convolutional GAN)  
- StyleGAN (Pretrained Model)  

---

## Key Findings

- Regularization improves generalization and reduces overfitting  
- CNNs outperform ANN for image-based tasks  
- Transfer learning significantly improves accuracy and convergence speed  
- Vision Transformers achieve the best classification performance  
- GAN models show progressive improvement in image generation quality  

---

## Notes

- Large datasets are not included due to size constraints  
- CelebA dataset should be downloaded from Kaggle  
- StyleGAN uses pretrained weights  
- The project is implemented as an experimental comparative study  

---
