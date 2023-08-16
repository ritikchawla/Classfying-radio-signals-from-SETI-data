# Classify Radio Signals from Space with Keras

This project demonstrates how to classify radio signals from space using a Convolutional Neural Network (CNN) implemented with Keras. The goal is to classify radio signals into different categories such as "squiggle," "narrowband," "noise," and "narrowbanddrd."


## Prerequisites

Make sure you have Python and the necessary libraries installed. You can use a virtual environment or install the libraries globally:

```sh
pip install pandas numpy matplotlib tensorflow scikit-learn seaborn
```
## Notebook Sections

The project notebook is divided into several sections:

### Task 1: Import Libraries

Import the required libraries for data preprocessing, modeling, and evaluation.

### Task 2: Load and Preprocess SETI Data

Load and preprocess the SETI data for training and validation.

### Task 3: Plot 2D Spectrograms

Visualize 2D spectrograms of radio signals.

### Task 4: Create Training and Validation Data Generators

Create data generators for training and validation data to apply data augmentation.

### Task 5: Creating the CNN Model

Create the Convolutional Neural Network model using Keras. The model architecture includes convolutional layers, batch normalization, activation functions, max pooling, dropout, and fully connected layers.

### Task 6: Learning Rate Scheduling and Compile the Model

Implement a learning rate scheduler using ExponentialDecay and compile the CNN model with an optimizer and loss function.

### Task 7: Training the Model

Train the model using the data generators and callbacks. Monitor loss, accuracy, and save model weights.

### Task 8: Model Evaluation

Evaluate the model's performance on the validation data. Calculate classification metrics such as accuracy and create a confusion matrix to visualize the results.

## Usage

1.  Clone the repository:
   
    
    `git clone https://github.com/ritikchawla/radio-signal-classification.git
    cd radio-signal-classification` 
    
2.  Run the provided IPython Notebook file `radio_signal_classification.ipynb`.

## Thanks
I am passionate about exploring new technologies and creating exciting projects. If you have interesting project ideas and would like to collaborate, feel free to reach out to me via [email](mailto:chawlaritik@gmail.com).
