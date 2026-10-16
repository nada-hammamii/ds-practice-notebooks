# ASL recognition with deep learning

- **Goal:** classify images of American Sign Language letters (A, B, C).
- **Data:** labelled hand-sign images, one zip per letter (`A.zip`, `B.zip`, `C.zip`), loaded with `sign_language.py`.
- **Method:** a small convolutional network in Keras (Conv2D → MaxPooling → Dense), trained from scratch and evaluated on a held-out split.

Notebook: [`asl-recognition.ipynb`](asl-recognition.ipynb) · based on a DataCamp guided project.
