This project aims to classify four types of citrus fruit diseases (Canker, Blackspot, Greening, and Fresh) on the basis of images of oranges using Convolutional Neural Networks (CNN). The CNN model has been trained on a dataset containing images of diseased and healthy oranges.

Dataset
The dataset used for training and testing the model consists of 1578 images of oranges that are divided into four classes: Canker, Blackspot, Greening, and Fresh. The images have been obtained from various sources, including Google Images and USDA Agricultural Research Service.

Model Architecture
The CNN model used for this project has been built using Keras, which is an open-source neural network library. The model consists of two convolutional layers, followed by two max-pooling layers, and then two fully connected layers. ReLU activation has been used in the convolutional layers, and softmax activation has been used in the fully connected layer to obtain the probabilities of each class.

Training and Testing
The dataset has been randomly split into training, validation, and testing sets, with a split ratio of 8:1:1. The model has been trained for 50 epochs with a batch size of 32. The Adam optimizer has been used with a learning rate of 0.001. The model has been evaluated on the testing set and has achieved an accuracy of 89.84%.

Results
The CNN model has achieved an accuracy of 89.84% on the testing set, which is a good performance. The confusion matrix shows that the model has performed well in classifying all the four classes, with Canker having the highest precision and recall values.

Conclusion
In conclusion, this project demonstrates the effectiveness of using deep learning techniques, specifically CNNs, for the classification of citrus fruit diseases. The model has shown promising results, and it can be further improved by using more advanced techniques such as transfer learning and data augmentation.
