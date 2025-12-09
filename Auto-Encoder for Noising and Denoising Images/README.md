# DenoiseNet

## Description
DenoiseNet is a convolutional autoencoder that removes noise from images, enhancing quality and visual appeal by reconstructing clean images from noisy inputs.

## Dataset & Noise
Uses CIFAR-10 (60,000 32x32 color images) with Gaussian noise added to simulate real-world scenarios for training.

## Model Architecture
- **Encoder:** Convolution + max pooling to extract features.  
- **Decoder:** Up-sampling + convolution to reconstruct images.  

## Training
Trained for 50 epochs using MSE loss and Adam optimizer to learn effective denoising.

## Results
Visualizes original noisy images, denoised outputs, and clean images to showcase performance.

## Applications
Useful in photography, video processing, medical imaging, and other tasks where image quality matters.
