# DENOISING_CNN-AUTOENCODER
IMAGE DENOISING USING CONVOLUTIONAL AUTOENCODER
1. Prepare the dataset: Our dataset(fashion_mnist) is take and normalized so that the pixel values lie between 0 and 1, after this gaussian noise is added to our data to create a set of noisy images for input

2. Build the Convolutional Autoencoder: Use a deep learning framework such as TensorFlow or Keras to build the Convolutional Autoencoder. The encoder should consist of several convolutional layers, followed by pooling layers. The decoder should consist of several convolutional layers, followed by Upsampling layers.

3. Train the Convolutional Autoencoder: Train the Convolutional Autoencoder on the noisy dataset. During training, the Autoencoder should learn to map the noisy images to their corresponding clean images. The loss function should be a pixel-wise mean squared error between the predicted and true images.

4. Denoise New Images: Once the model is trained and evaluated, use it to denoise new images. Pass a noisy image through the encoder to obtain a latent representation. Then, pass the latent representation through the decoder to obtain a denoised image.

5. Visualize the Results: Visualize the results by comparing the noisy images, the denoised images, and the ground truth clean images.

