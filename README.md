# Keras와 OpenCV를 이용한 이미지 분류
구글 Teachable Machine의 사전 학습된 AI 모델을 사용하여 제작한 '이미지 분류 프로그램'입니다. <br>
정의한 클래스는 'Car', 'Person', 'Dog', 'Plant'로 4개입니다. 

※ 프로그램 실행 파일은 'image_classification.py' 입니다.

## Tensorflow란?

![tensorflow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

Tensorflow는 구글이 개발한 오픈소스 머신러닝 프레임워크이다. 그래프 기반의 연산을 사용하여 병렬 처리 및 분산 컴퓨팅을 지원하며, 다양한 플랫폼에서 실행될 수 있다. 딥러닝 모델의 구축 및 훈련을 단순화하기 위한 다양한 고수준 API도 제공한다. Tensorflow를 사용하면, 대규모의 수치 데이터를 처리하고, 딥러닝 모델을 구축하고 훈련시키며, 이를 배포하고 실행할 수 있다. 
- Tensorflow Hub model
- Tensorflow.js model
- TF-Serving model
- Tensorflow Extended(TFX)
- Tensorflow Lite model

### Keras는?
Keras는 딥러닝 모델을 쉽게 구축하고 훈련시킬 수 있는 고수준 신경망 API이다. 사용자가 간단하게 딥러닝 모델을 정의하고 훈련시킬 수 있도록 고수준의 추상화를 제공한다. 이는 딥러닝 모델을 구성하는 데 필요한 많은 세부 사항들을 숨겨주므로, 초보자부터 전문가까지 다양한 사용자들이 쉽게 사용할 수 있다는 장점이 된다. 

Keras.h5 ▷ tensorflow용 가중치 파일

### OpenCV는?
OpenCV는 컴퓨터 비전 작업을 위한 오픈소스 라이브러리로, 이미지 및 비디오 처리, 객체 검출, 특징 추출, 영상 분할, 카메라 캘리브레이션 등 다양한 기능을 제공한다. 해당 프로젝트에서는 웹캡으로 이미지를 받아 처리하는데 사용했다.  
