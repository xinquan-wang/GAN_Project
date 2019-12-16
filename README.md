
# STAT5242 GAN Project

In this project, we explored the topic of Generative Adversarial Networks and built several models implementations using the Keras library. The models are implemented for two datasets: MNIST and SVHN.   
              
For MNIST, we ran a simple GAN with CNN layers as a baseline model and modified the architecture and hyper-parameters to generate a more advanced model. For SVHN, we applied the advanced model from MNIST first to see if there's any differenes in the quality compared to the GAN on MNIST. We also explored different architecture of neural networks and hyperpa-rameters. As an improved method, WGAN was implemented and compared with the traditional GAN method. 

- The dataset can be downloaded at
	- MNIST dataset: http://yann.lecun.com/exdb/mnist/
	- SVHN dataset(Format 2): http://ufldl.stanford.edu/housenumbers/


## Models

GAN_WGAN_MNIST.ipynb: GAN and WGAN models on MNIST dataset

GAN_WGAN_SVHN.ipynb: GAN and WGAN models on SVHN dataset


## Results

The resulting pictures, gifs and plots of loss can be found in the output folder.

- MNIST

|Baseline|Advanced|WGAN|
|:-:|:-:|:-:|
|![](./Output/MNIST/[Tutorial]image/image_at_epoch_0100.png)|![](./Output/MNIST/[Modified]image/image_at_epoch_0100.png)|![](./Output/MNIST/[WGAN]image/image_at_epoch_0100.png)|


|Generator loss|Discriminator loss|
|:-:|:-:|:-:|
|![](./Output/MNIST/Loss/gen_loss_MNIST.png)|![](./Output/MNIST/Loss/disc_loss_MNIST.png)

- SVHN

|Baseline|Advanced|WGAN|
|:-:|:-:|:-:|
|![](./Output/SVHN/[Tutorial]image/image_at_epoch_0200.png)|![](./Output/SVHN/[Modified]image/image_at_epoch_0096.png)|![](./Output/SVHN/WGAN/image_at_epoch_0200.png)|



## Reference
- Goodfellow, Ian, et al. "Generative adversarial nets." Advances in neural information processing systems. 2014. (Full paper: http://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf)
             
- https://www.tensorflow.org/tutorials/generative/dcgan
