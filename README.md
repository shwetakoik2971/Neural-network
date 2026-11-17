# Experiment - Fashion MNIST Image Classification (Neural Network)

## Aim

To implement a Neural Network using TensorFlow / Keras to classify Fashion MNIST images into 10 clothing categories.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Google Colab
- Neural Network

## Dataset

Fashion MNIST Dataset (`tf.keras.datasets.fashion_mnist`)

The dataset contains 70000 images and 10 classes:
- T-shirt
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle Boot

Each image is 28 x 28 grayscale image.
- Training Set: 60000 images
- Testing Set: 10000 images

## Procedure
1. Import the required Python libraries.
2. Load the Fashion MNIST dataset using TensorFlow.
3. Display the Fashion MNIST images.
4. Display 10 sample images with their class names.
5. Normalize the images by dividing by 255.0.
6. Display a normalized image.
7. Check pixel values before and after normalization.
8. Convert one image to a Pandas DataFrame and display it.
9. Create a Neural Network model using Keras Sequential.
10. Add Flatten layer with input shape (28, 28).
11. Add Dense layer with 128 neurons and relu activation.
12. Add Dense layer with 10 neurons and softmax activation.
13. Display the model summary.
14. Compile the model with adam optimizer and sparse_categorical_crossentropy loss.
15. Train the model for 5 epochs.
16. Evaluate the model on test data and display accuracy.
17. Predict the class of a test image.
18. Display the predicted image and compare Predicted vs Actual class.
