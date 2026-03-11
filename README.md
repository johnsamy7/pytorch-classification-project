# pytorch-classification-project

# Iris Flower Classification with PyTorch

This project implements a simple neural network using PyTorch to classify Iris flowers into three species.

## Dataset
The dataset used is the famous Iris dataset which contains 150 samples with 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The model predicts one of three classes:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

## Model Architecture

Feedforward Neural Network:

Input Layer: 4 features  
Hidden Layer 1: 8 neurons (ReLU)  
Hidden Layer 2: 9 neurons (ReLU)  
Output Layer: 3 neurons (Softmax via CrossEntropyLoss)

## Training

Loss Function:
CrossEntropyLoss

Optimizer:
Adam

Epochs:
100

## Training Loss

![Training Loss](images/training_loss (1).png)

## Example Prediction

```python
new_iris = torch.tensor([5.9,3.0,5.1,1.8])
