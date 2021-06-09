# Power-Consumption-Analysis-of-an-Extruder

I analyze the power consumption of a Pet Food extruder with respect to several variables, such as:
* Motor Load
* Gearbox oil
* Flowrate
* Product

This is a regression problem, as the Power is a continuous variable and I treated it as such. Although there are serveral features, the main objective is to analyze how the 2 different Oils (BL & PR) can afect the power consumption of an industrial machine.

Although the final results show a reduced power consumption with BL Oil,these are not conclusive and I think they require further research.

All the different types of pet food products the two types of oil names were encoded for confidentiality reasons.

The models used were Random Forests and XGBoost. At last, the Random Forest one yielded the better results. However, one could also explore stacking both models for improved results, which has not been done in this particular project.

Finally, acknowledgements for the different sections:
* EDA barplots, boxplots, pivot tables: https://www.kaggle.com/startupsci/titanic-data-science-solutions
* Modelling:
    - Several model evaluation: https://github.com/PlayingNumbers/ds_salary_proj
    - Random Forests Model Hyperparameter Tuning: https://towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74
    - XGBoost Regression Model Hyperparameter Tuning: https://www.analyticsvidhya.com/blog/2016/03/complete-guide-parameter-tuning-xgboost-with-codes-python/
