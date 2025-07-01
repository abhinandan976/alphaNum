## Alphanumeric Character Recognition using CNN
This project involves the recognition of grayscale images of handwritten characters, numerals, and special characters, each with a resolution of 24x24 pixels. The main goal of the project is to classify the images into their respective categories using a Convolutional Neural Network (CNN) model.

## Project Overview
The dataset contains grayscale images representing:

Handwritten letters (A-Z)
Numerals (0-9)
Special characters
Each image is of size 24x24 pixels and is labeled according to the character it represents. The CNN model is trained to recognize and classify these images into their respective classes.

## Features
Input: Grayscale images of size 24x24 pixels.
Output: Predicted class (letter, numeral, or special character).
Model: Convolutional Neural Network (CNN) designed to capture spatial features in the image for accurate classification.
Steps Involved
Preprocessing: Images were normalized to improve model accuracy.
Model Architecture: A CNN was built to extract features from the images and classify them into their respective classes.
Training: The model was trained using the dataset of handwritten characters, numerals, and special characters.
Evaluation: Model performance was evaluated using accuracy and loss metrics on the test set.
