# Handwritten-Digit-Recognition with TensorFlow

This project demonstrates a deep learning model for recognizing handwritten digits from the MNIST (Modified National Institute of Standards and Technology) dataset. The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9), with 60,000 images in the training set and 10,000 images in the test set.

The model architecture used in this example consists of two fully connected (dense) hidden layers with 128 and 64 units, respectively, and a softmax output layer with 10 units (one for each digit class). The model is trained using the Adam optimizer and categorical cross-entropy loss.
After training the model for 10 epochs, the final test accuracy achieved is 97.71%, which is a strong performance on this benchmark dataset. The project also includes visualization of sample images from the dataset and the training/validation accuracy and loss curves.

This example provides a solid foundation for understanding and implementing handwritten digit recognition using deep learning techniques. It can be further extended to explore more advanced architectures, hyperparameter tuning, and techniques like data augmentation to improve the model's performance.
