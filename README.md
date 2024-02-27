# uCDHWs
Identify, analyze, and visualize urban compound drought-heatwave (u-CDHW) events

Here a heatwave will be defined as a period of at least three consecutive days, where the daily maximum temperature in a city is higher than the 90th percentile in the warm season. An urban compound drought-heatwave (u-CDHW) will be identified when a heatwave in a city coincides with a monthly drought event in watersheds and aquifers where the city acquires its water source. An open dataset linking cities with their urban water source developed by (McDondald et al 2014) will be used to connect urban heatwave and watershed drought events. The severity of a compound event (u-CDHWS) will be calculated by first multiplying the heatwave severity (HWd) in the city and drought severity ($DS_d$) in the water sources on each day, and then summing the daily values over the event:

$$
uCDHW_S = \sum_{d=1}^{D} (HW_d \times DS_d)
$$

where $D$ is the duration of the event. $HW_d$ is calculated as the ratio of the difference between the daily maximum temperature ($T_{max,d}$) and the 25th percentile temperature ($T_{25p}$) to the difference between the 75th and 25th percentile temperatures of $T_{max}$ in the warm season. The drought severity ($DS_d$) is calculated based on the anomalies of terrestrial water storage ($W_{ij}$) compared to the mean ($W_j$) and standard deviation ($\sigma_j$) of anomalies in the month $j$.

These equations help in assessing the combined impact of heatwaves and droughts on urban greening effectiveness by integrating climate data and water resource availability. The document uses these calculations to identify cities at risk of reduced cooling effects from urban greening due to u-CDHWs and to propose strategies for enhancing climate resilience.
