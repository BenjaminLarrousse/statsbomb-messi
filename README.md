# Is it possible to defend against Messi? A data perspective.

Python code associated to my blog post about Messi.

# Content

This repo contains code for analysing [Messi Data Biography](https://github.com/statsbomb/open-data).

It contains folders for Jupyter notebooks, data, and figures.
 
## Notebooks

My analysis is composed of several notebooks. You can find the complete list below, with a small description.

| Notebooks | Description |
| ------ | ------ |
| 01-data_loading | Load Statsbomb data from local or github and do some preprocessing. |
| 02-data_exploration | Explore Messi data and visualize some stats (goals, winning %, etc.) |
| 03-Defense_analysis | Focus on the question "How to defend against Messi?". Exploration of Espanyol-Barcelona 2009/2010 |
| 04-VAEP_with_atomic-spadl | Use [atomic-spadl](https://github.com/ML-KULeuven/socceraction/tree/atomic) to use the VAEP metric |
| 05-xT_with_atomic-spadl | Use [atomic-spadl](https://github.com/ML-KULeuven/socceraction/tree/atomic) to use the xThreat metric |
| 06-EXTRA-advanced_messi_stats | Data vizualisation of some advance metrics |
| atomic-spadl_1-load-and-convert-statsbomb-data | Notebook from [atomic-spadl](https://github.com/ML-KULeuven/socceraction/tree/atomic) |
| atomic-spadl_2-compute-features-and-labels | Notebook from [atomic-spadl](https://github.com/ML-KULeuven/socceraction/tree/atomic) |
| atomic-spadl_3-estimate-scoring-and-conceding-probabilities | Notebook from [atomic-spadl](https://github.com/ML-KULeuven/socceraction/tree/atomic) |
| Utility_functions | Utility functions for data vizualisation and calculate advance stats |
| unit_test | Test of one utility function with [pytest](https://docs.pytest.org/en/latest/) |


## Interactive visualization

### General

All static images can be found here: https://github.com/BenjaminLarrousse/statsbomb-messi/tree/master/figures

| Vizualization | Description |
| ------ | ------ |
| [Win/draw/loss FC Barcelona](https://benjaminlarrousse.github.io/statsbomb-messi/figures/win_draw_loss_barcelona.html) | Win/draw/loss distribution of FC Barcelona with Messi (2004-2019). |
| [Win/draw/loss Messi](https://benjaminlarrousse.github.io/statsbomb-messi/figures/win_draw_loss_messi.html) | Win/draw/loss distribution depending on Messi scoring or assisting. |
| [Messi goals and assists](https://benjaminlarrousse.github.io/statsbomb-messi/figures/messi_goals_and_assists.html) | Number of games with goal, assist, or both. |
| [Goals and assists involvement](https://benjaminlarrousse.github.io/statsbomb-messi/figures/messi_percentage_involvement_goals_assists.html) | Percentage of games without goals or assists, by season. |
| [Messi xG distribution](https://benjaminlarrousse.github.io/statsbomb-messi/figures/messi_xg_probability_distribution.html) | Distribution of xG depending on goals or assists. |
| [Messi VAEP values by season](https://benjaminlarrousse.github.io/statsbomb-messi/figures/vaep_by_season_messi_.html) | Messi VAEP outputs by season. |
| [VAEP distribution](https://benjaminlarrousse.github.io/statsbomb-messi/figures/vaep_distribution.html) | VAEP distribution on the complete Messi dataset.|
| [VAEP vs xG](https://benjaminlarrousse.github.io/statsbomb-messi/figures/vaep_vs_xg_messi.html) | Correlation between xG and VAEP for Messi. |

### Derby Espanyol/Barcelona

All static images can be found here: https://github.com/BenjaminLarrousse/statsbomb-messi/tree/master/figures/derby

| Vizualization | Description |
| ------ | ------ |
| [VAEP Distribution (2009/10)](https://benjaminlarrousse.github.io/statsbomb-messi/figures/derby/vaep_distribution_messi_0910.html) | VAEP distribution, season 2009/10, and derby value. |

### Messi Advanced stats

| Vizualization | Description |
| ------ | ------ |
| [Completed passes inside the box](https://benjaminlarrousse.github.io/statsbomb-messi/figures/advanced-stats/completed_passes_inside_box.html) | Messi completed passes inside the box, normalized per 90. By season. |
| [Completed passes into the box](https://benjaminlarrousse.github.io/statsbomb-messi/figures/advanced-stats/completed_passes_into_box.html) | Messi open play completed passes into the box, normalized per 90. By season. |
| [Completed throughballs](https://benjaminlarrousse.github.io/statsbomb-messi/figures/advanced-stats/completed_throughballs.html) | Messi completed throughballs, normalized per 90. By season. |
| [Key passes](https://benjaminlarrousse.github.io/statsbomb-messi/figures/advanced-stats/key_passes.html) | Messi open play key passes, normalized per 90. By season. |
| [xG assisted](https://benjaminlarrousse.github.io/statsbomb-messi/figures/advanced-stats/xG_assisted.html) | Messi xG assisted, normalized per 90. By season. |


**N.B.**: make sure the _atomic_ folder of [socceraction](https://github.com/ML-KULeuven/socceraction/tree/atomic) is at the same level as this project if you want to use the associated notebooks.

## Contact

For further information, please contact me on Twitter: [@BLarrousse](https://twitter.com/BLarrousse)
