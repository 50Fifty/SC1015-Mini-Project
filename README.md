# SC1015 Datascience Mini-Project: Estimating Frequency of Natural Disasters With Machine Learning

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on making estimations on the likelihood of natural disasters occuring based on the changes in our climate such as the rise in greenhouse gases emissions and temperature. 

<!-- ![image](https://github.com/Dumbledore66/Mini-Project/blob/main/Project%20cover%20page.png) -->
![Cover Image](https://user-images.githubusercontent.com/91188372/164874007-277a8782-8888-4b14-8cb4-e3abafb8d4ba.JPG)



## Contributors
> For any queries related to this project , please refer to [Disclaimer](#disclaimer) section before sending us an enquiry

| Name                  |              Area of Focus               |    Telegram handle |
|----------------------|:----------------------------------------:|----------------|
| Foo Jen Sean | ARIMA, Multivariate Linear Regression | @mediumsean |
| Jeffrey Lim Yi Ren |  |  |
| Karishein Chandran |  |  |  


<!-- ## Table of Contents
- [Problem Definitions](#problem-definition)
- [Project Motivations](#motivations)
- [Team members](#contributors)
- [Source code individual components](#source-code-of-individual-components-in-order)
- [Machine Learning Process](#machine-learning-process)
- [Dataset Selection & Preparation](#dataset-selection--preparation)
    - [Disaster Dataset](#disaster-dataset)
    - [Temperature Change Dataset](#temperature-change-dataset)
    - [Greenhouse Gases Datasets](#greenhouse-gases-datasets)
- [Exploratory Data Analysis](#exploratory-data-analysis)
    - [EDA.ipynb]()
    - [ ]
    - [](#)
    - [](#)
    - [](#)
- [Machine Learning - Forecasting models](#machine-learning---forecasting-models)
    - [ARIMA model file: ARIMA.ipynb]()
    - [ARIMA Introduction](#arima-introduction)
    - [Hyperparameters Tuning using Grid search for ARIMA](#hyperparameters-tuning-using-grid-search-for-arima)
    - [Obtaining Test Data ARIMA](#obtaining-test-data-arima)
    - [Future Prediction using ARIMA model](#future-prediction-with-arima-model)
    - [SARIMA Introduction](#sarima-introduction)
    - [SARIMA model file: SARIMA.ipynb]()
    - [Hyperparameters Tuning using Grid search for SARIMA](#hyperparameters-tuning-using-grid-search-for-sarima)
    - [Obtaining Test Data SARIMA](#obtaining-test-data-sarima)
    - [Future Prediction using SARIMA model](#future-prediction-with-sarima-model)
- [Machine Learning - Regression model](#machine-learning---regression-model)
    - [Multivariate Linear Regression Introduction](#multivariate-linear-regression-introduction)
    - [Obtaining Test Data Multivariate Linear Regression](#obtaining-test-data-multivariate-linear-regression)
    - [Future prediction of Natural Disasters](#future-prediction-of-natural-disasters)
- [Insights, Observations and Conclusion](#insights-observations-and-conclusion)
- [Challenges faced](#challenges-faced)
- [Out-of-classroom implementations](#out-of-classroom-implementations)
- [Closing Remarks](#closing-remarks)
- [External links, references & inspirations](#external-links-references--inspirations)
- [Disclaimer](#disclaimer) -->


## Problem Definition
Does the **increase of greenhouse gases** in our climate contribute to a more immediate and imminent problem such as **Natural Disasters**?

## Motivations



> For brief project walkthrough, please refer to the slides [below](#external-links-references--inspirations)  
> For detailed project walkthrough, please view the source code [below](#source-code-of-individual-components-in-order)


<!-- ## Source code of individual components (in order)
`Please Install all relevant dependencies and libraries required for EACH individual components`
1. [EDA](https://github.com/)
2. [ARIMA Model](https://github.com/)
3. [SARIMA Model](https://github.com/)
4. [Multi-Variate Linear Regression](https://github.com/) -->

## Dataset Selection & Preparation

### Disaster Dataset (Kaggle - Baris Dincer):
[ALL NATURAL DISASTERS 1900-2021 / EOSDIS](https://www.kaggle.com/datasets/brsdincer/all-natural-disasters-19002021-eosdis)

### Temperature Change Dataset (NASA):
[GISS Surface Temperature Analysis (GISTEMP v4)](https://data.giss.nasa.gov/gistemp/)

### Greenhouse Gases Datasets (Global Monitoring Laboratory):
[Trends in Atmospheric Carbon Dioxide](https://gml.noaa.gov/ccgg/trends/data.html)  
[Trends in Atmospheric Methane](https://gml.noaa.gov/ccgg/trends_ch4/)  
[Trends in Atmospheric Nitrous Oxide](https://gml.noaa.gov/ccgg/trends_n2o/)

## Machine Learning Models Used and Process
### Models Used:
- ARIMA
- Seasonal-ARIMA (SARIMA)
- Multi-Variate Linear Regression

### Our ML Process:
![Machine Learning Process](https://user-images.githubusercontent.com/91188372/164874761-4dfe0cb3-2647-4771-88ce-6a4150f915a7.JPG)

<!-- ## Exploratory Data Analysis](#exploratory-data-analysis)
    - [EDA.ipynb]()
    - [ ]
    - [](#)
    - [](#)
    - [](#) -->


<!-- 
## Machine Learning Models Used

1. ARIMA
2. SARIMA
3. Multivariate Linear Regression -->

<!-- ### ARIMA Introduction

### [ARIMA model file]:(ARIMA.ipynb)

### Hyperparameters Tuning using Grid search for ARIMA

### Obtaining Test Data ARIMA

### Future Prediction with ARIMA Model

### SARIMA Introduction

### SARIMA model file: SARIMA.ipynb]()

### Hyperparameters Tuning using Grid Search for SARIMA

### Obtaining Test Data SARIMA

### Future Prediction with SARIMA Model

## Machine Learning - Regression model
### Multivariate Linear Regression Introduction
### Obtaining Test Data Multivariate Linear Regression
### Future prediction of Natural Disasters -->

## Insights, Observations and Conclusion


## Challenges faced
- Greenhouse gases datasets have different starting year datapoints
- Temperature change datasets 
- Disasters datasets 

## Out-of-classroom implementations
- Initiating the use of GitHub and Google Collab for project collaboration and data repository purposes
- Implementing different visualisation tools such as geopandas, stacked bar graph
- Implementing ARIMA forecasting model with grid search hyperparameters tuning
- Implementing SARIMA forecasting model with grid search hyperparameters tuning
- Implementing Multivariate Linear Regression model

## Closing Remarks



## External links, references & inspirations
<!-- - Disaster dataset: https://www.kaggle.com/datasets/brsdincer/all-natural-disasters-19002021-eosdis
- Temperature dataset: https://data.giss.nasa.gov/gistemp/
- C02 dataset: https://gml.noaa.gov/ccgg/trends/data.html
- CH4 dataset: https://gml.noaa.gov/ccgg/trends_ch4/
- N20 dataset: https://gml.noaa.gov/ccgg/trends_n2o/ -->
- Presentation Slides: https://docs.google.com/presentation/d/1J5O34ClllCszNBYHl5l9RQCixlJtVRxFab4xB8KYePg/edit?usp=sharing
- Climate Change indicators: https://www.epa.gov/climate-indicators/greenhouse-gases#:~:text=An%20increase%20in%20the%20atmospheric,atmosphere%20increased%20by%2045%20percent.
- Greenhouse gases: https://www.epa.gov/ghgemissions/overview-greenhouse-gases

## Disclaimer
- This prediction is **NOT** fine-tuned for 100% accuracy
- There are many other external-factors that are **NOT** accounted for for estimating the frequency of Natural disasters in a real world settings
- Data collected in the greenhouse gases datasets might not be complete and accurate
- We shall not hold responsibility for any misinformation of data for prediction and modelling, data derived from prediction, and data presented in any form in this project
- Any part in this repository is and will be subjected to copyright act
- All datasets, knowledge-based information and additional codes references are credited to their rightful owners under [External links, references & inspirations](#external-links-references--inspirations)
- Referencing, redistributing and licensing of this project shall only be for the sole purpose of education purposes

You've reached the end of the READ.ME file, click [here](#sc1015-datascience-mini-project-estimating-frequency-of-natural-disasters) to return to the top
