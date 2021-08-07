# Dacon_Credit Project
카메라 이미지 품질 향상 AI 경진대회 \

# 빛 번짐으로 저하된 📷카메라 이미지 품질을 향상시키는 AI 모델 개발
## 평가산식(PSNR)
* Filter를 통해 빛 번짐 현상이 나타나는 영상을 원상태로 Reconstruction하는 모델 개발
* 평가지표는 PSNR : 원본과 빛 번짐 영상간의 잡음 비율(차이) 계산
## 모델
* UNet - Backbone(ResNet101-V2) => LossFuuction 재구성
* Unet++ - No Backbone
* Unet++은 논문에서 소개하길 Decoder에서 출력된 Feature map과 Encoder에서 보내지는 Feature map이 semantically simillar할 때 최적화하기 쉬울 것이라고 말함.
* 즉, Pyramid Level이 높을수록 Unet보다 Unet++의 성능이 높을 것이라고 봄
* 
# Loss
## 
* 사용자의 신용카드 대금 연체를 기준으로 한 신용도

# Acknowledgements

https://dacon.io/competitions/official/235746/overview/description
