# Graph Convolutional Recurrent Neural Networks (GCRNN)

The code in this repository implements sequence modeling on graph structured dataset.
Example code runs with [Penn TreeBank dataset](http://aclweb.org/anthology/J93-2004) to predict next character, give sequence of sentence. The dataset can be downloaded from [here](https://github.com/carpedm20/RCMN/tree/master/data/ptb)
The core part of the code is presented in our paper:

Youngjoo Seo, Michaël Defferrard, Xavier Bresson, Pierre Vandergheynst, [Structured Sequence Modeling With Graph Convolutional Recurrent Networks][arXiv](https://arxiv.org/pdf/1612.07659.pdf)

The code is released under the terms of the [MIT license](LICENSE.txt). Please
cite the above paper if you use it.

## Environment
1. Tensorflow version 1.2
2. python 2.7
And we use graph convolutional filter based on ["Spectral Graph Convolutional Neural Network"](https://github.com/mdeff/cnn_graph)

## Installation and running

1. Clone this repository.
   ```sh
   git clone https://github.com/youngjoo-epfl/gconvRNN
   cd gconvRNN
   ```

2. Install the dependencies. The code should run with TensorFlow 1.0 and newer.
   ```sh
   pip install -r requirements.txt  # or make install
   ```

3. Run main with python.
   ```sh
   python gcrn_main.py
   ```


## Model configurations
You can see "config.py" to change the parameters for learning the model.
