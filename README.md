# Analysis of ACLED data

Data from ACLED's [Ukraine Crisis](https://acleddata.com/ukraine-crisis/)
datasets, which can be obtained through creating a free account.

### Preparation

Obtain `Ukraine_Black_Sea_2020_2023_Mar10.xlsx` from ACLED.

### Analysis

See the accompanying ipython jupyter notebook:
[acled_analysis.ipynb](acled_analysis.ipynb)

Total missile events (only those with category "Air")
![acled_missile_strikes](acled_missile_strikes.png)

Total "Air" strikes, including missile events
![acled_air_strikes](acled_air_strikes.png)

Missile (only those with category "Air") vs all "Air" events
![acled_air_vs_missile_strikes](acled_air_vs_missile_strikes.png)

Missile events vs all "Air strike" events
![acled_air_strikes_vs_missile_events](acled_air_strikes_vs_missile_events.png)

Scatter plot of "missile" events, 1-dimensional
![acled_missiles_scatter_1d](acled_missiles_scatter_1d.png)

Scatter plot of "missile" events, 2-dimensional
![acled_missiles_scatter_2d](acled_missiles_scatter_2d.png)

Scatter plot of "missile" events, 2-dimensional
![acled_missiles_scatter_2d](acled_missiles_scatter_2d.png)

Autocorrelation of missile events
![acled_missiles_autocorrelation](acled_missiles_autocorrelation.png)

Missile events, cumulative
![acled_missiles_cumulative](acled_missiles_cumulative.png)

Missile events, cumulative, regression fitted
![acled_missiles_cumulative](acled_missiles_reg_cumulative.png)

Missile "barrages" (more than 10 per day), scatter plot 2-dimensional
![acled_missiles_barrages_scatter_2d](acled_missiles_barrages_scatter_2d.png)

Missile "barrages" (more than 10 per day), scatter plot 1-dimensional
![acled_missiles_barrages_scatter_1d](acled_missiles_barrages_scatter_1d.png)
