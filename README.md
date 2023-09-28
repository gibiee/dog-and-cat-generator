Stable Diffusion의 공개 이후, diffusion 모델이 굉장히 많이 발표되는 것 같다.  
유저가 만들고 싶은 이미지에 대한 설명을 text prompt로 활용하여 유저의 의도를 전달해줄 수 있다는 것이 diffusion 모델의 가장 큰 강점이라고 생각한다.  
**그렇다면...*의도를 전달해줄 수 있다*는 부분을 제외한 이미지 생성 성능 자체는 어떨까?**  
라는 의문으로 시작한 toy project 입니다.  

<p align='center'>
  <img src="https://github.com/gibiee/dog-and-cat-generator/assets/37574274/b5199826-5f65-44cb-b1b4-f7d27db142a4" width=80% />
  <br/>
  <i>"GAN vs Diffusion" 프롬프트를 stable-diffusion-xl-base-1.0 모델에 입력한 결과...심연을 의미하는 걸까?</i>
</p>

## 목차

1. [개요](#개요)
2. [데이터셋 준비](#데이터셋-준비)
4. [GAN 모델 학습](#gan-모델-학습)
5. [GAN 모델 추론](#gan-모델-추론)
6. [Diffusion 모델 학습](#diffusion-모델-학습)
7. [Diffusion 모델 추론](#diffusion-모델-추론)
8. [결과 비교](#결과-비교)
9. [결론](#결론)


## 개요
단일 모델으로 개와 고양이를 conditional하게 생성할 수 있도록 학습을 진행할 예정입니다.


## 데이터셋 준비


## GAN 모델 학습
Base Model : [StyleGAN2-ADA](https://github.com/NVlabs/stylegan2-ada-pytorch)  


## GAN 모델 추론


## Diffusion 모델 학습
Base Model : [Latent Diffusion](https://github.com/CompVis/latent-diffusion)  
autoencoder 모듈은 ImageNet 데이터셋으로 pretrained된 것과 커스텀 학습 시킨 것...이렇게 2가지 버전으로 각각 테스트해봐야할 것 같다.  


## Diffusion 모델 추론


## 결과 비교


## 결론

