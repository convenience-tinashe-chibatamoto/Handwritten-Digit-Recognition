# Handwritten-Digit-Recognition with TensorFlow

This project demonstrates a deep learning model for recognizing handwritten digits from the MNIST (Modified National Institute of Standards and Technology) dataset. The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9), with 60,000 images in the training set and 10,000 images in the test set.

The model architecture used in this example consists of two fully connected (dense) hidden layers with 128 and 64 units, respectively, and a softmax output layer with 10 units (one for each digit class). The model is trained using the Adam optimizer and categorical cross-entropy loss.
After training the model for 10 epochs, the final test accuracy achieved is 97.71%, which is a strong performance on this benchmark dataset. The project also includes visualization of sample images from the dataset and the training/validation accuracy and loss curves.

This example provides a solid foundation for understanding and implementing handwritten digit recognition using deep learning techniques. It can be further extended to explore more advanced architectures, hyperparameter tuning, and techniques like data augmentation to improve the model's performance.

<hr>
Improvements :<br><br>
In this example, I used the MNIST dataset which comprises 70 000 images. An alternative could be using the EMNIST data, which is more sizeable, and in my opinion, more preferable. Here's why:<br>
<ul> <li>Dataset Size: The EMNIST dataset contains a total of 814,255 handwritten character images, which is significantly larger than the 70,000 images in the MNIST dataset.</li> <li>Number of Classes: The EMNIST dataset includes 47 different classes, covering the 26 uppercase letters, 26 lowercase letters, and the 10 digits (0-9). This is a much larger set of classes compared to the 10 digit classes in MNIST.</li> <li>Variety: The EMNIST dataset includes handwritten characters from a wider set of writers, making it a more challenging and realistic dataset for broader handwritten character recognition.</li> </ul>
<hr>
