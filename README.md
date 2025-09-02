# Detection_of_GAN_Generated_Image
Classifying a image as Fake/Real

140K real and fake faces (RGB, 64px) - real Flickr faces and StyleGAN-generated images

CNN acts as a StyleGAN discriminator

Enhanced generalization and robustness by creating augmented (flips, rotations, color jitter) and 2D FFT-transformed
input images, enabling the model to capture both spatial and frequency-domain artifacts characteristic of manipulated
media.

Incorporated interpretability with Grad-CAM visualizations to highlight discriminative facial regions, providing transparent
insights into decision-making .
