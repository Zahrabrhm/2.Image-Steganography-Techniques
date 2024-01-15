# Image Steganography Techniques

This repository contains implementations of various image steganography techniques. These techniques allow you to hide information within images, making them virtually undetectable to the naked eye. 

## Table of Contents

- [Among Pixels Method](#among-pixels-method)
- [LSB (Least Significant Bit) Method](#lsb-least-significant-bit-method)
- [Fourier Domain Method](#fourier-domain-method)

## Among Pixels Method

The "Among Pixels" method of image steganography involves hiding information by subtly manipulating the relationships between neighboring pixels. By strategically adjusting pixel values, it's possible to embed a message while minimizing visual impact. This technique often employs algorithms that exploit the spatial correlation among adjacent pixels in an image.

## LSB (Least Significant Bit) Method

The "LSB" method is one of the simplest and widely used image steganography techniques. In this method, the least significant bits of the pixel values in an image are altered to encode the secret message. Since the human eye is less sensitive to changes in the least significant bits, this technique allows for a relatively imperceptible embedding of information.

## Fourier Domain Method

The "Fourier Domain" method involves applying transformations to the image in the frequency domain, such as the Discrete Fourier Transform (DFT) or Discrete Cosine Transform (DCT). By manipulating the frequency components, information can be hidden within the image while maintaining a level of robustness against certain types of attacks.

# Image Results

Below are examples of the results obtained from implementing the image steganography techniques.

## Among Pixels Method

![Among Pixels Result](./Results/Betweenpixels.png)


## LSB (Least Significant Bit) Method

![LSB Result](./Results/LSB.png)

## Fourier Domain Method

![Fourier Domain Result](./Results/FurierDOmain.png)



