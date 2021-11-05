# SimpleDNCNN
## 2021 ConvNet Challenge in Multimedia & Lab Class  
PyTorch implementation of the TIP2017 paper  
[*Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising*](http://ieeexplore.ieee.org/document/7839189/).  
The author's [MATLAB implementation is here](https://github.com/cszn/DnCNN)  
DNCNN 논문의 아키텍처를 사용하였습니다.

# Training Setting
* Noise level: 25
* num_of_layers: 17
* Image resolution: 128 x 128
* MSE Loss
* Adam optimizer (lr=0.0001, eps=1e-08)
* 30 epochs on training

# Options
* Tensorboard available
* PSNR checking while training  
