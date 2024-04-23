# MNIST Generative Adversarial Network (GAN) Training

## Introduction to Generative Adversarial Networks (GANs)
Generative Adversarial Networks (GANs) are a class of machine learning models introduced by Ian Goodfellow and his colleagues in 2014. GANs consist of two neural networks, a generator and a discriminator, which are trained simultaneously through a competitive process. The generator aims to produce data (e.g., images) that are indistinguishable from real data, while the discriminator learns to distinguish between real and fake data. This adversarial training process results in the generator improving over time and generating increasingly realistic samples.

## Introduction to MNIST Dataset
The MNIST dataset is a widely-used benchmark dataset in machine learning, consisting of 28x28 pixel grayscale images of handwritten digits (0-9). It contains 60,000 training images and 10,000 test images, with each image labeled with the corresponding digit. MNIST is commonly used for tasks such as digit recognition, classification, and generative modeling.

## Requirements
- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- tqdm

## Usage
1. Clone the repository:

2. Run the training script:

3. Check the generated images:
- The generated images will be saved in the `generated_images` folder.
- Each image filename includes the epoch number.

## Training Process
- The GAN is trained using batches of real MNIST images along with generated images.
- The discriminator is trained to distinguish between real and fake images.
- The generator is trained to generate images that are classified as real by the discriminator.
- Training progresses through multiple epochs, with both generator and discriminator improving over time.

## Results
- The model learns to generate realistic handwritten digits resembling those in the MNIST dataset.
- Generated images are saved in the `generated_images` folder, with each image labeled with the epoch number.
  
![image](https://github.com/raselmeya94/GAN_On_MNIST/blob/main/Digits.gif)

## Contributing
- Contributions are welcome! Please feel free to submit pull requests or open issues for any improvements or bug fixes.

## Credits
- This project is based on the concept of Generative Adversarial Networks (GANs) introduced by Ian Goodfellow and his colleagues.
- The code structure and implementation are inspired by various GAN tutorials and resources available online.
