# COVID Project

이 프로젝트는 데이터로부터 질병의 특성을 파악하는 것을 목표로 합니다. 우리는 여러 기관으로부터 COVID-19의 확산과 관련된 데이터를 수집, 전처리, 모델링하는 프로젝트를 진행했습니다.



### 질병 관련 레포지토리

DVL-Sejong의 질병 관련 레포지토리는 다음과 같이 구성되어 있습니다.


|레포지토리|요약|기타|
|---|---|---|
|[COVID_DataProcessor](https://github.com/DVL-Sejong/COVID_DataProcessor)|COVID-19 관련 데이터 수집 및 전처리 (미국, 이탈리아, 인도, 중국)||
|[AutoCOVID19](https://github.com/DVL-Sejong/AutoCOVID19)|ConvLSTM-based 모델을 이용해 COVID-19에 감염된 사람 수를 예측하고, HPO 라이브러리를 이용해 모델 최적화 수행|비공개|
|[COVIDConvLSTM](https://github.com/DVL-Sejong/COVIDConvLSTM)|ConvLSTM-based 모델을 이용해 COVID-19에 감염된 사람 수 예측|비공개|
|[DeepNIPA](https://github.com/DVL-Sejong/DeepNIPA)|SEIR 모델에 LSTM 모듈과 Neural ODE 모듈 적용|비공개|
|[SIRD](https://github.com/DVL-Sejong/SIRD)|SIRD (Susceptible-Infected-Recovered-Deceased)|기존 전염병 모형|
|[R0_Estimation](https://github.com/DVL-Sejong/R0_Estimation)|R0|기존 전염병 모형|
|[NIPA](https://github.com/DVL-Sejong/NIPA)|NIPA (Network-Inference-Based Prediction Algorithm), 네트워크 추론을 이용한 COVID-19 예측 모델 (중국)|기존 전염병 모형|
|[COVID_Evaluation](https://github.com/DVL-Sejong/COVID_Evaluation)|모델 성능 비교||



### 논문

이 프로젝와 관련해 DVL-Sejong에서 발표한 논문은 다음과 같습니다.

| 논문 | 요약 | 관련 레포지토리 |
|---|---|---|
| [[K-Conference, 2021] Neural ODE를 이용한 COVID-19 확진자 수 예측 모델](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE10583048) | <ul><li>Created LSTM and NeuralODE‑based deep learning model which is predicting the number of infected people with COVID‑19</li><li>Using the NeuralODE module, designed the model for solving ordinary differential equations which is used to estimate the spread of disease</li></ul> | [DeepNIPA(private)](https://github.com/DVL-Sejong/DeepNIPA) |
| [[K-Journal, 2021] 다변량 데이터의 피처 조합을 활용한 ConvLSTM 기반 COVID-19 확산 예측](https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE10545774) | <ul><li>Created ConvLSTM‑based deep learning model for analyzing which feature combinations are affecting the spread of COVID‑19</li><li>Using patient and location information, generated multivariate 3d array dataset, and adopted KDE kernel for maximizing the spatial feature</li><li>Constructed 120 feature combinations by contextual & statistical methods, and optimized the model for each learning dataset using HPO libraries</li></ul> | <ul><li>[AutoCOVID19(private)](https://github.com/DVL-Sejong/AutoCOVID19)</li><li>[COVIDConvLSTM(private)](https://github.com/DVL-Sejong/COVIDConvLSTM)</li></ul> |

