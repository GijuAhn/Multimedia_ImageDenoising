# SimpleDNCNN
## 2021 ConvNet Challenge in Multimedia & Lab Class  
PyTorch implementation of the TIP2017 paper  
[*Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising*](http://ieeexplore.ieee.org/document/7839189/).  
The author's [MATLAB implementation is here](https://github.com/cszn/DnCNN)  
DNCNN 논문의 아키텍처를 사용하였습니다.

# 참고사항
* 딥러닝 모델 아키텍처 및 학습 예시 배포를 위한 코드로, 성능을 높이기 위한 데이터 증가, 파라미터 조정 등의 설정은 전혀 하지 않았습니다.
* 학생들은 성능을 높이기 위한 아키텍처 변경, 데이터 증가, 파라미터 조정 등을 구현해야 합니다.
* 아래 training setting은 기본 학습을 위한 예시이며, 높은 성능을 보장하지 않습니다 (PSNR on test dataset: 22.11dB).
* 코드 내부에 있는 주석을 확인하여 본인의 상황에 맞는 파일 경로를 지정해야 합니다.

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

