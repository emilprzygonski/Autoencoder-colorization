# Autoencoder-colorization
If you're getting error "Sorry, something went wrong. Reload?" please visit https://nbviewer.jupyter.org and paste the URL from Github.

## Data
Dataset contains first 10k face images from Large-scale CelebFaces Attributes (CelebA) Dataset. CelebFaces Attributes Dataset (CelebA) is a large-scale face attributes dataset with more than 200K celebrity images, each with 40 attribute annotations. The images in this dataset cover large pose variations and background clutter. CelebA has large diversities, large quantities, and rich annotations, including

## Project purpose
The purpose of this project is to build simple Convolutional Autoencoder that learns to extract the useful set of signals and then try to reconstruct the input. Usually in autoencoders input and output is the same picture, but in this case it's not. All images are converted to LAB color space, so first layer (image in grayscale) is input and 2 other layers are output.

Dataset from: http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
