#Brain Tumor Detection with CNN

This project uses a **Convolutional Neural Network (CNN)** to classify brain MRI images as either containing a **tumor** or being **healthy**.

#Objective

The main goal of this model is to predict whether a brain image shows signs of a **cancerous tumor** or is healthy using deep learning techniques.

# Tools 

- Python
- TensorFlow / Keras 
- ImageDataGenerator (for image preprocessing)
- Matplotlib (for visualization)

#Dataset

The brain image dataset was obtained from Kaggle:
[Brain Tumor Classification with Simple CNN](https://www.kaggle.com/boneacrabonjac/brain-tumor-classification-with-simple-cnn)

It contains two classes:
- Brain Tumor
- Healthy

#Model Architecture

The CNN model consists of:

- 3 Convolutional layers (with ReLU activation)
- MaxPooling layers after each convolution
- 2 Dense layers
- Dropout layer (to prevent overfitting)
- Sigmoid activation in the output layer (for binary classification)

#Evaluation

The model was also tested with images from a **different dataset**, including new examples of both tumor and healthy brains. The model performed well and was able to generalize beyond the original training data.

# Test the Model Yourself

We have included two example brain images in this repository so you can try the model out yourself
