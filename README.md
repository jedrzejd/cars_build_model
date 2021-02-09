# cars_build_model

This program build model from [this data](https://github.com/jedrzejd/scrap-otomoto) 

---

## Table of content
* [General info](#General-info)
* [Technologies](#technologies)

## General info

* ```Car_Feature_engineering.ipynb```
    - simple *Data visualization*
    - *feature engineering*
    - save preprocessed data as ```data/car_clean.pickle```

* ```Car_model.ipynb```
    - working on ```data/car_clean.pickle```
    - using logarithm trick
    - using **LightGBM** with hyperparameters optimization

Program saves model to ```data/lgb_model.txt``` directory.



## Technologies
- Python 3
