# 독버섯 탐지 이진분류 모델 데이터 분석
버섯의 다양한 특징 데이터를 바탕으로 독버섯 여부를 이진 분류하는 딥러닝 기반 모델 개발<br>
식용 가능 여부를 정확히 예측함으로써 생물학자들의 연구 속도와 정확성을 향상시키는 것을 목표로 함.<br>

### 프로젝트 개요 
- 모델: Multi-Layer Perceptron (MLP), Random Forest Classifier<br>
- 학습 방식: 원본 버섯 데이터(UCI 8124개)로 학습 후, Kaggle 기반 대규모 테스트 데이터 (약 300만 개)로 검증<br>
- 담당 역할: 데이터 분석 및 전처리<br>

### 데이터 분석 및 전처리 
불필요한 feature 제거: gill-attachment, veil-type, veil-color 제거 (총 22개 → 19개 feature 사용)<br>
각 범주의 등장 빈도와 독버섯 확률 시각화하여 의미 없는 범주 파악<br>
비슷한 패턴을 갖는 feature를 그룹화해 데이터 효율성 개선<br>
모든 feature를 One-hot 혹은 Multi-hot encoding으로 처리<br>

- 데이터셋: 독버섯 여부를 예측하기 위한 범주형 특성들로 구성된 이진 분류용 합성 데이터<br>
https://www.kaggle.com/datasets/davinascimento/poisonous-mushrooms 

### 기대효과 
전문가가 아닌 일반 사용자도 버섯의 특성을 입력하면 독성 여부를 예측 가능
생물학자들이 수집한 버섯 데이터를 빠르고 정확하게 분류함으로써 연구 속도와 정확성 향상에 기여




