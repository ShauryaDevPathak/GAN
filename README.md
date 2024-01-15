# GAN
This repository contains code that I have used to make a Fashion GAN model by following a tutorial by Nicholas Renotte on Youtube.

## Libraries used:
1. tensorflow
2. tensorflow-gpu
3. numpy
4. matplotlib
5. keras
6. tensorflow_datasets

## Results:
![Graph of g_loss and d_loss](https://github.com/ShauryaDevPathak/GAN/blob/main/Images/output_graph.png?raw=true)

g_loss = The generator loss is calculated from the discriminator’s classification – generator gets rewarded if it successfully fools the discriminator, and gets penalized otherwise.
d_loss = It penalizes itself for misclassifying a real instance as fake, or a fake instance (created by the  generator) as real, by maximizing the below function.

![Resultant images generated by the generator](https://github.com/ShauryaDevPathak/GAN/blob/main/Images/result.png?raw=true)

I trained it for 20 epochs only, so don't judge :)
