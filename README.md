# GARCH-R
GARCH estimation using R packages. Output of `rterm < xxfit_rugarch.r`:

```
prices file = spy_tlt.csv
period = days
nobs = 5718
#returns = 5717 
#symbols = 2 

 CORRELATIONS
       SPY    TLT
SPY  1.000 -0.316
TLT -0.316  1.000

    garch.model: fGARCH
 garch.submodel: GJRGARCH
   distribution: std

         symbol     mean       sd   Sharpe     skew kurtosis      min      max 
            SPY    0.045    1.202    0.599    0.020   17.243  -10.942   14.520 
            TLT    0.019    0.912    0.327    0.054    6.447   -6.668    7.520 

GARCH model for SPY 
     mu   archm   omega  alpha1   beta1   eta11   shape 
-0.0134  0.1134  0.0242  0.0573  0.8595  1.0000  6.4480 
                 
Akaike       2.59
Bayes        2.60
Shibata      2.59
Hannan-Quinn 2.59

GARCH model for TLT 
      mu    archm    omega   alpha1    beta1    eta11    shape 
 0.05316 -0.03580  0.00463  0.04788  0.94692 -0.06609 14.16424 
                 
Akaike       2.46
Bayes        2.47
Shibata      2.46
Hannan-Quinn 2.46

finished xxfit_rugarch.r (2)

for #symbols = 2 
Time elapsed(s): 4.81
```
