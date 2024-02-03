# 한국어 텍스트 분류를 위한 BERT 모델 학습

## 소개 (Introduction)
이 프로젝트는 한국어 텍스트 분류를 위해 BERT (Bidirectional Encoder Representations from Transformers) 모델을 활용한 것입니다. 주로 자연어 처리 (NLP) 분야에서 텍스트 분류 작업에 사용되는 BERT 모델을 한국어 데이터에 적용하여 성능을 향상시켰습니다.

## 기술 스택 (Tech Stack)
- BERT (한국어 버전)
- TensorFlow
- scikit-learn (평가 및 전처리용)

## 사용법 (Usage)
1. `requirements.txt`에 명시된 패키지들을 설치
2. `train_data.csv`에 학습 데이터를, `test_data.csv`에 테스트 데이터를 준비
3. `train_bert_model.py`를 실행하여 BERT 모델을 학습
4. `predict.py`를 사용하여 텍스트 분류 예측을 수행

## 참고 (References)
- BERT 모델: [https://github.com/google-research/bert](https://github.com/google-research/bert)
