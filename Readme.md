# Utkarsh Shukla 231AI040

## Table of Contents 
1.) Task 1 - Kaggle Competition

    Subtask 1.2 - NLP

2.) Task 2 - Underwater Image Enhancement Project

    Subtask 2.1 - VAE
    
    Subtask 2.2 - GANs on MNIST Dataset
    
    Subtask 2.3 - GANs on dataset
    
    Subtask 2.4 - Diffusion Model

## Task 1 - NLP
For this subtask , I used sklearn. I mainly used Bag of Words with the XGBoost classifier. I used BayesSearchCV for cross-validation. 
I used F1 as an evaluation metric here. 

## Task 2

### Subtask 2.1

I used a Variational Autoencoder (VAE) model to enhance underwater images.

### Subtask 2.2

I implemented a GAN model on the MNIST dataset and generated new digit samples.

### Subtask 2.3

For this subtask, I implemented a GAN model on the provided dataset. I used pix2pix loss function as given with UNET and PatchGAN.

### Subtask 2.4

To implement the diffusion model for underwater image enhancement, I used forward and reverse processes with Simple UNet.

# Conclusion
    Evaluations
    
    Models     PSNR         SSIM       MSE
    VAE      18.7001      0.6258     0.0187
    GAN      14.5933      0.5410     0.0461
    Diff     16.3050      0.4945     0.0297
