# IRIS-ANN
ANN on Iris Dataset


Dataset Description:
Design a Neural Network on IRIS dataset using Feed Forward Neural Network consisting of an input layer L0 consisting of m nodes for m features, two hidden layers L1 and L2 consisting of n and p nodes respectively, and an output layer L3 consisting of k nodes for k classes. Use Softmax Activation Function as Activation Parameter and Categorical Cross-Entropy Loss as Loss Function Design a ANN Model.

Expected Result:
1. A technical report containing implementation details
2. Final parameter values at the end of training
3. Train vs Test loss
4. Train and Test accuracy
5. F1-Score, Classification report & Confusion Matrix
6. Plot of the loss function vs. epochs

Architecture:

Input Layer: Relu Activation
1st Hidden Layer: Relu Activation
2nd Hidden Layer: Relu Activation
Output Layer: Softmax
loss: Categorical Cross Entropy
optimizer: Adam
metrics: accuracy
Number of Epochs: 200

a. This ANN consists here are of four layer first and last layer is input and output layer and having two layer in middle which is h1,h2.
b. The sequential model here will connect together a list of layers in order from first to last.
c. Using argument units we define how many output we want.Here Lo(Input)consists of 4 nodes,the two hidden layer consists of node n=15 & p=8 and an output consists of k=3 nodes.
d. Dense layers are connected by lines and planes so we need something non-linear which is called activation functions. 
e. After definig a model adding a loss function and optimizer with the model.compile method.


Output:
ANN Model was build with 
Train Accuracy:0.9850
Test Accuracy:0.97
Train Loss:0.0415
Test Loss:0.0860
