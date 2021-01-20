# Caribbean-connectivity-and-travel-time-distributions

This repository contains Python scripts used in my BSc research project on investigating connectivity and travel time distributions of plastic pathways in the Caribbean Sea.

In this code, for every predefined region is checked which trajectories were in it at what time.
From this, the time it takes for trajectories to go from region i to region j is calculated.
Functions from scipy.stats are then fitted to the timedistributions and the chi-squared values to measure the goodness of fit is calculated.
