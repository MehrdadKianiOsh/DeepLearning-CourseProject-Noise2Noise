# DeepLearning-CourseProject-Noise2Noise

This project is consisting of two mini projects:

One can download the images from Kaggle: 
https://www.kaggle.com/datasets/mehrdadkianiosh/noisy-images

Mini-project 1: Noise2Noise is able to reconstruct a signal from learning exclusively from the corrupt signals. In this case, we use this idea to denoise 
blurry images without training the model with clear images. With the U-Net model that we implemented according to the paper, we have achieved peak signal 
to noise ratio (PSNR) of 25.55 db on the validation set.

Mini-project 2: In this project, the goal is to create a framework from the ground up that can be used to apply the Noise2Noise model to denoise a 
picture that lacks clean data. To do this, we will construct several modules such as the convolution module, activation functions, loss function, 
and optimizers while only using the main Python libraries, as well as the Pytorch’s tensor, unfold, and fold. The goal of this project was to implement 
a library similar to PyTorch by our own and it was a success. The best achieved PSNR is 24.37 dB.
