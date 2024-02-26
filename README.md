# uCDHWs
Identify, analyze, and visualize urban compound drought-heatwave (u-CDHW) events

Here a heatwave will be defined as a period of at least three consecutive days, where the daily maximum temperature in a city is higher than the 90th percentile in the warm season. An urban compound drought-heatwave (u-CDHW) will be identified when a heatwave in a city coincides with a monthly drought event in watersheds and aquifers where the city acquires its water source. An open dataset linking cities with their urban water source developed by (McDondald et al 2014)13 will be used to connect urban heatwave and watershed drought events. The severity of a compound event (u-CDHWS) will be calculated by first multiplying the heatwave severity (HWd) in the city and drought severity ($DSd$) in the water sources on each day, and then summing the daily values over the event:

$$
u–CDHWS=d=1d=DHWdDSd; D3
$$

where $D$ is the duration of the event. The heatwave severity (HWd) will be calculated as

$$
HWd=Tmax,d-T25p/T75p-T25p
$$

where Tmax,d is the daily maximum temperature on day d, and T25p and T75p are the 25th and 75th percentiles of Tmax in the warm season. The drought severity (DSd) will be calculated as

$$
DSd=Wj-Wi,j/j
$$

where $Wi,j$ is the anomalies of terrestrial water storage in year i and month j, and Wj and j are the mean value and standard deviation of anomalies in month j. The daily values of DSd are the same for each month. Historical records of daily maximum temperature and monthly terrestrial water storage will be obtained from the European Centre for Medium-Range Weather Forecast (ECMWF) atmospheric reanalysis version 5 (ERA5)
