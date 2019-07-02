# variationalAutoEncoder

This project implements a Variational Autoencoder on the MNIST digits. It's in a Jupyter notebook. The last few cells show the end result. The first picture shows transitioning between two different writings of the same digit, for each digit 0-9. The second picture shows transitions between two different digits. This project was based on the course AML 498 offered by teh University of Illinois. Link to project: https://courses.engr.illinois.edu/cs498aml/sp2019/homeworks/homework9.html

The description of the project, as shown on that page, is:

## Problems

An autoencoder is a type of artificial neural network used to learn efficient data codings in an unsupervised manner. Variational autoencoder (VAE) models inherit the autoencoder architecture, but make strong assumptions concerning the distribution of latent variables.

For 10 pairs of MNIST test images of the same digit (1 pair for "0", 1 pair for "1", etc.), selected at random, compute the code for each image of the pair. Now compute 7 evenly spaced linear interpolates between these codes, and decode the result into images. Prepare a figure showing this interpolate. Lay out the figure so each interpolate is a row. On the left of the row is the first test image; then the interpolate closest to it; etc; to the last test image. You should have a 10 rows (1 row per digit) and 9 columns (7 interpolates + 2 selected test images) of images

For 10 pairs of MNIST test images of different digits selected at random, compute the code for each image of the pair. Now compute 7 evenly spaced linear interpolates between these codes, and decode the result into images. Prepare a figure showing this interpolate. Lay out the figure so each interpolate is a row. On the left of the row is the first test image; then the interpolate closest to it; etc; to the last test image. You should have a 10 rows and 9 columns of images.
