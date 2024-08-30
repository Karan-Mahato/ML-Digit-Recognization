# ML-Digit-Recognization

# Aim
To develop a robust and efficient machine learning model capable of accurately recognizing and classifying handwritten digits from 0 to 9, leveraging advanced techniques in neural networks.

# Description
The ML-Digit-Recognition model is designed to interpret and classify handwritten digits with high accuracy. This model utilizes a artificial neural network (ANN) architecture, which is well-suited for image recognition tasks due to its ability to capture spatial hierarchies in images. The dataset used for training and testing the model is the MNIST dataset, a benchmark in the field of machine learning and computer vision.

## Key features of the model include:
libraies used : numpy, matplotlib, tensorflow<br>
MNIST data set is used ( imported using tensorflow )<br>
Total 60,000 images shape (60000,28,28)<br>
Split into test(10000) and train(50000)<br>

### Preprocessing:
Normalize pixel vales from 0-255 to 0-1

### Model:
Number of layers: 3<br>
layer 1(input layer): for flattening (28,28) matrix into a 1D array 784 nodes<br>
layer 2(hidden layer): 120 nodes AF: RELU  with a droupout of 20%<br>
layer 3(output layer): 10 nodes (0-1) AF: SOFTMAX<br>

optimizer : ADAM<br>
loss : SparseCategoricalCrossentropy<br>
Validation Split : 20%<br>
epochs : 100 <br>
batch_size : 1000 <br>
<br>
Accuracy : 98%%
Loss : 0.076


![Screenshot 2024-08-07 232121](https://github.com/user-attachments/assets/b5d1a895-3ccd-4c6e-8b9e-d72743dbf40e)


![image](https://github.com/user-attachments/assets/6dab2f78-7347-4c66-80e1-59a7bd26d10d)

