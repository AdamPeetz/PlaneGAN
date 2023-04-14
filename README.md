# PlaneGAN

Generative Adversarial Networks for Images

DCGAN with 16 million parameters displays its training outputs every 10 epochs:

![alt text](https://github.com/AdamPeetz/imagehosting/blob/main/aerospace_images_example.jpg) <br>

## Datasets

### Aerospace Dataset

![alt text](https://github.com/AdamPeetz/imagehosting/blob/main/anime_images_example.jpg) <br>

#### Sources

#### Preprocessing Steps

Images scraped from the internet come in many different shapes and sizes. Images must be resized and scaled to a specific dimensions and values before they can be used by the GAN. Scaling down images also reduces the amount of storage space they consume. This allows the model to use fewer resources during its training phase.

AlexNet, a seminal CNN research effort by Krizhevsky et al. (2017), employed an image processing pipeline that downscaled images to 256x256 prior to inputting them in the model. In this pipeline, rectangular images were rescaled around the shortest side, and then the center was cropped out of them.

### Anime Faces

![alt text](https://github.com/AdamPeetz/imagehosting/blob/main/latent_space_gif.gif) <br>

#### Sources

#### Preprocessing Steps

## Models

### Deep Convolutional Generative Adversarial Network (DCGAN)

#### 80 Million Parameter DCGAN Results: Aerospace

#### 60 Million Parameter DCGAN Results: AnimeFaces

### Auxillary Classifier Deep Convolutional Generative Adversarial Network (ACGAN)

#### 110 Million Parameter ACGAN Results: Aerospace

### Conditional Deep Convolutional Generative Adversarial Network (CGAN)

#### X Million Parameter CGAN Results: Aerospace

## Creating GAN images

### Generating Single Images

### Interpolation of latent space 

The input of a generative model is a hypersphere of noise referred to as latent space. The generative network learns to map different points in latent space to features of the dataset it is trained on. Inputting the same point in latent space results in the same generated outcome.  

Points on a curve between areas of latent space can be fed into the model to create a smooth transition between two areas, interpolating the latent space of the model.

![alt text](https://github.com/AdamPeetz/imagehosting/blob/main/latent_space_gif.gif) <br>

# References

Abadi, A., Agarwal, P. B., Brevdo, E., Chen, Z., Citro, C., Corrado, G., Davis, A., Dean, J., Devin, M., Ghemawat, S., Goodfellow, I.,Harp, A., Irving, G., Isard, M., Jozefowicz, R., Jia Y., Kaiser, L., Kudlur, M., Levenberg, J., Mané, D., Schuster, M., Monga, R., Moore, S. Murray, D., Olah, C., Shlens, J., Steiner, B., Sutskever, I., Talwar, K., Tucker, P., Vanhoucke, V., Vasudevan, V., Viégas, F., Vinyals, O., Warden, P., Wattenberg, M., Wicke, M., Yu, Y., & Zheng. X., (2015). TensorFlow: Largescale machine learning on heterogeneous systems. Software available from tensorflow.org ​

Boe, Bryce. (2023). PRAW: The Python Reddit API Wrapper. Reddit.com​

Brownlee, Jason. (2019). Generative Adversarial Networks with Python. Machine Learning Mastery. EBook. ​

Chintala, Soumith. Denton, Emily. Arjovsky, Martin. Mathieu, Michael. (2023). How to Train a GAN? Tips and tciks to make GANs work. Githib. Retreived 4/2/2023 from guthub.com/soumith/ganhacks​

Chollet, Francois. (2015). Keras. GitHub. https://github.com/fchollet/keras  ​

Das Shuvo, Falguni. (2020). Repeatedly calling model.predict(...) results in memory leak. GitHub. Retrieved 3/15/2023 from https://github.com/keras-team/keras/issues/13118 https://machinelearningmastery.com/generative_adversarial_networks/​

Deng, Jia., Dong, Wei., Socher, Richard., Li, Li-Jia., Li, Kia., Fei-Fei, Li. (2009). ImageNet: A large-scale hierarchical image database. IEEE Conference on Computer Vision and Pattern Recognition.   pp. 248-255, doi: 10.1109/CVPR.2009.5206848.​

Harris, C.R., Millman, K.J., van der Walt, S.J. et al. (2020) Array programming with NumPy. Nature 585, 357–362. DOI: 10.1038/s41586-020-2649-2 ​

Hunter, J. D. (2007). Matplotlib: A 2D graphics environment. Computing in Science & Engineering. https://zenodo.org/badge/DOI/10.5281/zenodo.592536.svg ​

Karras, Tero. Aila, Timo. Laine, Samuli. Lehtinen, Jaakko. (2017). Progressive Growing of GANs for Improved Quality, Stability, and Variation. arXiv:1710.10196 ​

Krizhevsky, Alex. Sutskever, Ilya. & Hinton, Geoffrey. (2017). ImageNet classification with deep convolutional neural networks. Communications of the ACM. 60(8). DOI: 10.1145/3065386​

Lower, Jacob. (2022). RedditImageScraper. retrieved 01/13/2023 from https://github.com/ClarityCoders/RedditImageScraper​

OpenCV Team. (2023). ComputerVision2 (cv2). Opencv.org ​

Regis Jesuit University. (2021). MSDS600 Intro to Data Science . Regis University​

Regis Jesuit University. (2022). MSDS660 Deep Learning. Regis University​

Renotte, Nicholas. (2022). GANBasics. Github.com. Retrieved 04/01/2023 from  githuib.com/nicknochnack/GANBasics​

r/carporn. (2023). Image dataset. reddit.com. retrieved 01/20/2023 ​

r/helicopters. (2023). Image dataset. Reddit.com. Retrieved 03/26/2023​

r/tanks. (2023). Image dataset. reddit.com. retrieved 01/20/2023 ​

r/tankporn. (2023). Image dataset. reddit.com. retrieved 01/20/2023 ​

r/warplaneporn. (2023). Image dataset. Reddit.com. Retrieved 03/26/2023

TianbaiYu-Toby. (2022). Anime Girl Faces. dataset. kaggle.com. Retreived 4/14/2023 from https://www.kaggle.com/datasets/tianbaiyutoby/animegirl-faces
