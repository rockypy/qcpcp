# qcpcp
Space-Time Statistical Quality Control of Extreme Precipitation observations

------------------------------------------------------------------------------------------------------------------------
Precipitation extremes form the basis of many engineering design decisions. Extremes are rare events which may differ strongly from “normal” observations. Unfortunately some of the observed extremes may be inaccurate or false. The purpose of this investigation is to present a quality check of observed extremes using space-time statistical methods. As a first step the biggest values for each observation location and event duration are selected. For each of these the observed values of all other stations corresponding to the same time steps are collected and the spatial variogram is calculated. The value at the extreme location is estimated using the surrounding stations, and this estimated value is compared to the observed extreme. If the difference exceeds the critical value of the test, the extreme is flagged as possible outlier. The same procedure is repeated for different aggregations in order to avoid singularities caused by advection. The critical values for the test are obtained by stochastic simulation using the observed spatial structure and a skewed marginal distribution. The flagged extremes are then compared to the extremes of the surrounding stations using the same procedure – interpolation and subsequent comparison of the interpolated and the observed values. All flagged extremes are subsequently compared to the corresponding radar observations and finally implausible extremes are removed. The procedure is demonstrated using observations of high temporal resolution in Germany.

------------------------------------------------------------------------------------------------------------------------

##TODO:

1) Upload code cross validate extreme events
2) Upload code find outliers in cross validated events
3) Upload code plot outliers versus observations
4) Upload code plot map with all stations
