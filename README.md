# Physics Informed Neural Networks (PINNs) with TensorFlow

## Introduction
Physics Informed Neural Networks (PINNs) are a type of neural network that incorporates physical laws, often expressed as partial differential equations (PDEs), into the learning process. This allows the network to leverage both data and known physical principles to improve its predictions and generalization capabilities. This repository provides an implementation of PINNs using TensorFlow.

## Architecture Diagram

The architecture of a typical PINN can be visualized as follows:
Input Layer (Time and Spatial Coordinates) --> Hidden Layers (Fully Connected) --> Output Layer (Solution of PDE)

Each hidden layer consists of neurons with activation functions. The network is trained to minimize the loss function that includes both data loss and physics loss.

## Installation

To use this implementation, you need to have TensorFlow installed. You can install it using pip:

```bash
pip install tensorflow
```



## Star the Repository

If you find this project useful or interesting, please consider starring the repository on GitHub!

[![Star this repository](https://img.shields.io/github/stars/bsshreesha/Physics_Informed_Neural_Network.svg?style=social)](https://github.com/bsshreesha/Physics_Informed_Neural_Network/)
