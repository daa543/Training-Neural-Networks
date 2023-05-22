# Training-Neural-Networks

### Introduction
In this assignment, you will build a neural network from scratch using PyTorch and train it on the MNIST dataset for handwritten digit recognition. You will also add dropout and regularization layers to improve the model’s performance. Finally, you will hyper-tune the optimizer type, learning rate, and batch size to achieve the best possible results.

### Step 1
Download the MNIST dataset from kaggel and apply any preprocessing needed on the data. Split the data randomly into being 80% training set and 20% validation set.

### Step 2
Build a neural network architecture from scratch using PyTorch. The network should have at least two hidden layers and should use ReLU activation function between hidden layers. You can change the number of hidden layers, number of perceptrons in each layer based on your own preferences.

Train the model using:

• Optimizer: Adam

• Learning rate : 0.01

• Loss Function: Cross Entropy

Plot the following

• Training / Validation Loss.

• Training / Validation Accuracy.

### Step 3
Add Dropout and Layer Normalization layers to your model’s architecture. Retrain the model and compare the following plot.

• Train / Validation loss.

• Train / Validation Accuracy.

Report what happened to the model performance and why, based on the number of layers (Dropout / Layer Normalization) you added and the value of Dropout.

### Step 4
Train 3 more model based on the model architecture you chose in step 3. For each model you will change the following:

• Learning Rate (0.001, 0.0005, 0.0001).

• Probability of Dropout. (0.2, 0.4, 0.6).

Report same plots and comparisons requested in step 3.
