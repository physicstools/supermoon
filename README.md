# SuperMoon
## Code to Predict When the Moon-Earth Distance is at a Minimum

You may have heard about Supermoons, that occur every once in a while.
They appear larger in size than a normal Moon, due to their closer proximity 
to the Earth at certain times. We just recently had the best Supermoon seen since 1948.
When will be the next?

This jupyter notebook will demonstrate how to compute dates for these interesting viewing nights.
It uses the PyEphem python package to compute a time series of Moon positions and 
the Pandas package to assist with analyzing the results.

## Installation
I use conda from Continuum Analytics to install and manage python libraries.
Quick install instructions:
http://conda.pydata.org/docs/install/quick.html

```
% conda install ephem
% conda install pandas
```
