NOTE:  📌⚠️ Note that this project requires a GPU to run due to the large amount of dataset. If you do not have a GPU in your local environment, you can use Google Colab to run the project, Here I used the [Google Colab](https://colab.research.google.com/).

NOTE: 📌  For any queries or mistakes was done from my end, that need to modify Please do reach out me in [LinkedIn](https://www.linkedin.com/in/basavaraj-n-hirebidari-94982b1a9)


### Objective:
The objective of this project is to use deep learning techniques to accurately classify images of potato plants into three categories: early blight, late blight, and healthy. The goal is to build a model that can help farmers detect the signs of disease in their crops early, allowing them to take action before the disease spreads and damages the crop.

### Dataset:
The project uses a dataset of labeled images of potato plants that were collected from various sources. The images were preprocessed and labeled, and then split into three subsets: training, validation, and test. The training set is used to train the model, the validation set is used to tune the model hyperparameters and avoid overfitting, and the test set is used to evaluate the final model performance.

### Model:
The model is a convolutional neural network (CNN) that takes in an input image of size 256x256 and outputs a probability distribution over the three classes. The model architecture includes multiple convolutional layers with ReLU activation, max pooling layers, and dense layers with softmax activation. To improve model performance, the input images are preprocessed using a sequence of data augmentation techniques, including random flipping and rotation.

### Training:
The model is trained using the training dataset with the Adam optimizer and Sparse Categorical Crossentropy loss function. During training, the model is evaluated on the validation dataset to tune the hyperparameters and avoid overfitting. The training process continues until the model achieves satisfactory performance on both the training and validation datasets.

### Evaluation:
The final model is evaluated on the test dataset to estimate its real-world performance. The evaluation metrics include loss and accuracy, which measure how well the model can predict the correct class labels for the test images. The model achieved a high accuracy score of 99.61% on the test dataset, indicating that it can accurately classify images of potato plants into early blight, late blight, and healthy categories.

### Application:
The trained model can be used to detect and classify diseases in potato crops in real-world scenarios. Farmers can take pictures of their crops and use the model to classify the images into one of the three categories. This allows farmers to take action quickly and prevent further spread of disease, ultimately improving crop yields and reducing economic losses.

#### For the code, documentation and additional information, please refer to the [Potato Disease.ipynb](https://github.com/nhBasavaraj/nhBasavaraj/blob/main/Potato%20Disease/DS_DL_Potato_project.ipynb)

