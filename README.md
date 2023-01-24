# Generative-Adversarial-Networks
(22/07 ~ 23/02) 광운대학교 산학연계 프로젝트

## Introduction
Apply Generative Adversarial Nets to generating leak data.

## 주요 기능
1. 리크 데이터 생성
>* GAN 모델로 랜덤 생성

2. 불량 이미지 생성
>* 생성 위치 랜덤 지정
>* 생성 위치 사용자 지정
>* 여러개 리크 생성

3. 불량 이미지 다운로드

## 서비스 화면

### 메인 화면

![메인화면](https://user-images.githubusercontent.com/49435654/214221161-7d22fda2-fc1e-437f-8203-15548903a60d.png)

### 사용자 설정 화면

### 불량 이미지 생성 화면

## 시스템 구성 및 아키텍쳐

### Back-End & Front-End

### Modeling
> 1. Pre-processing
> 
> 2. Modeling
>> [DCGAN](https://arxiv.org/pdf/1511.06434.pdf)
>> ![DCGAN 구조](https://user-images.githubusercontent.com/49435654/214224661-3dd07006-e5b6-425b-a638-c69c3dba77d1.PNG)


> 3. Generate Defective Image

## Requirements:
* Python 3.9.5
* OpenCV 4.6.0
* Pytorch 1.12.1

## Prerequistes

node.js & npm

## checkout, build & run

```
1. git clone
2. npm install 
4. npm run start
```

## Team (사미용두)
* [김대현](https://github.com/DevDae)
* [김재윤](https://github.com/kimjaeyoonn)
* [김태영](https://github.com/kty4119)
* [손재성](https://github.com/noseaj)
* [장효영](https://github.com/HyoYoung22)
