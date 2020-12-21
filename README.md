# Sentiment-analysis

# 실행 환경
- 클라우드 서버와 GPU를 제공받는 google colab 에서 진행.<br />
- 런타임 유형 하드웨어 가속기 : GPU<br />
- tensorflow와 pytorch 모두 이용<br />

1. NSMC 네이버 영화 리뷰 데이터 감정 분석<br />
- NSMC_KOELECTRA.ipynb<br />
- KOELECTRA 모델 사용<br />

# 실행 방법
1. 모든 셀 실행을 통해 1) 데이터 전처리, 2) 모델 구현 및 학습, 3) test set 결과 확인 및 csv 파일 변환 가능.

참고문헌 및 코드<br />
- 국문<br />
- https://github.com/reniew/NSMC_Sentimental-Analysis<br />
- https://github.com/deepseasw/bert-naver-movie-review<br />

- 영문<br />
- https://github.com/jiwonny/nlp_emotion_classification

2. Friends 영화 대본 데이터 감정 분석<br />
- frineds_eng.ipynb<br />
- ELECTRA 모델 사용<br />

# 실행 방법
1. 캐글에 첨부된 friends_train.json, friends_dev.json, friends_test.json을 다운로드.<br />
2. 이후 모든 셀 실행을 통해 1) 데이터 전처리, 2) 모델 구현 및 학습, 3) test set 결과 확인 및 csv 파일 변환 가능.
