# SC1015 Data Science Mini-Project: Estimating Frequency of Natural Disasters With Machine Learning

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on making estimations on the likelihood of natural disasters occuring based on the changes in our climate such as the rise in greenhouse gases emissions and temperature. 

<!-- ![image](https://github.com/Dumbledore66/Mini-Project/blob/main/Project%20cover%20page.png) -->
![Cover Image](https://user-images.githubusercontent.com/91188372/164874007-277a8782-8888-4b14-8cb4-e3abafb8d4ba.JPG)



## Contributors
> For any queries related to this project , please refer to [Disclaimer](#disclaimer) section before sending us an enquiry

| Name                  |              Area of Focus               |    Telegram handle |
|----------------------|:----------------------------------------:|----------------|
| Foo Jen Sean | EDA, ARIMA, Multivariate Linear Regression, Slides | @mediumsean |
| Jeffrey Lim Yi Ren | EDA, Slides, Dataset Sourcing, Github Repository | @jeffreylyr |
| Karishein Chandran | EDA, SARIMA, Slides | @karishein6 |  

## Problem Definition
Does the **increase of greenhouse gases** in our climate contribute to a more immediate and imminent problem such as **Natural Disasters**?

## Motivations
In order to proceed with the estimating the frequency of natural disasters, we will have to break down the problem statement into different area of focus. 

Greenhouse gases comprises of Carbon Dioxide (CO2) , Methane(CH4), Nitrous Oxide(N20) and Fluroinated gas. These are the more common gases in our atmosphere that help trap heat in our atmosphere, which is also known as the greenhouse effect. This effect helps to keep our Earth's surface warm, making it habitable for living beings. However ,CO2 produced by human activities is the largest contributor to global warming. By 2020, its concentration in the atmosphere had risen to 48% above its pre-industrial level (before 1750). Hence, this trapping of heat and the increase of carbon gas emission in the atmosphere have in turn, cause a long-term rise in global temperatures, which is known as global warming.

![Greenhouse Gases](https://github.com/Dumbledore66/Mini-Project/blob/main/Miscellaneous/Slide5%20Greenhouse%20gases%20pie%20chart.JPG)

Global Warming can cause changes such as rise in sea level or melting glaciers causes natural disasters such as floods and tsunami. The change in precipitation pattern can lead to increased risk of natural dissaters such as droughts and forest fires in certain area, and floods in another.

![Global Warming](https://github.com/Dumbledore66/Mini-Project/blob/main/Miscellaneous/Slide6%20Global%20warming.JPG)


Natural disasters have always been a threat to all life form. On average since 1970, each disasters have take 367 lives, affected around 740,000 lives, and caused around USD 750,000 in damages.


With this in mind, we have 3 main areas to focus on, the rise in greenhouse gases, rise in global temperature and also the rise in natural disasters occurrence.

![Problem Breakdown](https://github.com/Dumbledore66/Mini-Project/blob/main/Miscellaneous/Slide8%20Problem%20breakdown.JPG)

> For visual project walkthrough, please refer to the slides [below](#external-links-references--inspirations)  
> For detailed project walkthrough, please view the [source code](https://github.com/Dumbledore66/Mini-Project/tree/main/Source%20Codes)


## Source Code of Individual Components (in order)
`Please Install all relevant dependencies and libraries required for EACH individual components`

For a quick glance:
1. [EDA](https://github.com/Dumbledore66/Mini-Project/blob/main/Source%20Codes/SC1015_Mini_Project_EDA.ipynb)
2. [ARIMA Model](https://github.com/Dumbledore66/Mini-Project/blob/main/Source%20Codes/SC1015_Mini_Project_ARIMA.ipynb)
3. [SARIMA Model](https://github.com/Dumbledore66/Mini-Project/blob/main/Source%20Codes/SC1015_Mini_Project_SARIMA.ipynb)
4. [Multivariate Linear Regression](https://github.com/Dumbledore66/Mini-Project/blob/main/Source%20Codes/SC1015_Mini_Project_MVLR.ipynb)

> [Full Jupyter Notebook](https://github.com/Dumbledore66/Mini-Project/blob/main/Source%20Codes/SC1015_Mini_Project_FULL.ipynb)  

## Datasets Used

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

### ARIMA 
Generalised Forecasting Equation
``` ŷt   =   μ + ϕ1 yt-1 +…+ ϕp yt-p - θ1et-1 -…- θqet-q ```  

### SARIMA 
Generalised Equation 
```Φ(𝐵𝑚)𝜙(𝐵)∇𝐷𝑚∇𝑑𝑋𝑡 = Θ(𝐵𝑚)𝜃(𝐵)𝑍𝑡```

### Our ML Process:
![Machine Learning Process](https://user-images.githubusercontent.com/91188372/164874761-4dfe0cb3-2647-4771-88ce-6a4150f915a7.JPG)

## Machine Learning Results
![Model Results](https://user-images.githubusercontent.com/91188372/164883134-987d437f-592a-4196-a84a-3798a380ae77.png)

## Insights, Observations and Conclusion
1. Increased greenhouse gases will lead to global warming, which in turn/concurrently, leads to the increase in occurrence of natural disasters
2. From our forecasted data, this trend will continue to increase throughout from 2021 to 2030 if no actions are taken to reduce the emission of greenhouse gases
3. This climate change will cause an increase in natural disasters such as droughts, floods and forest fires for already affected countries based on our regression model

## Challenges Faced
1. ARIMA forecasting model does not account for seasonality in the time series data
2. The best hyperparameters for the model was obtained by using grid search and selected based on the lowest AIC value
3. SARIMA model was used as it accounts for seasonality in the time series data
4. The accuracy of the prediction of greenhouse gases and temperature change by using SARIMA forecasting model is determined by the RMSE value
5. Multivariate Linear Regression is then used to estimate the natural disaster occurrences from the predicted values given by the SARIMA forecasting model
6. Best estimation of the regression model is determined by the metrics  (RMSE, R2) values


## Out-of-Classroom Implementations
- Initiating the use of GitHub and Google Collab for project collaboration and data repository purposes
- Implementing different visualisation tools such as geopandas, stacked bar graph
- Implementing ARIMA forecasting model with grid search hyperparameters tuning
- Implementing SARIMA forecasting model with grid search hyperparameters tuning
- Implementing Multivariate Linear Regression model

## Closing Remarks
Through this project, our team have learn about the importance of global warming and how it contributes to a more immediate and imminent impact such as natural disasters. Our team believes that every country should be responsible for the amount of carbon emissions produced, and should be taking sustainability measures to reduce the concentration of these gases in our atmosphere. This will in enable a longer lifespan of Mother Earth.  

## External Links, References & Inspirations
- [Presentation Slides (PDF, no audio)](https://github.com/Dumbledore66/Mini-Project/blob/main/Slides_PDF_SC3_LimChandranFoo.pdf)
- Climate Change indicators: https://www.epa.gov/climate-indicators/greenhouse-gases#:~:text=An%20increase%20in%20the%20atmospheric,atmosphere%20increased%20by%2045%20percent.
- Greenhouse gases: https://www.epa.gov/ghgemissions/overview-greenhouse-gases
- ARIMA: https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/
- ARIMA: https://otexts.com/fpp2/arima.html
- SARIMA: https://towardsdatascience.com/time-series-forecasting-with-sarima-in-python-cda5b793977b
- SARIMA: https://towardsdev.com/auto-arima-hyperparameter-search-ab991a21c2bd

## Disclaimer
- This prediction is **NOT** fine-tuned for 100% accuracy
- There are many other external-factors that are **NOT** accounted for for estimating the frequency of Natural disasters in a real world settings
- Data collected in the greenhouse gases datasets might not be complete and accurate
- We shall not hold responsibility for any misinformation of data for prediction and modelling, data derived from prediction, and data presented in any form in this project
- Any part in this repository is and will be subjected to copyright act
- All datasets, knowledge-based information and additional codes references are credited to their rightful owners under [External links, references & inspirations](#external-links-references--inspirations)
- Referencing, redistributing and licensing of this project shall only be for the sole purpose of education purposes

You've reached the end of the READ.ME file, click [here](#sc1015-data-science-mini-project-estimating-frequency-of-natural-disasters-with-machine-learning) to return to the top
