# RNN_LSTM_from_scratch_numpy
Welcome to my implementation of a Recurrent Neural Network and a Long Short Term Memory with only numpy as a matrix operations tool. I really enjoyed working on this, you can even see how my functions usage is similar to Pytorch. Here are the implemented classes:

- **Linear**: A linear layer, which performs a weighted sum of its inputs.
- **CrossEntropy**: A cross-entropy loss function, which is commonly used for classification tasks.
- **SGD**: A stochastic gradient descent optimizer, which updates the weights of a neural network in order to minimize the loss function.
- **Adam**: An adaptive moment estimation optimizer, which is a more advanced optimizer than SGD and often performs better.
- **ReLu**: A rectified linear unit activation function, which outputs the maximum of its input and zero.
- **Embedding**: An embedding layer, which converts one-hot encoded inputs into dense vectors.
- **RNN**: A recurrent neural network layer, which takes a sequence of inputs and produces a sequence of outputs.
- **Gate**: The gates of an LSTM cell, which control the flow of information through the cell.
- **LSTM**: An LSTM cell, which is a type of RNN cell that is well-suited for learning long-term dependencies in sequential data.

The optimizers also include a weight decay parameter, a momentum parameter, and a nesterov momentum parameter. The model was trained and evaluated on PTB dataset on CPU. To test the correctness of the implementation, I evaluated the same architecture and parameters with pytorch on GPU. Both my own and Pytorch's RNN failed to learn effectively. While Pytorch implementation stayed on track, my model became worse after a few steps. As for LSTM, my implementation evaluation loss went down to 7.5 after 150 steps, while Pytorch model went down to 6.

This project was only meant to be an exercise for me and I do not intend to further update it. You are welcome to get inspiration from it.
