## Colorization Autoencoder

This project implements an autoencoder model for converting grayscale images into color images. The model is built using convolutional layers and trained on a dataset of grayscale and corresponding color images. The autoencoder learns to reconstruct color images from their grayscale versions.

### Project Overview

Input: Grayscale images (single channel).

Output: Colorized images (three channels: RGB).

Model Architecture: A convolutional autoencoder consisting of an encoder that compresses the grayscale images into a lower-dimensional representation and a decoder that reconstructs the color images from this representation.

Data Preprocessing: The input images are resized and normalized before being fed into the model.

Training: The model is trained using the Mean Squared Error (MSE) loss function and optimized with the Adam optimizer.

Visualization: After training, the model's predictions are visualized by comparing the original grayscale images, the colorized outputs, and the original color images.

!images/output.png

!images/output1.png

!images/output2.png

!images/output3.png
