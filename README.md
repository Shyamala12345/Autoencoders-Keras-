# Autoencoders-Keras-


Based on the unsupervised neural network concept, Autoencoders is a kind of algorithm that accepts input data, performs compression of the data to convert it to latent-space representation, and finally attempts is to rebuild the input data with high precision.

Autoencoder Architecture
Autoencoder generally comprises of two major components:-

Encoder – This section takes the input data and then performs the compression of it for obtaining the data in latent-space.
Decoder – The decoder component follows the encoder in the architecture, it takes the output generated by the encoder and then tries to reconstruct the actual input

![image](https://user-images.githubusercontent.com/113771543/198082781-10d850b1-0077-4b36-a015-3a42ea422173.png)
In the above illustration, initially, a digit is provided as an input to the autoencoder. The encoder creates a smaller and compressed version of the input through the latent representation of the digit. Lastly, the operations of the decoder take place, whose aim is to produce copies of input by minimizing the mean squared error between the actual input (available as a dataset) and duplicate input (produced by the decoder).
