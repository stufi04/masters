High Level Project Overview


Abstract

Capsule endoscopy is a non-invasive medical procedure used to record images of the gastrointestinal tract. While this method is a better alternative for patients, it presents a difficulty to doctors who need to go over as much as 50000 images. Scientists are developing machine learning algorithms that will automatically throw away images free of any anomalies. Like other medical applications, however, available data to train such models is sparse. Therefore, we attempt to create synthetic images that can be used as substitution. For the purpose we have used generative adversarial networks (GANs) as they have recently shown great promise for problems like this one. Training a classifier on both the real and synthetic data, we achieve an increase in the classification accuracy for a dataset of intestine images.


Repository

All code can be found at:
https://github.com/stufi04/masters

The repo holds the following notebooks:
gan_fashion_mnist.ipynb
wgan_fashion_mnist.ipynb
cgan_fashion_mnist.ipynb
wgan.ipynb
wgan-gp.ipynb
eval.ipynb

They contain all the models implemented as explained in the report, as well as some further experimentation (tests, assessment etc). Two files with the weights of the final model can also be found in the repository. Finally, I have put a folder ‘images’ with some examples of generated images for different resolutions.


Note to the reader

As this project is developed with a private company, unfortunately we cannot upload the dataset that we worked with.
