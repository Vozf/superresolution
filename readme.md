# Super resolution model using PyTorch
#### Model converts images from 72x72 to 256x256
Dataset used is 2GB part of Imagenet.\
Model is trained first on pixel loss and then using perceptual loss from Vgg16(relu layers before batchnorm) also [icnr](https://arxiv.org/ftp/arxiv/papers/1707/1707.02937.pdf) initialization for PixelShuffle layers is used to prevent checkerboard atifacts

Here are some examples ([hi-res](https://vk.com/doc98389977_480295729)):
![](https://pp.userapi.com/c848524/v848524226/a9bff/3WLCPpj8SQg.jpg)

