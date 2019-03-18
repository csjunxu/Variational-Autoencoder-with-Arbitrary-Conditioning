# Variational Autoencoder with Arbitrary Conditioning

## Introduction
This is a PyTorch implementation of the ICLR 2019 paper `Variational Autoencoder with Arbitrary Conditioning'. More details will be added soon.


## Qualitative Results
Here are some qualitative results on MNIST.

![mnist-test](https://github.com/rohitrango/ICLR-challenge/blob/master/images/MNIST/0.png)
![mnist-test](https://github.com/rohitrango/ICLR-challenge/blob/master/images/MNIST/1.png)
![mnist-test](https://github.com/rohitrango/ICLR-challenge/blob/master/images/MNIST/2.png)
![mnist-test](https://github.com/rohitrango/ICLR-challenge/blob/master/images/MNIST/3.png)
![mnist-test](https://github.com/rohitrango/ICLR-challenge/blob/master/images/MNIST/4.png)
![mnist-test](https://github.com/rohitrango/ICLR-challenge/blob/master/images/MNIST/5.png)
![mnist-test](https://github.com/rohitrango/ICLR-challenge/blob/master/images/MNIST/6.png)
![mnist-test](https://github.com/rohitrango/ICLR-challenge/blob/master/images/MNIST/7.png)
![mnist-test](https://github.com/rohitrango/ICLR-challenge/blob/master/images/MNIST/8.png)
![mnist-test](https://github.com/rohitrango/ICLR-challenge/blob/master/images/MNIST/9.png)


## Quantitative Results

### MNIST
The only metric the paper supplied was the negative log-likelihood. Although the log-likelihood doesn't make much sense since there can be many probable images with the same value of observed image, and hence a single solution may not be the image corresponding to the ground truth but may still be feasible.

|		| Negative log-likelihood | 
|-------|-------------------------|
|MNIST	| 0.18557				  |


## Updates
**17 Mar 2019:** Set up the directory structure and general flow of the paper after reading and understanding the paper at the implementation level. Added dataloaders for MNIST and CelebA.

**19 Mar 2019:** Compiled results for MNIST. Qualitative results look good, although not as diverse as the paper showed. Quantitative results are in the table. 

