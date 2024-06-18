# Neural Network for Cat and Dog Classification

In this project, i developed a neural network to classify images as either a dog or a cat. To train the neural network, i processed 2000 images of each class (dogs and cats). The steps involved in this process are as follows:

**Image Collection**: We gathered 2000 images of cats and 2000 images of dogs. These images serve as the dataset for training the neural network.

**Data Preprocessing**:

**Pixel Extraction**: We extracted pixel values from each image. This step converts the images from matrix into vector format that can be used by the neural network.

**Normalization**: The pixel values were normalized to improve the neural network's performance. Normalization typically involves scaling the pixel values to a range of 0 to 1, which helps in accelerating the training process and achieving better accuracy.

**Neural Network Architecture**: A suitable neural network architecture was designed to classify the images. This network consists of layers such as convolutional layers, pooling layers, and fully connected layers. The architecture is designed to capture and learn the features that distinguish cats from dogs.

**Training**: The preprocessed images were used to train the neural network. During training, the network learns to identify patterns and features that are unique to each class (cats and dogs). The learning process involves adjusting the network's weights based on the error in its predictions.

  ![Screenshot (47)](https://github.com/Davlegbish/Dog-and-Cat-Classification/assets/155652335/98202687-b63e-430b-a48f-0b545e6ad5b0)
  

**Evaluation**: After training, the neural network's performance was evaluated using a separate set of images that were not included in the training dataset. This step ensures that the network can generalize its learning to new, unseen images.

![Screenshot (50)](https://github.com/Davlegbish/Dog-and-Cat-Classification/assets/155652335/bb826a55-8c4c-43a0-b48e-54a372f2bd35)


By following these steps, the neural network was trained to accurately classify images as either a dog or a cat. The preprocessing steps, particularly pixel extraction and normalization, were crucial in improving the network's prediction accuracy.

![Screenshot (49)](https://github.com/Davlegbish/Dog-and-Cat-Classification/assets/155652335/eb8ed5e5-b59f-4325-afe9-03323265919c)


**Challenges Encoutered**
1. Slow pixel Extraction From Image's:
   The procedure for retrieving pixel information from images is taking longer than expected, due high resolution from the images.

2. Slow Eposh Speed:
   The duration for completing each training epoch is longer than anticipated, due to the  large dataset size and complex model architecture.







