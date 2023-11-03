# Handwritten Digits Recognition with Convolutional Neural Network

This project is a 5-layer Sequential Convolutional Neural Network (CNN) designed to recognize handwritten digits from the MNIST dataset. The MNIST dataset is a classic benchmark in computer vision and serves as an excellent resource for testing and comparing various machine learning and deep learning algorithms.

The main objective of this project is to accurately classify tens of thousands of handwritten digit images. We use the Keras API with a TensorFlow backend to build and train the CNN model. Below, we outline the steps involved in the project, from data preparation to model evaluation.


## Data Preparation
1. **Load Data** - We start by loading the MNIST dataset, which contains a vast collection of handwritten digit images.

2. **Check for Null and Missing Values** - We ensure the dataset is clean and ready for processing.

3. **Normalization** - We normalize the pixel values of the images to a common scale.

4. **Reshape** - We reshape the data to prepare it for the CNN model.

5. **Label Encoding** - We encode the labels for training the model.

6. **Split Training and Validation Set** - We split the dataset into training and validation sets for model training and evaluation.

## CNN
1. **Define the Model** - We define a 5-layer CNN architecture for the task of digit recognition.

2. **Set the Optimizer and Annealer** - We specify the optimizer and learning rate annealing for model training.

3. **Data Augmentation** - Data augmentation techniques are applied to enhance the model's robustness.

## Evaluate the Model
1. **Training and Validation Curves** - We visualize training and validation curves to monitor model performance.

2. **Confusion Matrix** - A confusion matrix is generated to assess the model's accuracy and misclassifications.

## Prediction and Submission
1. **Predict and Submit Results** - We use the trained model to make predictions and submit the results.

## Results
We can see that when we use the unaugmented data, we get an accuracy of **98.64%**.
With the Data augmented set, we get an accuracy of **99.02%**.

<br>
Feel free to explore the code and experiment with the model for your own digit recognition tasks. If you have any questions or feedback, please don't hesitate to contact me.

Happy coding!

