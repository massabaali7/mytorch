# MyTorch Framework 

MyTorch is a custom PyTorch-inspired framework designed as part of the IDL course, allowing students to implement neural networks and deep learning components from scratch. This repository provides the foundational building blocks for learning and experimenting with the core principles behind frameworks like PyTorch.

## Repository Structure

```plaintext

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

    



