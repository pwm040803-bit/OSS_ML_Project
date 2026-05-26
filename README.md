# OSS_ML_Project
## 프로젝트 설명

본 프로젝트는 13장에서 학습한 지도학습과 분류 개념을 바탕으로 진행하였다.  
Breast Cancer 데이터셋을 사용하여 유방암 데이터를 양성/악성으로 분류하는 머신러닝 모델을 구현하였다.

## 사용한 데이터셋

- 데이터셋: load_breast_cancer
- 데이터 개수: 569개
- 특성 개수: 30개
- 모델: DecisionTreeClassifier

## Commit 기록

1. Initial upload  
   - breast_cancer_model.py 파일을 처음 업로드하였다.
   - 데이터셋 로드, train/test split, 모델 학습, 예측 및 정확도 출력 코드를 포함하였다.

2. Parameter change experiment  
   - DecisionTreeClassifier 모델에 max_depth=4 파라미터를 추가하였다.
   - 모델 파라미터 변경 실험을 진행하였다.
