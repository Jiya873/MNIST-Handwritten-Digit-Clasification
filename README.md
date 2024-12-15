# MNIST-Handwritten-Digit-Clasification
This project demonstrates the implementation of a neural network for classifying handwritten digits from the MNIST dataset using TensorFlow and Keras

## Dependencies
* Python 3.12.5
* NumPy
* Matplotlib
* Seaborn
* OpenCV
* PIL
* TensorFlow
* Keras

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   cd <repository-directory>
   ```
2. Install the required packages
3. Run the cells sequentially to execute the code

## Notebook Overview
1. Importing Dependencies:
* Import necessary libraries such as NumPy, Matplotlib, Seaborn, OpenCV, PIL, TensorFlow, and Keras
2. Loading the MNIST Dataset:
* Load the MNIST dataset using Keras' built-in dataset loader
3. Data Preprocessing:
* Normalize the pixel values of the images to the range [0, 1]
* Reshape the data as required by the neural network
4. Building the Neural Network:
* Define a sequential model with layers including Flatten, Dense, and Activation layers
5. Compiling the Model:
* Compile the model using the Adam optimizer and sparse categorical cross-entropy loss function
6. Training the Model:
* Train the model on the training data for a specified number of epochs
7. Evaluating the Model:
* Evaluate the model's performance on the test data
* Display the accuracy and loss
8. Making Predictions:
* Use the trained model to make predictions on the test data
* Convert prediction probabilities to class labels
9. Visualizing Results:
* Display sample images from the test set along with their predicted and true labels.
* Plot the confusion matrix to visualize the model's performance

**The model achieves a high accuracy on both the training and test datasets**

