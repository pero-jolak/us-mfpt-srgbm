# us-mfpt-srgbm

This repository includes data presented in the paper: "", available at:
The dataset is called **us_income_data.xlsx** and contains the following Sheet/Variable:

* Average income data/year - year (time variable);
* Average income data/pxpy - we used in total 18 different threshold income -- short note: if x=74 and y=75, then the column **p74p75** contains the average income one needs to cross in order to enter the **75-th** percentile of the income distribution. Similarly, if x=80 and y=90, then the column **p80p90** represent the average income to enter the **ninth** decile of the income distribution;
* Threshold income data/year - year (time variable);
* Threshold income data/pxpy - here we show in total 18 different threshold income -- short note: if x=5 and y=6, then the column **p5p6** contains the minimum income (threshold) one needs to cross in order to enter the **sixth** percentile of the income distribution. Similarly, if x=80 and y=90, then the column **p80p90** represent the threshold income to enter the **ninth** decile of the income distribution;
* srGBM parameters/year - year (time variable);
* srGBM parameters/top 10% share - empirical variable for the share of income owned by the workers situated at the top 10% of the income distribution;
* srGBM parameters/resetting_rate - empirical variable for the resetting rate;
* srGBM parameters/mu - fitted drift parameter: $\mu$;
* srGBM parameters/sigma - fitted volatility parameter: $\sigma$;
