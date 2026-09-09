# Citrus Fruit Disease Classifier

![img]("img.jpeg")

A deep learning project that classifies citrus fruit (oranges) as healthy or diseased using a Convolutional Neural Network (CNN).

## Dataset

The dataset consists of 1,164 images of oranges divided into four classes: **Canker**, **Blackspot**, **Greening**, and **Fresh**. Data augmentation is used to expand the training set via:

- Random horizontal flip
- Random vertical flip
- Random rotation
- Resizing
- Rescaling

## Model architecture

Built with Keras: six convolutional layers followed by max-pooling layers, then two fully connected layers. ReLU activation is used in the convolutional layers, and softmax activation in the final layer to output class probabilities.

## Training & testing

The dataset is split 8:1:1 into training, validation, and testing sets. The model is trained for 20 epochs with a batch size of 32, using the Adam optimizer.

## Results

The model achieves **89.84% accuracy** on the test set.

## Tech stack

- Python
- Keras / TensorFlow
- Jupyter Notebook

## Future work

- Transfer learning from pretrained models (e.g. ResNet, EfficientNet) to improve accuracy
- Additional data augmentation techniques
- Deployment as a simple web or mobile app for real-world use by growers
