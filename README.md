# Project Name : Bike Demand Assignment

- Background\
BoomBikes, a US bike-sharing provider, has faced significant revenue declines due to the COVID-19 pandemic. To recover, they aim to understand the post-pandemic demand for shared bikes. They plan to use this insight to prepare for increased demand and outperform competitors. BoomBikes has hired a consulting firm to identify key factors influencing bike demand in the American market and to determine how well these factors predict future demand. This strategic approach is intended to help BoomBikes thrive once the economy stabilizes.

- Objective\
Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Table of Contents
* [General Info](#general-information)
* [Modules Used](#Modules-Used)
* [Conclusions](#Conclusions)


## General Information
BoomBikes, a US bike-sharing provider, has faced significant revenue declines due to the COVID-19 pandemic. To recover, they aim to understand the post-pandemic demand for shared bikes. They plan to use this insight to prepare for increased demand and outperform competitors. BoomBikes has hired a consulting firm to identify key factors influencing bike demand in the American market and to determine how well these factors predict future demand. This strategic approach is intended to help BoomBikes thrive once the economy stabilizes.

## Modules Used
- numpy
- pandas
- seaborn
- sklearn
- statsmodel
- scipy
- statsmodels

#### Final Inferences

1. Based on R-Squared Values returned, 84% of variance is explained in Train Dataset whereas 81% of variance in Test Dataset can be explained by the model.
2. Since both R-Squared values are close, one significant observation is overfitting didn't happen
3. Based on the co-efficients returned there is positive increase in the bike demand on yearly basis (i.e. 0.23), more demand if it is a working day (0.04), more demand if the temperature is warmer (0.53) and also some impact based on the Months & Seasons
4. However, there is lesser demand if either windspeed (-0.18) & humidity (-0.16) increases

#### Suggestions

1. Increasing bike availability based on sesons & specific months
2. Evaluating the strategy & fine tuning operational model/pricing strategy to ensure/meet bike availability needs

#### Summary 

In summary, our analysis has highlighted the key factors driving bike demand and offered valuable insights that BoomBikes can use to strengthen their business strategy. These findings emphasize the need to adapt to shifting conditions and customer preferences to enhance service quality and boost revenue.

-  Equation of line becomes/Bike Demand = const*0.1945 + yr*0.2292 + holiday*-0.055 + workingday*0.044 + temp*0.530 + hum*-0.169 + windspeed*-0.185 + mnth_aug*0.056 + mnth_sept*0.125 + mnth_oct*0.041 + weekday_sat*0.052 + season_summer*0.103 + season_winter*0.134 + weathersit_moderate*-0.0582 + weathersit_bad*-0.2486