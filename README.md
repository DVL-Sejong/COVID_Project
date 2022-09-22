# COVID Project

This project aims to characterize how diseases are spreading through data. We have worked on a project to collect, preprocess, and model data related to the spread of COVID-19 from multiple organizations.



### Disease-related Repositories

DVL-Sejong's disease-related repositories are organized as follows:

| Repositories                                                 | Summary                                                      | Etc                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------------------------------------- |
| [DVL-Sejong/COVID_DataProcessor](https://github.com/DVL-Sejong/COVID_DataProcessor) | COVID-19-related data collection and preprocessing (USA, Italy, India, China) |                                                      |
| [DVL-Sejong/AutoCOVID19](https://github.com/DVL-Sejong/AutoCOVID19) | Predict the number of people infected with COVID-19 using a ConvLSTM-based model, and optimize the model using the HPO libraries | Private                                              |
| [DVL-Sejong/COVIDConvLSTM](https://github.com/DVL-Sejong/COVIDConvLSTM) | Predicting the number of people infected with COVID-19 using a ConvLSTM-based model | Private                                              |
| [DVL-Sejong/DeepNIPA](https://github.com/DVL-Sejong/DeepNIPA) | Expanded SEIR model using LSTM module and Neural ODE module  | Private                                              |
| [DVL-Sejong/SIRD]()https://github.com/DVL-Sejong/SIRD        | SIRD (Susceptible-Infected-Recovered-Deceased)               | Classical compartmental model in epidemiology        |
| [DVL-Sejong/R0_Estimation](https://github.com/DVL-Sejong/R0_Estimation) | R0                                                           | Estimating basic reproduction number in epidemiology |
| [DVL-Sejong/NIPA](https://github.com/DVL-Sejong/NIPA)        | NIPA (Network-Inference-Based Prediction Algorithm), network inferenced COVID-19 prediction model in China |                                                      |
| [DVL-Sejong/COVID_Evaluation](https://github.com/DVL-Sejong/COVID_Evaluation) | Comparing model performance among COVID-19 prediction models |                                                      |



### Papers

The papers presented by DVL-Sejong are as follows:

| Papers                                                       | Summary                                                      | Related Repositories                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [[K-Conference, 2021] COVID-19 Infected Case Prediction Model using Neural ODE](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE10583048) | <ul><li>Created LSTM and NeuralODE‑based deep learning model which is predicting the number of infected people with COVID‑19</li><li>Using the NeuralODE module, designed the model for solving ordinary differential equations which is used to estimate the spread of disease</li></ul> | [DVL-Sejong/DeepNIPA(private)](https://github.com/DVL-Sejong/DeepNIPA) |
| [[K-Journal, 2021] ConvLSTM-Based COVID-19 Outbreak Prediction using Feature Combination of Multivariate Dataset](https://www.dbpia.co.kr/Journal/articleDetail?nodeId=NODE10545774) | <ul><li>Created ConvLSTM‑based deep learning model for analyzing which feature combinations are affecting the spread of COVID‑19</li><li>Using patient and location information, generated multivariate 3d array dataset, and adopted KDE kernel for maximizing the spatial feature</li><li>Constructed 120 feature combinations by contextual & statistical methods, and optimized the model for each learning dataset using HPO libraries</li></ul> | <ul><li>[DVL-Sejong/AutoCOVID19(private)](https://github.com/DVL-Sejong/AutoCOVID19)</li><li>[DVL-Sejong/COVIDConvLSTM(private)](https://github.com/DVL-Sejong/COVIDConvLSTM)</li></ul> |

