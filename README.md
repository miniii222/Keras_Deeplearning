# Keras_deeplearning
케라스 창시자에게 배우는 딥러닝

딥러닝을 다시 공부해보려고 한다...


# Part1. The Fundamentals of Deep Learning
## CH1. What is Deep Learning?
## CH2. The Mathematical Blocks of Neural Networks [link](https://github.com/miniii222/Keras_Deeplearning/tree/master/CH2.Mathematical_neural_net)

##### SGD Stochastic Gradient Descent (확률적 경사 하강법)
1. 훈련 샘플 배치 x와 이에 상응하는 타깃y 추출
2. x로 네트워크를 실행하고 예측 y_pred
3. 이 배치에서 y_pred와 y 사이의 오차를 측정하여 네트워크의 손실 계싼
4. 네트워크의 파라미터에 대한 손실 함수의 그래디언트 계싼
5. 그래디언트의 반대 방향으로 파라미터 이동

- 확률적 : 각 배치 데이터가 무작위로 선택.(mini batch)


## CH3. Getting Started with Neural networks [link](https://github.com/miniii222/Keras_Deeplearning/tree/master/CH3.Getting_Started)
- N개의 클래스로 분류하려면, 마지막 Dense 층은 N
- 단일 레이블, 다중 분류 문제에서는 N개의 클래스에 대한 확률 분포를 출력하기 위해 `softmax` 함수 사용
- label -> one-hot encoding : categorical_crossentropy
- lael -> 정수형 : sparse_categorical_crossentropy
- 많은 수의 클라스로 분류할 때, 중간층의 크기가 너무 작아 네트워크에 정보의 병목이 생기지 않도록 주의
- GPU를 써 보니 항상 CPU보다 빠른 것은 아님..ㅎ


## CH4. Fundatmentals of Machine Learning [link](https://github.com/miniii222/Keras_Deeplearning/tree/master/CH4.Machine_Learning)

# Part2. Deep Learning in Practice
## CH5. Deep learning For Computer Vision [link](https://github.com/miniii222/Keras_Deeplearning/tree/master/CH5.Computer_Vision)
- CNN은 시각적인 분류 문제를 다루는 최상의 도구
- CNN은 우리가 보는 세상을 표현하기 위한 패턴의 계층 구조와 개념을 학습
- 학습된 표현은 쉽게 분석. CNN은 블랙박스가 아님
- 이미지 분류 문제를 풀기 윟 ㅐ자신만의 CNN을 처음부터 훈련시킬 수 있음
- 사전 훈련된 CNN을 사용하여 Feature Extraction, Fine Tuning
- 활성화 히트맵을 포함하여 CNN이 학습한 필터를 시각화

## CH6. Deep learning For Text and Sequences [link](https://github.com/miniii222/Keras_Deeplearning/tree/master/CH6.Text%2CSequence)
## CH7. Advanced Deep learning Best Practices
## CH8. Generative Deep learning
## CH9. Conclusions
