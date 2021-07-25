Time series analysis is a statistical technique that deals with time series data, or trend analysis.  Time series data means that data is in a series of  particular time periods or intervals.  The data is considered in three types:

- Time series data: A set of observations on the values that a variable takes at different times.

- Cross-sectional data: Data of one or more variables, collected at the same point in time.

- Pooled data: A combination of time series data and cross-sectional data.



get some items today:

1. Stationarity
    - μ is const.
    - σ is const.
    - No seasonality

    check: visual, global vs local test, ADF test.
  
2. Unit Roots

    If have unit root, cannot use time series(t.s.). 

    Either do transformation and continue with t.s. or shift to other modeling methods.
  
3. Dickey Fuller Test and Augmented Dickey Fuller(ADF) Test

    DFT is for AR(1);ADFT is for AR(order>1).

    H0: Q=1 ,unit root, not stationary
    
    H1: Q<1 ,no unit root, stationary
  
4. White Noise (non-predictable)

    Yt= signal+ white noise

    when a model have exhausted the variable effect and only left white noise unpredicted, then the model is done.

    - mean is 0
    - std dev is const. with time
    - correlation between lags is 0
 
5. ACF and PACF

    ACF includes direct and indirect effects from time stamp t-2 to t.

    ACF is for MA order  -->  q


    PACF only represents direct effect from time stamp t-2 to t, ignoring all the indirect effects.

    PACF is for AR order  --> p


6. AR and MA

7. ARMA

8. ARIMA

    A: Auto

    R: Regressive

    I: Integrated

    M: Moving

    A: Average


9. AIC and BIC (not only for time series models)


    l: a log likelihood

    k: a number of parameters

    n: a number of samples used for fitting


    AIC = 2k - 2l

            lower the better --> why? 

            - lower k means use less parameters to fit 

            -  higher log likelihood means better model fitting result


    BIC = k*ln(n) -2l

            lower the better --> why?

            - lower k means use less parameters to fit 

            - lower n means less sample is needed in model fitting

            -  higher log likelihood means better model fitting result
