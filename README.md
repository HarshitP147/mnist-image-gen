# MNIST Imagen

This is the source for MNIST Imagen = a small scale diffusion model that generates single digits!! The model is trained using PyTorch and uses the [MNIST Dataset](https://en.wikipedia.org/wiki/MNIST_database).

The source code is implemented in available here. The model was trained locally on my laptop GPU - Nvidia GeForce RTX 3050 and took approximately 3 hours to fully train.

You can run `model.ipynb` file for training the entire model from scratch on your setup. Or you can simply download the weights and run the inference at `run.ipynb`. 


There are essentially two models whose weights you can download here:

1) [Classifier weights](https://drive.google.com/file/d/1r7TAbXATuaMQYiNeYl4-FOeG-r7cfaIp/view?usp=drive_link) : Weights for the numerical digit classifier.
2) [Diffusion weights](https://drive.google.com/file/d/1lbgzJZxAvxYKy41OloZpMEY0W4TJ3tdQ/view?usp=drive_link) : Weights for the diffusion model.

Enter a digit and watch the model generate the image of that digit in realtime🚀.