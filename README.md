# Machine Learning Analysis of ENIGH Database 🇲🇽

## Description
This project applies a Random Forest classification model to predict the socioeconomic stratum of Mexican households using data from the 2018 National Household Income and Expenditure Survey (ENIGH) by INEGI.

## Objective
Classify households into four socioeconomic strata (Low, Lower-middle, Upper-middle, High) based on income, expenditure, and housing characteristics.

## Results
- **Model:** Random Forest Classifier
- **Accuracy:** 61%
- **Most important variables:** Current income, transportation expenditure, and type of dwelling

## Key Findings
- Income and expenditure variables are stronger predictors of socioeconomic stratum than physical housing characteristics
- Middle strata are predicted more accurately than extreme strata
- PCA projection confirmed significant overlap between strata, explaining the model's accuracy ceiling

## Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Data Source
INEGI - Encuesta Nacional de Ingresos y Gastos de los Hogares (ENIGH) 2018
https://www.inegi.org.mx/programas/enigh/nc/2018/
