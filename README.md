# MNIST-GAN

This is a **Generative Adversial Network (GAN)** built using tensorflow.

This GAN uses the MNIST data to train it's generator and discriminator and, as a result, produce handwritten numbers similar to the data provided in the MNIST dataset.

The current implemenetation has been run for ***1000 epochs*** for a batch size of ***100 samples***. The results can be seen as under:

After 1st iteration:<br>
![Epoch 0](https://github.com/nsurampu/MNIST-GAN/blob/master/epoch0.png)

After 1000th iteration<br>
![Epoch 999](https://github.com/nsurampu/MNIST-GAN/blob/master/epoch999.png)

We can see that even after 1000 iterations, even though the noise has been reduced compared to the first iteration image, the image is still hazy. This, however, can be improved by running over more samples for more epochs than before.


**Credits:** GeeksforGeeks
