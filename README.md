# Tennis Visualizations

This repo will contain code to generate various visualizations of tennis data, as well as the output itself and--occasionally--underlying data that doesn't exist elsewhere.

In general, the underlying data will come from my other repos (tennis_atp, tennis_wta, tennis_slam_pointbypoint, etc), and since I'm not that good at data viz, the primary value of the code in this repo is probably the data manipulation.

If I end up adding much stuff here, I'll make more of an effort to organize it. For the time being, code will live in the main directory of this repo, output will head to an output/ subdirectory, and any additional data I use that doesn't already live in one of my other repos will be stored in a data/ subdirectory.

## Contents

**player_tournament_history_serve_speed_boxplot.py (2021-07-04)**

*python/pandas/altair, data from tennis_slam_pointbypoint* 

Compare a player's serve speeds at a single tournament from various years. The output example is Roger Federer's first serve speeds in the first three rounds at Wimbledon, 2014-21.

**elo_vs_surface_elo.py (2021-07-05)**

*python/pandas/altair, data from the [Tennis Abstract site](http://tennisabstract.com/reports/wta_elo_ratings.html).* 

Scatterplot of overall elo ratings vs surface-specific ratings. Output example is the last 16 women at Wimbledon in 2021, overall vs grass.

**tournament_winners_vs_ufe.py (2021-07-06)**

*python/pandas/altair, data from tennis_slam_pointbypoint* 

Plot winner rate (winners per point) against unforced error rate for all players who reached a certain point in a tournament. Output example is the last 8 women at Wimbledon (with the rest of the last 32 shown in the background).


