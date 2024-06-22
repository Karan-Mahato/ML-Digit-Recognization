# ML-Digit-Recognization
ML model for digit recognization 

MNIST data set is used ( imported using tensorflow )
Total 60,000 images shape (60000,28,28)
Split into test(10000) and train(50000)

##Preprocessing:
Normalize pixel vales from 0-255 to 0-1

###Model:
Number of layers: 3
layer 1(input layer): for flattening (28,28) matrix into a 1D array 784 nodes
layer 2(hidden layer): 128 nodes AF: RELU
layer 3(output layer): 10 nodes (0-1) AF: SOFTMAX

optimizer : ADAM
loss : SparseCategoricalCrossentropy
Validation Split : 25%
epochs : 60 (Over 60 model get Overfit)

Accuracy : 98%
