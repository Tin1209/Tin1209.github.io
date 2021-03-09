---
title: 알짜딥러닝 1강 
categories:
- Deep Learning 
tags: 
- Deep Learning
use_math: true
---  

# 단층 퍼셉트론 신경망 구조   

입력 벡터 하나로부터 출력 벡터 하나를 바로 얻어내는 가장 기본적인 구조이다. 출력 $ \mathbf{y} $에 대해서 $ \mathbf{y} = \mathbf{x} \mathbf{w} + \mathbf{b} $ 형태로 나타낼 수 있으며, 출력 벡터의 길이가 n, 입력 벡터의 길이가 m개인 경우 다음과 같이 나타낼 수 있다. 
$$ \begin{bmatrix} y_1 \\ y_2 \\ y_3 \\ \vdots \\ y_n \end{bmatrix} = \begin{bmatrix} x_1 \\ x_2 \\ \vdots \\ x_m \end{bmatrix} \begin{bmatrix} w_{11} & w_{12} & \cdots & w_{1m} \\ w_{21} & w_{22} & \cdots & w_{2n} \\ \vdots & \ddots & \vdots & \vdots \\ w_{m1} & w_{m2} & \cdots & w_{mn} \end{bmatrix} $$   

안녕 $ x $ 나는 ~~ 라고 해! 