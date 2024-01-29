# Variational Autoencoder and Conditional Variational Autoencoder for Clothing Image Generation
## Overview
This repository showcases of training a Variational Autoencoder (VAE) and Conditional Variational Autoencoder (CVAE) using a manually collected dataset of diverse clothing items. The primary objective is to leverage the trained VAE and CVAE for generating novel and aesthetically pleasing images of these clothing items.

## Data Collection 
Our data collection process was meticulous, ensuring a rich diversity within the dataset. We prioritized capturing various styles, colors, and textures, aiming for a comprehensive representation of clothing items. Each clothing item within the dataset is thoughtfully labeled with a unique class. To augment the dataset size and enhance variability, we incorporated techniques such as rotation, flipping, and adjusting lighting.

## Implementation of Variational Autoencoder

The heart of our project lies in the design and implementation of the Variational Autoencoder (VAE). This intricate architecture consists of a carefully crafted encoder, sampling layer, and decoder, ensuring effective learning and the generation of meaningful latent representations. The VAE is specifically tailored to capture the diverse features and styles present in our meticulously curated dataset of clothing items.

## Conditional Variational Autoencoder (CVAE)

Taking our project a step further, we've incorporated a Conditional Variational Autoencoder. This innovative addition empowers the model to generate images with specific class labels, providing enhanced control over the creative process. Now, our VAE not only captures the inherent diversity of clothing items but also allows users to guide the generation process towards desired classes.

## Generation of Acceptable Images
the new images will be created from a hidden space. The measure of success is that the new images must, at the very least, show the unique shape and characteristics of the clothing items. It is expected and required that the new images accurately depict different styles and details.


### GUI Interface with Slider

we've implemented a graphical user interface (GUI) featuring a slider for both VAE and CVAE. This intuitive tool enables users to easily determine the number of images they wish to generate, the number of images to visualize, and the number of class labels for (CVAE). Seamlessly integrated, especially for users on platforms like Kaggle or Colab, this feature enhances the overall user experience and flexibility in image generation.