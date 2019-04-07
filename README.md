# BostonHousing_kaggle

Kaggle 데이터 셋 중 하나인 'Boston Housing' 데이터를 이용하여 탐색적 데이터 분석-변수 선택-예측모델링-예측모델 평가로 이어지는 분석을 진행함.

## 분석 환경
- Windows 7 64bit (i7-4790, RAM 16G)
- Python3.6
- Anaconda

## 구성
- Exploratory Data Analysis.ipynb : 데이터 탐색적 분석 과정이 정리된 코드
- Modeling.ipynb : 예측 모델링을 위한 과정(모델 분석 등)이 정리된 코드
- Training&Prediction.ipynb : 최종적으로 모델 학습 및 평가가 정리된 코드
  - Modeling.ipynb 이 각 모델 비교 및 분석이 들어가 있으므로, 여기서 데이터 입력, 변수 선택, 모델 학습, 모델 평가만 추출하여 평가자가 모델을 학습할 수 있도록 따로 구성함. 
- Boston House Price Prediction.pdf : 데이터 탐색적 분석부터 모델링, 평가까지의 분석 리포트

## Requirements
- Python3.6
- Numpy, pandas, scipy, sklearn, matplotlib
- Seaborn (pip install seaborn)
- Xgboost (pip install xgboost)
- Lightgbm (pip install lightgbm)
- Mlxtend (pip install mlxtend)

## 실행 방법
- 아래의 requirements.txt 에 있는 라이브러리를 설치한 후, Training &Prediction.ipynb 을 순차적으로 실행 

		$ pip install -r requirements.txt 
