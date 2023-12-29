I quick project using GANs on the MNIST dataset.

I implemented the generator and discriminator with modifications to the DCGAN tutorial. I chose to use nn.LeakyReLU as the activation function in the generator and fewer layers in both models. This is so that I can train the model with more epochs in a reasonable time. The training was able to finish completing significantly faster, with reasonable results. I also ran the DCGAN tutorial implementation with 100 epochs to compare the results. The more complex layers of the generator and discriminator model proved to be more beneficial than more epochs in training.

My implementation:

<img src="https://github.com/KiwiThePoodle/Generative-Adversarial-Networks-on-MNIST/blob/main/generated_samples.png">

DCGAN:

<img src="https://github.com/KiwiThePoodle/Generative-Adversarial-Networks-on-MNIST/blob/main/generated_samples_DCGAN.png">
