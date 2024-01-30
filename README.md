## Prediction of Air Quality Index

### Module:
WQD7005 Data Mining 

### Group Members:
| Name | Matric ID|
| ---------------------- |:--------:|
| Wong Jia Hui | S2192852 |
| Low Boon Kiat | 17138399 |
| Jie HongSheng | 22064728 |
| Zhao Zihui | S2187551 |

### Analysis Goal:
The main objective of this project is to perform data sampling and data exploration on the selected dataset to understand the correlations between weather parameters, pollutant’s concentration, and Air Quality Index (AQI). By understanding the correlations between those parameters, we can identify the types of data modifications required and select the right features for constructing our model to accurately predict the AQI during the Modify and Modeling phase in SEMMA methodology. In addition, we also aim to explore the distribution and range of variables to identify if there are any outliers through the exploration. Moreover, a predictive model for AQI offers several significant benefits such assisting government to make better-informed decisions in policy planning and resource allocation, better public health protection from timely alerts, and environmental quality improvement.

### Objective:
- To explore multiple Natural Language Processing methods for extracting feature from text.
- To develop classification models for predicting personality types of an individual based on their online text. 
- To evaluate and compare the performance of the classification models for personality prediction.

### Dataset:
- Global Meteorological Data Repository dataset on [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository)
- Contains a comprehensive set of features such as meteorological, weather data, pollutants’ concentrations, and Air Quality Index (AQI) from various geographical locations around the world.
- The dataset after preprocessing comprises 27 features with a total of 17,149 entries, spanning from 28/08/2023 to 29/11/2023.

### Methodology:  
_Basic Data Cleaning using Talend Data Preparation:_ 
- Drop duplicated columns with different units of measurement.  
- Group similar values and make it easier to analyze data in the Explore phase.  
- Correct the spelling error on country name (noisy data).  
- Change the timezone format (inconsistent data).  

 _Sample Phase:_   
 - Use the entire dataset for the Explore phase, driven by small size of our dataset coupled with our intention to thoroughly examine the data for any potential data quality issues.  
 - For Model phase, we ensure that our model is initially trained on the full dataset to maximize the use of available data, and if necessary, subsequent sampling with proportional stratification will be conducted.
 - Define column metadata.  

_Explore Phase:_   
- Summary statistics  
- Univariate analysis  
- Bivariate analysis  
- Multivariate analysis  
- Time series similarity plot  
- KNIME DBSCAN plot  
- Association rule analysis statistics plot  
- Sequence analysis statistics plot  

_Modify Phase:_   
- Missing value imputation for MCAR, MAR and MNAR  
- Feature engineering  

_Model Phase:_   
- Data partition  
- Decision tree  
- Neural network  
- Ensemble modeling  

_Assess Phase:_   
- Misclassification rate, average squared error and ROC index  
- Confusion matrix  
