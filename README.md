# AI Video Processing Projects

안녕하세요!  
이 레포지토리는 **AI Video Processing** 수업에서 진행한 과제와 프로젝트를 정리한 공간입니다.  
딥러닝 기술을 활용한 영상 데이터 처리와 분석 방법을 학습하고, 다양한 실습을 통해 프로젝트를 수행한 결과물을 공유합니다.

---

## 수업 개요
- **딥러닝과 머신러닝의 기초 이론 학습**
- TensorFlow를 활용한 딥러닝 모델 구현 및 학습
- CNN 구조 설계 및 영상 분류 문제 해결
- 탐색 알고리즘을 활용한 최적 경로 탐색 및 시각화

---

## 주요 개념
### 1. Convolutional Neural Networks (CNN)
- **CNN**은 영상 데이터를 처리하기 위해 설계된 딥러닝 모델입니다.
  - **Convolution Layer**: 필터를 통해 이미지의 주요 특징 추출
  - **Pooling Layer**: 데이터 크기를 줄이고 특징 요약
  - **Fully Connected Layer**: 분류를 위한 최종 단계

### 2. Gradient Descent
- **Gradient Descent**는 모델의 손실(Loss)을 최소화하기 위해 가중치를 업데이트하는 최적화 알고리즘입니다.
  - **Batch Gradient Descent**: 전체 데이터를 사용해 가중치 업데이트
  - **Mini-Batch Gradient Descent**: 데이터를 일부씩 나눠 효율적으로 학습

### 3. 탐색 알고리즘
- **BFS (너비 우선 탐색)**: 모든 노드를 계층적으로 탐색하며 최단 경로를 찾음.
- **DFS (깊이 우선 탐색)**: 가능한 한 깊이까지 탐색 후 백트래킹.
- **A***: 휴리스틱을 활용해 가장 효율적으로 최적 경로를 탐색.

### 4. 데이터 전처리 및 시각화
- **데이터 전처리**: 정규화, 이상치 제거, 데이터 증강
- **시각화**: 학습 과정과 결과를 그래프로 표현 (예: 손실 함수 값, 정확도)

---

## 주요 프로젝트
### 1. Gradient Descent와 Linear Regression 비교
- **목적**: 반복 횟수(100회, 10,000회)에 따른 Gradient Descent 성능 분석
- **구현**: 
  - 선형 회귀 모델 학습
  - 반복 횟수 증가에 따른 모델 수렴 속도 비교
- **결과**: 반복 횟수가 증가할수록 모델의 성능이 안정적으로 수렴

### 2. CNN을 활용한 영상 분류 (기말 프로젝트)
- **목적**: MNIST 데이터셋을 사용해 손글씨 숫자 분류
- **구현**:
  - CNN 설계 및 학습
  - Convolution, Pooling Layer 적용
  - Fully Connected Layer와 비교
- **결과**:
  - CNN의 정확도가 Fully Connected Layer보다 뛰어남
  - 학습 정확도: 94%, 테스트 정확도: 89%

### 3. 탐색 알고리즘 실습
- **내용**:
  - BFS, DFS, 반복 심화 탐색을 통해 최적 경로 탐색
  - A* 알고리즘을 활용해 휴리스틱 기반 경로 탐색 구현
- **결과**: BFS와 DFS에 비해 A*가 더 효율적인 경로 탐색 가능

### 4. TensorFlow를 활용한 데이터 시각화
- **목적**: 학습된 모델의 활성화 값과 손실 함수를 시각화
- **결과**:
  - 손실 함수 변화와 학습 정확도를 그래프로 표현
  - 학습 과정에서 모델의 수렴 패턴 분석

---

## 활용 기술
- **프로그래밍**: Python, TensorFlow
- **딥러닝 모델**: CNN, Fully Connected Layer
- **탐색 알고리즘**: BFS, DFS, A*
- **데이터셋**: MNIST
- **데이터 시각화**: Matplotlib, Seaborn

---

AI 기반 영상 처리 기술을 학습하며 얻은 결과물들을 공유합니다.  
**피드백**이나 **협업 제안**은 언제든 환영합니다! 😊
