# ML-Digit-Recognization
ML model for digit recognization 

MNIST data set is used ( imported using tensorflow )<br>
Total 60,000 images shape (60000,28,28)<br>
Split into test(10000) and train(50000)<br>

### Preprocessing:
Normalize pixel vales from 0-255 to 0-1

### Model:
Number of layers: 3<br>
layer 1(input layer): for flattening (28,28) matrix into a 1D array 784 nodes<br>
layer 2(hidden layer): 128 nodes AF: RELU<br>
layer 3(output layer): 10 nodes (0-1) AF: SOFTMAX<br>

optimizer : ADAM<br>
loss : SparseCategoricalCrossentropy<br>
Validation Split : 25%<br>
epochs : 60 (Over 60 model get Overfit)<br>
<br>
Accuracy : 97.4%
