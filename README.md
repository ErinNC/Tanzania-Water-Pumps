# Tanzania Water Pump Classification

## Description:

A large portion of Tanzania's population lack access to potable water, so it is imperative to know the functional status of pre-existing water pumps. Using data provided by [Taarifa](http://taarifa.org/) and [Tanzania Ministry of Water](http://maji.go.tz/), we will predict whether a pump is `'functional'`, `'functional needing repair'`, or `'non-functional'` using a variety of machine learning models. The underlying assumption is that the Tanzanian government lacks resources and funds to inspect every single water pump. Our machine learning model will provide predictions for the pumps in the most dire need of repair.

We will use **decision tree**, **random forest**, and **gradient boosting classifiers** and compare their results using classification accuracy as our evaluation metric.

## Necessary Packages:
- matplotlib
- numpy
- pandas
- pandas_profiling
- scikit-learn
- scipy
- seaborn
- sklearn
- xgboost

## Credits
This predictive modeling challenge comes from [DrivenData](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/), an organization that helps non-profits organizations by hosting data science competitions for social impact. The competition has open licensing: "The data is available for use outside of DrivenData." This project was also part of BloomTech's Data Science curriculum.