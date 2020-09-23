## Adversarial Gradient Origin Network

Experiment to try and improve Gradient Origin Network image quality by putting it in an adversarial setting with a Discriminator network. After the first gradient update to find the latent code, the network is trained both on the
reconstruction error with respect to this latent code and the score of the discriminator simultaneoulsy, with a
bigger weightage given to the latter.

This is an extended/modified version of the code found [here](https://github.com/cwkx/GON) for GONs. Relativistic
Averaging Loss is used for the adversarial loss. 

![](https://github.com/krishnan-meep/GAN-Shenanigans/blob/master/images/samples_1.png)