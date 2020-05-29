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



**N.B.**: make sure the _atomic_ folder of [socceraction](https://github.com/ML-KULeuven/socceraction/tree/atomic) is at the same level as this project if you want to use the associated notebooks.

## Contact

For further information, please contact me on Twitter: [@BLarrousse](https://twitter.com/BLarrousse)
