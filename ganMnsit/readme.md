# **Generative Adversarial Network (GAN) - Image Generation using MNSIT dataset**

This repository implements a Generative Adversarial Network (GAN) for generating realistic images from random noise. The model is trained using adversarial training, where a Generator learns to create images that fool a Discriminator, and the Discriminator learns to distinguish between real and fake images.

GANs are a class of neural networks designed for unsupervised learning and generative tasks. This project demonstrates:
- How to train a GAN for image synthesis.
- The adversarial process between the **Generator** and **Discriminator**.
- Image generation progression through training.

## **How GANs Work**

1. **Generator**: Takes random noise as input and generates realistic-looking images.
2. **Discriminator**: Takes images as input and classifies them as real or fake.
3. **Adversarial Training**: The Generator improves by trying to fool the Discriminator, while the Discriminator improves by distinguishing real from fake.

The two networks are trained simultaneously in a zero-sum game.

## **Project Highlights**

- **Noise Input**: A latent vector sampled from a Gaussian distribution.
- **Generator Architecture**: Uses transposed convolution layers to create images.
- **Discriminator Architecture**: Uses convolutional layers to classify images.
- **Training Metrics**: Tracks Generator and Discriminator losses over epochs.

## **Results**

### **Image Generation Progression**

Below are snapshots of generated images at different epochs, showcasing how the Generator improves over time:

#### **Epoch 0 (Random Noise):**
![Epoch 0](https://github.com/srujan-b/Gans/blob/main/ganMnsit/images/mnist_0.png)

#### **Epoch 10000:**
![Epoch 10000](https://github.com/srujan-b/Gans/blob/main/ganMnsit/images/mnist_10000.png)

#### **Epoch 20000:**
![Epoch 20000](https://github.com/srujan-b/Gans/blob/main/ganMnsit/images/mnist_20000.png)

#### **Epoch 30000:**
![Epoch 30000](https://github.com/srujan-b/Gans/blob/main/ganMnsit/images/mnist_30000.png)

#### **Epoch 40000:**
![Epoch 40000](https://github.com/srujan-b/Gans/blob/main/ganMnsit/images/mnist_40000.png)

#### **Epoch 50000:**
![Epoch 50000](https://github.com/srujan-b/Gans/blob/main/ganMnsit/images/mnist_50000.png)

#### **Epoch 60000:**
![Epoch 60000](https://github.com/srujan-b/Gans/blob/main/ganMnsit/images/mnist_60000.png)

#### **Epoch 70000:**
![Epoch 70000](https://github.com/srujan-b/Gans/blob/main/ganMnsit/images/mnist_70000.png)

#### **Epoch 80000:**
![Epoch 80000](https://github.com/srujan-b/Gans/blob/main/ganMnsit/images/mnist_80000.png)

#### **Epoch 90000:**
![Epoch 90000](https://github.com/srujan-b/Gans/blob/main/ganMnsit/images/mnist_90000.png)
