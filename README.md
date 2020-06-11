# COVID-data
Repository for data used in paper.

Codebooks explain data in the two csv files.

Prediction spreadsheets allow one to test different levels of mobility changes for each model. To do this, input new mobility value in highighted cell (currently set to 0), prediction column shows prediction for each state as well as 95% confidence interval from estimates.
Each worksheet contains a separate model. "r7" in global models refers to effective reproduction rate with 7 day serial interval.
"uci7" in global model refers to corresponding upper level credible interval. In state models "median" refers to the median r_t value and "uci" to the upper level credible interval.  The worksheet tabs are generally self explanatory at identifying the model.
