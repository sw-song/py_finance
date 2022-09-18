# Py-Finance
파이썬 금융 데이터 분석 기초 학습 자료입니다. 파이썬 기초 문법과 기초적 수준의 주가(시계열) 분석을 배워봅니다.

## **1. 기본 학습 자료**

**[Ch 01. 라이브러리, 데이터프레임, 인덱싱](https://github.com/sw-song/py_finance/blob/main/tutorial/01/tutorial_01.ipynb)**
> 판다스 데이터프레임을 다뤄봅니다.
```
Step 1. 라이브러리
Step 2. 인덱싱
     2-1. 열 인덱싱
     2-2. 행 인덱싱
     2-3. 행과 열 동시 인덱싱
```

**[Ch 02. 차트 시각화, 시계열 분해, 자기 상관 분석](https://github.com/sw-song/py_finance/blob/main/tutorial/02/tutorial_02.ipynb)**
> 시계열 데이터에 대해 이해합니다.
```
Step 1. 데이터 불러오기
Step 2. 시각화
     2-1. 기본 선 그래프
     2-2. 그래프 채우기
     2-3. 산점도
     2-4. 기준선 및 구간 표시
     2-5. 타이틀 표기
Step 3. 장/단기 추세
     3-1. 3일 이동평균
     3-2. 30일 이동평균
Step 4. 시계열 분해
     4-1. 장기 주가데이터
     4-2. 단기 주가데이터
     4-3. 장기 로그 주가데이터
     4-4. 장기 로그차분 주가데이터
Step 5. 자기상관분석
     5-1. 기본 종가 데이터
     5-2. 로그 데이터
     5-3. 로그차분 데이터
```

**[Ch 03. 회귀 분석, 정규성 검정, 상관 분석, 쌍체 검정](https://github.com/sw-song/py_finance/blob/main/tutorial/03/tutorial_03.ipynb)**
> 기본적인 통계 분석 방법론을 경험합니다.
```
Step 1. 데이터 불러오기
Step 2. 데이터 분할
     2-1. 시점(2020년) 기준 분할하기
     2-2. 데이터 길이 맞추기
     2-3. 데이터 분포 맞추기(스케일링)
Step 3. 통계 분석
     3-1. 회귀 분석
     3-2. 정규성 검정
     3-3. 상관성 검정
     3-4. 쌍체 검정
```

**[Ch 04. 머신러닝](https://github.com/sw-song/py_finance/blob/main/tutorial/04/tutorial_04.ipynb)**
> LogisticRegression, RandomForest, XGBoost, LightGBM을 활용해 AI 분류모델을 만들어봅니다.
```
Step 1. 데이터 불러오기
Step 2. 예측값 정의
Step 3. 모델 인스턴스 생성 및 파이프라인 정의
Step 4. 모델링 및 평가
     4-1. 기본 데이터 모델링
     4-2. 차분 데이터 모델링
     4-3. 로그차분 데이터 모델링
```

## **2. 보충 자료**

**[Appendix 01. 데이터 타입](https://github.com/sw-song/py_finance/blob/main/tutorial/appendix/01/appendix_01.ipynb)**
> 데이터 분석을 위한 최소한의 자료형을 알아봅니다.
```
Step 1. 단일 데이터 표현
     1-1. int
     1-2. float
     1-3. str
     1-4. bool
Step 2. 다중 데이터 표현
     2-1. list
     2-2. dict
     2-3. set
Step 3. 벡터 및 행렬 표현
     3-1. (numpy)array
     3-2. (pandas)DataFrame, Series
```

**[Appendix 02. 반복문, 함수, 데이터 시각화](https://github.com/sw-song/py_finance/blob/main/tutorial/appendix/02/appendix_02.ipynb)**
> subplots와 반복문, 함수를 사용해 더 효율적으로 차트를 그려봅니다.
```
Step 1. Matplotlib
     1-1. subplots
     1-2. subplots with for-loop
     1-3. fill_between
     1-4. alpha
     1-5. line plot + fill_between
     1-6. axvline
     1-7. axvspan
Step 2. Time Series
     2-1. get stock data
     2-2. draw yearly stock trends with subplots
     2-3. time series decomposition
     2-4. auto-correlation, partial auto-correlation
```

**[Appendix 03. 상관 분석, 회귀 분석](https://github.com/sw-song/py_finance/blob/main/tutorial/appendix/03/appendix_03.ipynb)**
> 선형 관계에 대해 이해하고, 상관 분석과 회귀 분석의 차이를 확인합니다.
```
Step 1. 선형 관계와 분석 방법론
Step 2. 주가 데이터 추출
Step 3. 상관 분석
     3-1. 테슬라 주가와 애플 주가간 상관 분석
     3-2. 테슬라 거래량과 애플 주가간 상관 분석
     3-3. 랜덤한 숫자와 애플 주가간 상관 분석
Step 4. 회귀 분석
     4-1. MS 주가와 애플 주가간 회귀 분석
     4-2. 전날 MS 종가와 다음날 거래량간 회귀 분석
```
