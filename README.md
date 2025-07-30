# Building_a_Neural_Network

Simple Neural Network for MNIST Classification
This repository contains a simple neural network implemented in PyTorch for classifying handwritten digits in the MNIST dataset.

Features
A simple neural network with one hidden layer
Training and testing on the MNIST dataset
Accuracy evaluation on the test set
Requirements
PyTorch
Torchvision
Python 3.12.4
Usage
Clone the repository: git clone https://github.com/your-username/simple-nn-mnist.git
Install the required packages: pip install torch torchvision
Run the notebook: jupyter notebook simple_nn_mnist.ipynb
Model Architecture
The neural network consists of:

One input layer with 784 neurons (28x28 images)
One hidden layer with 128 neurons (ReLU activation)
One output layer with 10 neurons (softmax activation)
Training
The model is trained on the MNIST training set with a batch size of 100 and a learning rate of 0.001.

Evaluation
The model's accuracy is evaluated on the MNIST test set.

Results
The model achieves an accuracy of approximately 84.34% on the test set.

Saving the Model
The trained model can be saved to a file using torch.save(model.state_dict(), 'simple_nn_model.pth').

Contributing
Feel free to contribute to this repository by opening an issue or submitting a pull request.

License
This repository is licensed under the MIT License.
