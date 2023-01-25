# IMDb Movie Ratings Prediction with R: Influencing Factors

This is the R markdown repo for our course project in MSBA7027 Machine Learning at HKU Business School. 

## Executive Summary

Internet Movie Database (IMDb), a well-known source of movie information for viewers, 
has never disclosed its rating calculation mechanism to the public. Since ratings
indicate the popularity of a film among the large audience and reflect financial prospects, we aim 
to investigate the influencing factors of IMDb movie ratings via analysis of the best-performing model
among 7 machine learning algorithms. XGBoost yields the lowest cross-validated Root Mean Square Error (RMSE), 
the evaluation metric in this Project, and hence has been selected as the final model fit to aid the analysis. 
By examining the Variable Importance Plots (VIPs) and Partial Dependence Plots (PDPs), we conclude that a movie with 
high ratings tends to be widely watched, old, and receive more votes from users aged over
45 or male. To obtain higher ratings on IMDb, interested parties are recommended to set their work's 
duration within 80 to 220 mins, to release the movies around October, to lean over 
Drama instead of Horror and Action, and to avoid being infatuated with bigshots just for the 
many films they starred. Limitations of the current discussion include data collection 
and sampling bias, a potentially over-simplified calculation of a self-defined variable, and the 
omission of features that evaluate films’ monetary performance.
