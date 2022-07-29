# Py-Finance
파이썬 금융 데이터 분석 스터디 `Py-Finance`의 학습 자료 저장소입니다.

**Ch 00. 데이터 타입 | [코드](https://github.com/sw-song/py_finance/blob/main/tutorial/00_data_type.ipynb)**
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

**Ch 01. 라이브러리, 데이터프레임, 인덱싱 | [코드](https://github.com/sw-song/py_finance/blob/main/tutorial/01_library_and_indexing.ipynb) | [설명](https://blog.naver.com/sw930601/222803780138)**
> 판다스 데이터프레임을 다뤄봅니다.
```
Step 1. 라이브러리
Step 2. 인덱싱
     2-1. 열 인덱싱
     2-2. 행 인덱싱
     2-3. 행과 열 동시 인덱싱
```

**Ch 02. 차트 시각화, 시계열 분해, 자기 상관 분석 | [코드](https://github.com/sw-song/py_finance/blob/main/tutorial/02_visualization_decomposition_autocorrelation.ipynb) | [설명](https://blog.naver.com/sw930601/222811729646)**
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

**Ch 03. 회귀 분석, 정규성 검정, 상관 분석, 쌍체 검정 | [코드](https://github.com/sw-song/py_finance/blob/main/tutorial/03_statistical_analysis.ipynb) | [설명](https://blog.naver.com/sw930601/222822718529)**
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

**Ch 04. LogisticRegression, RandomForest, XGBoost, LightGBM | [코드](https://github.com/sw-song/py_finance/blob/main/tutorial/04_machine_learning.ipynb) | [설명](https://blog.naver.com/sw930601/222825538747)**
> 머신러닝 기법을 다뤄봅니다.
```
Step 1. 데이터 불러오기
Step 2. 예측값 정의
Step 3. 모델 인스턴스 생성 및 파이프라인 정의
Step 4. 모델링 및 평가
     4-1. 기본 데이터 모델링
     4-2. 차분 데이터 모델링
     4-3. 로그차분 데이터 모델링
```