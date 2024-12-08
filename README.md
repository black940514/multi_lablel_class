Multi-label classification

# Multi-label classification이란?
- 두 이상의 선택지에서 여러 객체를 분류하는 기법
- Loss function -> Binary Cross Entropy
- Sigmoid threshold 0.5

# 장단점
- 클래스 개수 절감
하나의 모델로 모든 클래스의 조합으로 구성할 수 있음

- 데이터 불균형 문제
빈도수 높은 카테고리가 존재하면 학습이 불리
-> 빈도수가 높은 클래스의 데이터를 줄이거나 빈도수가 낮은 클래스의 데이터를 늘림

- 모델 복잡도 증가

# Google Vision API
- 이미지 분류 모델
- 이미지 내 모든 객체 분류

