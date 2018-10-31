# Super resolution model using PyTorch
#### Model converts images from 72x72 to 256x256
Model is trained first on pixel loss and then using perceptual loss from Vgg16(relu layers before batchnorm) also [icnr](https://arxiv.org/ftp/arxiv/papers/1707/1707.02937.pdf) initialization for PixelShuffle layers is used to prevent checkerboard atifacts

Here are some examples ([hi-res](https://psv4.userapi.com/c848036/u98389977/docs/d14/482455c54b26/1.png?extra=_g9nOJrHpoyDRUd0L3bQGjNVqPqu4LmQLS3NrDDtwthZ5j4j_VZZuUiOWS2TCcM-IlyOjR67G8PidhfmsPNndq2EEyB9LulIHqqdH18DVAOjegwwQQyYtVUxXqRGJR8RX9nudPdExjoFmKsGfoD9)):
![](https://psv4.userapi.com/c848036/u98389977/docs/d14/482455c54b26/1.png?extra=_g9nOJrHpoyDRUd0L3bQGjNVqPqu4LmQLS3NrDDtwthZ5j4j_VZZuUiOWS2TCcM-IlyOjR67G8PidhfmsPNndq2EEyB9LulIHqqdH18DVAOjegwwQQyYtVUxXqRGJR8RX9nudPdExjoFmKsGfoD9)

