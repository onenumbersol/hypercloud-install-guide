
# Kubeflow 개발 시나리오 가이드

## 시나리오 요약
Fashion-MNIST 데이터를 활용하여 Machine Learing을 진행하고 Model 서빙 과정 설명
    0. 작업을 위한 namespace 만들기
    1. python 코드 작성을 위한 notebook 만들기
    2. ML model 코딩하기
    3. hyper-parameter tuning을 위한 katib 사용하기
    4. Model 학습을 위한 tfjob 생성하기
    5. Model 서빙을 위한 kfserving 사용하기
    6. process 자동화를 위한 workflow 생성하기