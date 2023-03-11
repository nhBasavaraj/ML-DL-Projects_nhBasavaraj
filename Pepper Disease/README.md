NOTE:  📌⚠️ Note that this project requires a GPU to run due to the large amount of dataset. If you do not have a GPU in your local environment, you can use Google Colab to run the project, Here I used the [Google Colab](https://colab.research.google.com/).

NOTE: 📌  For any queries or mistakes was done from my end, that need to modify Please do reach out me in [LinkedIn](https://www.linkedin.com/in/basavaraj-n-hirebidari-94982b1a9)

Pepper Disease Detection is a deep learning project that aims to classify pepper plant images as healthy or diseased. The project consists of the following key components:

Dataset bifurcation: The dataset is divided into three subsets - training, validation, and test. The training subset is used to train the model, the validation subset is used to evaluate the model during training, and the test subset is used to evaluate the final model.

Resizing and normalization: The input images are resized to a desired size (256x256) and normalized to improve model performance. A layer is added to the model for resizing and normalization of the input images.

Data augmentation: Data augmentation techniques are applied to the training dataset to increase the number of training samples and reduce overfitting. Techniques like rotation, zooming, and horizontal flipping are used to generate new images.

Convolutional Neural Network: The model architecture is based on the Convolutional Neural Network (CNN) layers, which are effective for image classification tasks. The model consists of several convolutional layers, each followed by a max-pooling layer, to extract and learn the features of the input images.

Softmax activation: The final layer of the model uses the Softmax activation function to output the class probabilities. Softmax converts the output values of the model into probabilities that sum up to 1.

Adam optimizer: The model is trained using the Adam optimizer, which is a popular optimization algorithm for training deep learning models. Adam optimizer adapts the learning rate of each parameter based on the gradient and the second moment of the gradients.

SparseCategoricalCrossentropy loss function: The loss function used in the project is Sparse Categorical Crossentropy, which is commonly used for multiclass classification tasks. The loss function measures the difference between the predicted and actual class labels.

Model evaluation: The model is evaluated using metrics like accuracy and loss. During training, the model achieves a high accuracy of 99.95% and a low loss of 0.0033 on the training set. The validation set is used to evaluate the model during training, achieving a validation accuracy of 100% and a validation loss of 0.0069. Finally, the test set is used to evaluate the model, achieving an accuracy of 98.96% and a loss of 0.0299.

Application: The trained model can be used by farmers to detect and diagnose plant diseases, helping them to take necessary preventive measures and minimize crop losses. The model can be integrated into a mobile app or a web application to make it accessible to a wider audience.

The code and the dataset used in this project are open-sourced and can be accessed from this repository.

For the code, documentation and additional information, please refer to the [Pepper Disease.ipynb](https://github.com/nhBasavaraj/nhBasavaraj/blob/main/Pepper%20Disease/DS_DL_Pepper_project.ipynb)

