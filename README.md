# Implementing-A-Deep-Dense-Variant-AutoEncoders-VAE-for-reconstructing-the-images-of-the-MNIST-data
Modify the encoded data by two different methods with different values as below and trace the effect of such modification.


z_zz = encoder.predict(x_train)

Method 1: x_decoded = decoder.predict(z_zz[2]+Val1)   try different values for Val1 and figure-out the effect

Method 2: x_decoded = decoder.predict(z_zz[0]+z_zz[1] * Val2)    try different values for Val2 and figure-out the effect

A deeper network is required. The encoder and decoder should include more layers.
Try different latent dimensions and figure-out the effec
