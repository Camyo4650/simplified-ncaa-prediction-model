# 2021-NCAA-prediction-model
---
Creates a basic model for ncaa predictions.

### Data
All data were pulled from the [sportsipy](https://github.com/roclark/sportsipy/tree/ea0043747015209550abeee15df75914a58fe40b) library, which relied on [sportsreference.com](https://www.sports-reference.com/cbb/). The bracket produced was surprising to say the least.

### Team Average Point Differentials CSV
Apon running the main file with proper csv files of each team, a "team_avg_diffs.csv" file will appear in the main project directory. This will then be fed through "SRS.py" where each average point margin will balance eachother out in a matrix-type solution. (Credit to [sports-reference.com](https://www.pro-football-reference.com/blog/index4837.html?p=3) for the formula)

References:
* https://sports.sites.yale.edu/game-team-statistics-nba
* https://www.pro-football-reference.com/blog/index4837.html?p=3
* All data taken from www.sports-reference.com and www.espn.com
* https://sportsreference.readthedocs.io/en/stable/
