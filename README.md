# Anime_DCGAN

Using a computer to generate images with realistic images is a new direction in
current computer vision research. This paper designs an image generation model
based on the Generative Adversarial Network (GAN). This paper creates a model
– a discriminator network and a generator network by eliminating the fully
connected layer in the traditional network and applying batch normalization and
deconvolution operations. This paper also uses a hyper-parameter to measure the
diversity and quality of the generated image. The experimental results of the
model on the CelebA dataset show that the model has excellent performance in
face image generation. In this report we take this approach to an entirely new
type of style, I.e hand drawn animation. This is inherently challenging due to the
fact that CelebA dataset contains data of similar style, real world palette. But, In
terms of anime, the art style differs and palette is volatile at best.

## Description
With the increasing use of deep learning in the field of computer vision,
automatic image generation based on depth models has received more and more
attention. By using the powerful learning ability of the depth model, the inherent
distribution law in the data can be efficiently mined to generate images with
similar distribution.High-quality generated images can also be used to expand the
amount of image data in the dataset, which can alleviate the need for a large
number of training samples during deep learning model training, so that practical
applications such as face recognition have higher accuracy.

## Goal
The main objective of developing this project is
- To develop a Architecture that is able to handle a Volatile pattern of images
and able to successfully generate new images based on learned latent
distribution.
- To determine the faults and mode collapse conditions which may lead to
breakdown of GAN


#### [Data and Trained Model Weights](https://drive.google.com/drive/folders/1qB8MBNXQ19SfWhtTkIxYyW2Te18Tl0jr?usp=sharing)

#### [Detailed implementation Document](https://github.com/sirreajohn/Anime_DCGAN/blob/main/BATCH_3_Animated%20Background%20Character%20Generation%20Based%20On%20Generative%20Adversarial%20network.pdf)
