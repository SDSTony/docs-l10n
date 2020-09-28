# 전이 학습이란 무엇입니까?

정교한 딥 러닝 모델에는 수백만 개의 매개변수(가중치)가 있으며 이를 처음부터 훈련하려면 종종 많은 양의 컴퓨팅 리소스 데이터가 필요합니다. 전이 학습은 관련 작업에 대해 이미 훈련된 모델의 일부를 가져와 새 모델에서 재사용함으로써 손쉽게 데이터를 구축하는 기술입니다.

예를 들어, 이 섹션의 다음 튜토리얼에서는 이미지 내에서 수천 가지의 다양한 객체를 인식하도록 이미 훈련된 모델을 활용하여 고유한 이미지 인식기를 구축하는 방법을 보여줍니다. 사전에 훈련된 모델의 기존 지식을 조정함으로 필요한 원래 모델보다 훨씬 적은 훈련 데이터를 사용하여 자체 이미지 클래스를 감지할 수 있습니다.

이 방법은 새 모델을 신속하게 개발하고 브라우저 및 모바일 장치와 같이 리소스가 제한된 환경에서 모델을 사용자 정의하는 데 유용합니다.

대부분은 전이 학습을 할 때 원래 모델의 가중치를 조정하지 않습니다. 대신 최종 레이어를 제거하고 잘린 모델의 출력 위에 새로운(종종 상당히 얕은) 모델을 훈련합니다. 이러한 기술은 해당 섹션 튜토리얼에 잘 나타나 있습니다.

- [전이 학습 기반 이미지 분류자 빌드하기](image_classification)
- [전이 학습 기반 오디오 인식기 빌드하기](audio_recognizer)