[vgg16]: https://github.com/Curt-Park/handwritten_digit_recognition/blob/master/vgg16.py
[mobilenet]: https://github.com/Curt-Park/handwritten_digit_recognition/blob/master/mobilenet.py
[resnet164]: https://github.com/Curt-Park/handwritten_digit_recognition/blob/master/resnet164.py
[wideresnet28-10]: https://github.com/Curt-Park/handwritten_digit_recognition/blob/master/wide_resnet_28_10.py

# KEKOxMNIST
Classification & generative models on MNIST, implemented by Keras.

## Classification models

Units: accuracy %

|Model|Validation|Test|Comment|
|:-:|:-:|:-:|:-|
|Simple MLP|0.0%|0.0%||
|Simple convnet|0.0%|0.0%||
|VGG-like convnet|0.0%|0.0%||
|[VGG16][vgg16]|99.61%|99.68%|Batch size: 64, epoch: 200, image standardization, data augmentation: rotating(15), width/height shift(0.1), shearing(0.2), zooming(0.1)|
|[Mobilenet][mobilenet]|99.63%|99.68%|Batch size: 64, epoch: 200, image standardization, data augmentation: rotating(15), width/height shift(0.1), shearing(0.2), zooming(0.1)|
|[Resnet164][resnet164]|99.72%|99.70%|Batch size: 128, epoch: 200, image standardization, data augmentation: rotating(15), width/height shift(0.1), shearing(0.2), zooming(0.1)|
|[WideResnet28-10][wideresnet28-10]|99.72%|99.76%|Batch size: 128, epoch: 200, image standardization, data augmentation: rotating(15), width/height shift(0.1), shearing(0.2), zooming(0.1)|

## Generative models

|Model|Sample|Comment|
|:-:|:-:|:-|
|GAN|||
|DCGAN|||
|cGAN|||
