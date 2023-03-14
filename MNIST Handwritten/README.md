
### Description of an MNIST handwritten project

### Introduction:
The MNIST (Modified National Institute of Standards and Technology) dataset is one of the most popular and widely used datasets in the field of computer vision and machine learning. The dataset consists of 70,000 images of handwritten digits, where 60,000 images are used for training, and the remaining 10,000 images are used for testing. In this project, we develop a machine learning model to recognize and classify the digits in the MNIST dataset using the TensorFlow Keras API.

### Data Preprocessing:
Before feeding the data into the neural network, we first preprocess the data to make it suitable for training. The first step in preprocessing is to normalize the pixel values in the input images by dividing them by 255.0. This step ensures that the pixel values are in the range of 0 to 1, which helps in faster convergence of the model during training. Next, we reshape the input images to a 1D array of size 784 (28x28), which represents the total number of input features.

### Model Architecture:
The neural network architecture used in this project consists of an input layer, three hidden layers, and an output layer. The input layer has 784 neurons, which correspond to the size of the input image. The first hidden layer has 128 neurons, followed by a second hidden layer with 64 neurons, and a third hidden layer with 16 neurons. Each hidden layer uses the ReLU (Rectified Linear Unit) activation function, which is known to perform well in deep neural networks. The output layer has 10 neurons, which correspond to the 10 digit classes (0 to 9) in the MNIST dataset. The output layer uses the softmax activation function, which produces probability scores for each class.

### Model Training:
The model is trained using the Adam optimizer, which is an adaptive learning rate optimization algorithm. The loss function used in the model is sparse categorical cross-entropy, which is suitable for multi-class classification problems. During training, we use a batch size of 1000 and train the model for 100 epochs. The training process produces a history object, which contains the loss and accuracy metrics for the training and validation datasets at each epoch.

### Model Evaluation:
After training the model, we evaluate its performance on the test dataset. The test dataset contains 10,000 images of handwritten digits, which the model has not seen before. We use the evaluate() method to calculate the loss and accuracy metrics for the test dataset. The model achieves a test accuracy of 97.67%, which is a good indication of its generalization ability.

To further evaluate the model's performance, we use a confusion matrix to visualize the number of correct and incorrect predictions for each digit class. The confusion matrix helps us identify which digit classes are easy or difficult for the model to classify. We also plot the learning curves for the training and validation datasets, which help us identify if the model is overfitting or underfitting the data.

### Conclusion:
In conclusion, the MNIST Handwritten Digits Recognition project demonstrates the use of machine learning algorithms for image recognition and classification tasks. The project highlights the importance of data preprocessing, selecting appropriate activation functions and optimization algorithms, and evaluating model performance. The project's model can be used in various applications, such as digit recognition in financial documents or postal services. The project serves as a foundation for more advanced image recognition and classification tasks using deep learning techniques.

For the code, documentation and additional information, please refer to the [ML_MNIST_Handwritten_Project.ipynb](https://github.com/nhBasavaraj/nhBasavaraj/blob/main/MNIST%20Handwritten/MNSIT%20Project%20.ipynb)



NOTE:  📌⚠️ Note that this project requires a GPU to run for faster training. If you do not have a GPU in your local environment, you can use Google Colab to run the project, Here you go [Google Colab](https://colab.research.google.com/).

NOTE: 📌  For any queries or mistakes was done from my end, that need to modify Please do reach out me in [LinkedIn](https://www.linkedin.com/in/basavaraj-n-hirebidari-94982b1a9)
