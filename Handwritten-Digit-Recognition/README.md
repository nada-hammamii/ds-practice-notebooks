# Handwritten digit recognition

- **Goal:** classify handwritten digits (0–9).
- **Data:** MNIST, downloaded by `torchvision.datasets.MNIST` the first time the notebook runs.
- **Method:** a convolutional network written in PyTorch (`nn.Module` with `Conv2d` and `Linear` layers), trained with a standard loop and evaluated on the test set.

Notebook: [`handwritten-digit-recognition.ipynb`](handwritten-digit-recognition.ipynb)
