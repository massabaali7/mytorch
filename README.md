# MyTorch Framework 

MyTorch is a custom PyTorch-inspired framework designed as part of the IDL course, allowing students to implement neural networks and deep learning components from scratch. This repository provides the foundational building blocks for learning and experimenting with the core principles behind frameworks like PyTorch.


mytorch/ │ ├── mytorch/ # Your main library │ ├── nn/ # Neural network modules and layers │ ├── optim/ # Optimizers │ ├── flatten # Flatten layer implementation │ ├── gru_cell # Gated Recurrent Unit (GRU) cell │ ├── rnn_cell # Recurrent Neural Network (RNN) cell │ └── utils # Utility functions │ ├── models/ # Templates for constructing models using the MyTorch framework
│ ├── mlp # Multi-Layer Perceptron model │ ├── mlp_scan # MLP with scanning architecture │ ├── cnn # Convolutional Neural Network model │ ├── rnn_classifier # RNN-based classifier │ └── char_predictor # Character prediction model │ ├── CTC/ # Connectionist Temporal Classification (CTC) utilities │ ├── CTC # CTC loss implementation │ └── CTCDecoding # CTC decoding logic │ ├── toy_example/ # Contains runnable examples │ └── mlp_example # MLP example implementation │ └── testing/ # Includes unit tests and scripts to verify the correctness and performance of various components in the framework

yaml
Copy code


## Repository Structure
mytorch/
│
├── mytorch/              # Your main library
│   ├── nn/
│   ├── optim/
│   ├── flatten
│   ├── gru_cell
│   ├── rnn_cell
│   └── utils
│
├── models/              # templates for constructing models using the mytorch framework           
│   ├── mlp
│   ├── mlp_scan
│   ├── cnn
│   ├── rnn_classifier
│   └── char_predictor
├── CTC/              
│   ├── CTC
│   └── CTCDecoding
├── toy_example/              # Contains runnable examples
│   └── mlp_example
└── testing/              # Includes unit tests and scripts to verify the correctness and performance of various components in the framework

    



