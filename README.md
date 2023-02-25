![img]("img.jpeg")

This project aims to classify four types of citrus fruit diseases on the basis of images of oranges using Convolutional Neural Networks (CNN). The CNN model has been trained on a dataset containing images of diseased and healthy oranges



<h1>Dataset</h1>

The dataset used for training and testing the model consists of 1,164 images of oranges that are divided into four classes: Canker, Blackspot, Greening, and Fresh. The images. Data augmentation is used to increase the size of the training dataset by applying different transformations to the original images. The following transformations were applied to the images during training:

*Random horizontal flip

*Random vertical flip

*Random rotation

*Resizing

*Rescaling



<h2>Model Architecture</h2>

The CNN model used for this project has been built using Keras, which is an open-source neural network library. The model consists of six convolutional layers, followed by max-pooling layers, and then two fully connected layers. ReLU activation has been used in the convolutional layers, and softmax activation has been used in the fully connected layer to obtain the probabilities of each class.



<h3>Training and Testing</h3>

The dataset has been split into training, validation, and testing sets, with a split ratio of 8:1:1. The model has been trained for 20 epochs with a batch size of 32. The Adam optimizer has been used.


<h4>Results</h4>

The CNN model has achieved an accuracy of 89.84% on the testing set, which is a good performance.


<h5>Conclusion</h5>

In conclusion, this project demonstrates the effectiveness of using deep learning techniques, specifically CNNs, for the classification of citrus fruit diseases. The model has shown promising results, and it can be further improved by using more advanced techniques such as transfer learning and data augmentation.
