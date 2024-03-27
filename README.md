# Sign Language Recognition

## About the Data

The Sign Language MNIST dataset is presented here as an alternative to the traditional MNIST dataset, with the goal of providing a more challenging task for computer vision applications. Instead of handwritten digits, this dataset contains images of American Sign Language letters, representing a multi-class problem with 24 classes.

## Dependencies

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- keras
- tensorflow
- opencv-python
- mediapipe

You can install these dependencies using pip:

## Usage

1. Make sure you have all dependencies installed.
2. Download the Sign Language MNIST dataset and save it in a directory named `Dataset`.
3. Run the provided Python script `sign_language_recognition.py`.
4. The script will train a Convolutional Neural Network (CNN) model on the dataset and save the trained model as `smnist4.h5`.
5. Once the model is trained, the script will open your webcam and start real-time sign language recognition.
6. Place your hand gesture in front of the webcam and press the spacebar to capture the gesture.
7. The script will analyze the captured gesture and display the predicted letter along with confidence levels.
8. Press the Escape key to exit the program.

## Acknowledgements

- This script is based on the Sign Language MNIST dataset and utilizes the Mediapipe library for hand detection and OpenCV for webcam access.
- The CNN model architecture used in this script is adapted for sign language recognition.

