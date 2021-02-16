## Shark bites analysis

<a href="https://doi.org/10.5281/zenodo.4461747"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.4461748.svg"></a>

Accompanies the article: BRADSHAW, CJA, P MEAGHER, MJ THIELE, RG HARCOURT, C HUVENEERS. 2021. 
<a href="https://doi.org/10.1098/rsos.201197">Predicting potential future reduction in shark bites on people</a>. <em>Royal Society Open Science </em> doi:10.1098/rsos.201197

January 2021

Corey J. A. Bradshaw (corey.bradshaw@flinders.edu.au)
Global Ecology, Flinders University
<a href="http://GlobalEcologyFlinders.com">GlobalEcologyFlinders.com</a>

The <a href="https://github.com/cjabradshaw/sharkbite/blob/master/sharkbiteGithub.R">R code</a> attached reproduces an analysis to predict the number of people who could avoid being bitten by a shark in Australia from 2020-2066 if wearing electronic deterrents.

The analysis requires four different data files:

1. Australian Shark Attack File ('sharkbite.exp.csv') — for proprietry reasons, this dataset is only available upon request to Taronga Conservation Society Australia, Taronga Zoo, Sydney, New South Wales, Australia

2. Monthly southern oscillation index (soi) values from the Australian Bureau of Meteorology (BoM) ('<a href="https://github.com/cjabradshaw/sharkbite/blob/master/soi.csv">soi.csv</a>')

3. Monthly Pacific Decadal Oscillation (pdo) values from https://www.ncdc.noaa.gov/teleconnections/pdo/ ('<a href="https://github.com/cjabradshaw/sharkbite/blob/master/pdo.csv">pdo.csv</a>')

4. Australian population size estimates (past) and projections to 2066 ('<a href="https://github.com/cjabradshaw/sharkbite/blob/master/auspop.csv">auspop.csv</a>') from the Australian Bureau of Statistics

Also accompanying the code are two source files with additional functions necessary to reproduce the analyses ('<a href="https://github.com/cjabradshaw/sharkbite/blob/master/r.squared.R">r.squared.R</a>' & '<a href="https://github.com/cjabradshaw/sharkbite/blob/master/new_lmer_AIC_tables3.r">new_lmer_AIC_tables3.R</a>')
