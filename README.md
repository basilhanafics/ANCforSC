# ANCforSC
Adversarial Neural Cryptography based Smart Contracts
Neural Cryptography with PyTorch
This repository contains a PyTorch implementation of a neural network-based cryptographic system inspired by adversarial learning. The setup involves Alice, Bob, and Eve, where Alice and Bob attempt to securely communicate while Eve tries to intercept the message.

Features
Uses PyTorch for training neural networks.
Implements AliceBobNet for encryption/decryption.
Includes EveNet, which acts as an adversary trying to decrypt the message.
Simulates secure communication using neural cryptography.

Setup & Installation
Prerequisites
Ensure you have the following dependencies installed:

Python (>=3.7)
PyTorch
Matplotlib

You can install them using:
pip install torch matplotlib

Usage
Run the Jupyter Notebook to train and test the model:

jupyter notebook PSC3.ipynb

The notebook includes:

Model definitions for Alice, Bob, and Eve.
Training loop for adversarial learning.
Performance visualization using matplotlib.

Results
The training process attempts to:

Enable Alice and Bob to develop a secure encryption scheme.
Prevent Eve from successfully decrypting the message.

Future Improvements
Extend to variable-length messages.
Introduce different encryption techniques.
Improve Eve’s attack strategies.

License
This project is open-source under the MIT License.

