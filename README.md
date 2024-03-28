# MIDAS-Nowcast
## Abstract
> This paper proposes an empirical method for Central Banks to contemporaneously estimate household savings from high-frequency banking statistics (without relying on survey or compensation data) through a parsimonious specification of U-MIDAS.
>
>  The Model outperforms Bank of England Forecast by reducing the out-of-sample RMSE by up to 50% without using regularisation techniques for variable selection. Depending on the model specification, the out-of-sample RMSE varies between 2.4 and 4.2 units of Saving Ratio, with residual standard errors of 1.1-1.6 unit. This research contributes to the latest trend in the statistical community towards the integration of money measurements into real-time macroeconomic projections.
>
> Further improvements were introduced in the full paper by considering different lag weight structures (Polynomial and Normalised Almon lags through MLE estimation) for predictors and different transformation techniques for limited dependent variable (Logit).

## Dependent Variable (Quarterly):
- Household Saving Ratio, Seasonally Adjusted (ONS Code: [DGD8](https://www.ons.gov.uk/economy/grossdomesticproductgdp/timeseries/dgd8/ukea))

## Predictors (Monthly):
- Changes of Net Consumer Credit (Gross lending minus Total repayments), Seasonally Adjusted [LPMB3PS](https://www.bankofengland.co.uk/boeapps/database/FromShowColumns.asp?Travel=&searchText=LPMB3PS)
- Changes of M4 Money Supply Holdings by Households, Seasonally Adjusted [LPMVVHS](https://www.bankofengland.co.uk/boeapps/database/FromShowColumns.asp?Travel=&searchText=LPMVVHS)
- Cash Fiscal Deficit (commonly known as Public Sector Net Cash Requirement), Seasonally Adjusted [LPMVQRR](https://www.bankofengland.co.uk/boeapps/database/FromShowColumns.asp?Travel=&searchText=LPMVQRR)

## Latest Nowcast Run:
Latest Release Date: 28-03-2024  
Latest Quarter Published on ONS Website: 2023 Q4  
  
Next Release Date: 26-06-2024  
Next Quarter to be Published: 2024 Q1  
Basic Nowcast (First Month only): 8.041  
Balanced Nowcast (First Month only): 8.324  
AR(1) Benchmark: 9.279  
  
Errors:  
RMSE for Basic Nowcast (First Month only): 2.299  
RMSE for Balanced Nowcast (First Month only): 2.45  
RMSE for AR(1) Benchmark: 3.526  
