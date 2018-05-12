LSTM Autoencoder and LSTM Future Predictor in Tensorflow.
===
This is a simple implementation based on this paper : https://arxiv.org/abs/1502.04681

Requirement
---
1. Tensorflow 1.4.0
2. Python 3.5.4
3. Python packages : numpy, matplotlib, os, argparse, scipy

Usage
---
* Data generation using rotation and shift : Image_generation.ipynb
* Reconstruct data using LSTM autoencoder : Autoencoder.ipynb
* Input Reconstruction and Future Prediction : AE_with_Predictor

Results
---
From Composite Model

Data sequence(left to right) : 0,1,...,t-1,t
### Rotated Data
After entering sequence data in LSTM model, reconstruct the data and predict how much rotate

Input Sequence

![input](/image/rotated_input_sequence.PNG)

Input Reconstruction

![recon](/image/rotated_reconstruction.PNG)

Input Future Prediction 

![pred](/image/rotated_prediction.PNG)


### Shifted Data
After entering sequence data in LSTM model, reconstruct the data and predict how much shift


Input Sequence

![input](/image/shifted_input_sequence.PNG)

Input Reconstruction

![recon](/image/shifted_reconstruction.PNG)

Input Future Prediction 

![pred](/image/shifted_prediction.PNG)


Reference Implementations
---
+ https://github.com/iwyoo/LSTM-autoencoder
+ https://github.com/peytonhong/LSTMAutoencoder