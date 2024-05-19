# In-Depth Review and Application of Generative Adversarial Networks (GANs) for Image Generation
## For CSE 575 - Statistical Machine Learning (Spring 2023)


## Overview
This GitHub repository is dedicated to our comprehensive project on Generative Adversarial Networks (GANs), focusing on the application of GANs for generating realistic car images. Our project explores the intricacies of GAN architecture, its training process, and its application in creating high-quality synthetic images that closely mimic real-world objects. This repository contains all the resources, code, and findings of our project.

### Team Members
- Akshat Nambiar (ASU ID: 1225484000)
- Ryan Collins (ASU ID: 1225687957)
- Sahithya Cherukuri (ASU ID: 1226054065)
- Sai Prakash Ravichandran (ASU ID: 1225761147)

## Project Description
Generative Adversarial Networks (GANs) are a class of artificial intelligence algorithms used in unsupervised machine learning, implemented by a system of two neural networks contesting with each other in a game. Through our project, we aim to leverage the power of GANs to generate realistic images of cars that can be used in various applications such as virtual reality, gaming, and automotive design.

### Objectives
- Conduct a thorough literature review on GAN architecture and its variants.
- Collect and preprocess a dataset of car images for training the GAN model.
- Develop a GAN model capable of generating realistic car images.
- Evaluate the model's performance using suitable metrics.
- Explore potential applications and future improvements for the GAN model.

## Dataset
Our dataset comprises over 60,000 car images, collected and preprocessed to train our GAN model effectively. For practical reasons, we initially utilize a subset of 300 images due to computational constraints, aiming to scale as our resources allow.

## Model Architecture
We employed a Deep Convolutional Generative Adversarial Network (DCGAN) for our project. The DCGAN architecture uses convolutional and convolutional-transpose layers in the generator and discriminator, respectively. This choice is motivated by DCGAN's proven effectiveness in generating high-quality images.

## Training Process
The GAN model is trained using an alternating approach, where the generator and discriminator networks are updated sequentially. This training process involves generating a batch of synthetic images, which are then evaluated by the discriminator alongside a set of real images. The networks are trained to minimize respective loss functions, with the ultimate goal of generating realistic images that the discriminator cannot easily distinguish from real ones.

## Results
Our model showed promising results, with the quality of generated images improving significantly over training epochs. Initially, the images lacked detail, but as training progressed, the images became more refined and realistic, capturing intricate details of cars, such as headlights, grills, and logos.

### Epoch Progression Images
- <img width="695" alt="Screenshot 2024-03-04 at 2 53 38 AM" src="https://github.com/aks1804/GANForImageGen/assets/46503137/08a8167f-27ae-49f0-9a5b-db333dc9df34">
- <img width="699" alt="Screenshot 2024-03-04 at 2 53 22 AM" src="https://github.com/aks1804/GANForImageGen/assets/46503137/fdd425dc-7ef6-418e-bb44-bd95669398ec">
- <img width="687" alt="Screenshot 2024-03-04 at 2 53 48 AM" src="https://github.com/aks1804/GANForImageGen/assets/46503137/70778bc4-962b-47d7-a7d6-854b00dd3072">
- <img width="696" alt="Screenshot 2024-03-04 at 2 54 03 AM" src="https://github.com/aks1804/GANForImageGen/assets/46503137/3d0edfcd-bb31-4df6-826a-32f434984c56">


## Conclusions and Future Work
Our project demonstrates the potential of GANs in generating realistic images, with significant implications for various industries. Future directions include exploring more complex GAN architectures, scaling up the dataset, and applying the technology to other domains beyond automotive images.

## Contributions
- Data Collection and Preprocessing: Sai Prakash and Ryan Collins
- Generator Model Development: Ryan Collins
- Discriminator Model Development: Akshat Nambiar
- Literature Review: Sahithya Cherukuri and Sai Prakash
- Model Testing and Refinements: Akshat Nambiar and Sahithya Cherukuri

## How to Use
Please refer to the `Project.ipynb` notebook for a detailed guide on setting up the environment, training the model, and generating images. Additionally, the `requirements.txt` file lists all the necessary dependencies to run the project.

## License
This project is open-source and available under the MIT License. Please refer to the LICENSE file for more details.
