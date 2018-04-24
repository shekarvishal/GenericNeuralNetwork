# GenericNeuralNetwork
This is a generic neural network. It takes as input the following:
Hyper parameters: training rate, num_epochs
Parameters: #Layers, #units in each layer, the activation and diff activation funtion in each layer (limited to tanh, sigmopid, ReLU)
Saves the data into disk using pickle
SmartLoad: if training with same data file, and same hyper and parametera, then no need to train. loads the weights from the persisted store.
Driver funtion ot classify given the weights.
Also has option of training using TensorFlow framework and compare the weights learned by the Native and Tensorflow
dataset is the Cats vs non-cats.
