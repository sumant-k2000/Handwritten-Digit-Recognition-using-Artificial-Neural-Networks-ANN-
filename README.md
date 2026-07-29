# Handwritten Digit Recognition using Artificial Neural Networks (ANN)

## Objective

The objective of this project is to develop an Artificial Neural Network (ANN) that can recognize handwritten digits (0–9) using the MNIST Handwritten Digits dataset. The model is trained to classify images accurately and evaluate its performance using standard classification metrics.

---

## Dataset Link

MNIST Handwritten Digits Dataset

https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- TensorFlow
- Keras
- Scikit-learn

---

## Methodology

1. Loaded the MNIST dataset using Pandas.
2. Displayed the first five records.
3. Identified the input features and target variable.
4. Displayed dataset dimensions and summary information.
5. Visualized a sample handwritten digit using Matplotlib.
6. Checked for missing values.
7. Separated input features and target labels.
8. Normalized pixel values to the range 0–1.
9. Split the dataset into training and testing sets (80:20).
10. Converted target labels into categorical format using One-Hot Encoding.
11. Built an ANN with two hidden layers (128 and 64 neurons) using ReLU activation.
12. Used a Softmax output layer with 10 neurons for digit classification.
13. Compiled the model using the Adam optimizer and Categorical Crossentropy loss function.
14. Trained the model for 10 epochs.
15. Evaluated the model using test accuracy, confusion matrix, and classification report.
16. Plotted Accuracy vs Epoch and Loss vs Epoch graphs.

---

## Results

- The ANN achieved high classification accuracy on the MNIST test dataset.
- The confusion matrix showed that most handwritten digits were classified correctly.
- The accuracy increased while the loss decreased over successive training epochs.
- The model effectively recognized handwritten digits from 0 to 9.

---

## Conclusion

The ANN model successfully recognized handwritten digits with high accuracy by learning complex patterns from image pixels. Hidden layers played a significant role in improving classification performance by extracting meaningful features. Deep Learning proved effective for image recognition tasks, although ANN models require large datasets and computational resources for training.
