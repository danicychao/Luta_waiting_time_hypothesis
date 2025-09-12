# Luta waiting time analysis

In this repo, I analyze double espresso waiting time at Luta, the best coffee shop in the world. I also provide a Bayesian framework for Luta fans to update their waiting time and improve the waiting time model.

## Data

I have record the waiting time for the Ethopia double espresso during 08:30 - 09:15 at Luta for 24 days. Data is [here](https://github.com/danicychao/Luta_waiting_time_hypothesis/blob/main/data_waiting_time.txt).

<p align="center">
<img src="figures/histograms_kde.png" style="width:375px;">
</p>

## Probability distribution of waiting time

- The minimum of the 24 data points is 74 seconds, which is very likely the least required time for Luta boys to serve the double espresso (taking order, grinding, machine extracting, and handing to customer).

- The average of the 24 data points is ~137 seconds, with deviation ~52 seconds.

- Since both exponential distribution and gamma distribution fit the 24 data points reasonably well, it is hard to decide which distribution works better on the Luta waiting time.

- Although gamma distribution might fit slightly better, exponential distribution is simpler and has only one parameter. Threfore, I use exponential distribution for the Bayesian framework.

Fitting result:
<p align="center">
<img src="figures/fitting.png" style="width:425px;">
</p>




## Bayesian framework



## Prospects

#### Ongoing project
TODO: keep updating data <br />
TODO: write flow to update data and show analysis results
