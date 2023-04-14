# PlaneGAN

Generative Adversarial Networks for Airplane Images

This repo is a work in progress

DCGAN with 16 million parameters displays its training outputs every 10 epochs:

![alt text](https://github.com/AdamPeetz/imagehosting/blob/main/DCGANGIF.gif) <br>

# # Creating GAN images: Interpolation of latent space 

The input of a generative model is a hypersphere of noise referred to as latent space. The generative network learns to map different points in latent space to features of the dataset it is trained on. Inputting the same point in latent space results in the same generated outcome.  

Points on a curve between areas of latent space can be fed into the model to create a smooth transition between two areas, interpolating the latent space of the model. 
