# Example of replacing MLP with KAN in autoencoder(AE) and variational autoencoder(VAE)
This is an implementation that uses KAN instead of MLP in both autoencoder and variational autoencoder, 
the experimental dataset is MNIST, and the same network architecture and training parameters are constructed on CPU. 
After experimentation, it is observed that KAN achieves the same results as MLP in both autoencoder and variational autoencoder,
but the training time is much longer, for 5 epochs on CPU, the training time for variational autoencoder using MLP is 192 seconds, 
while the training time for variational autoencoder using KAN is 1117 seconds.
