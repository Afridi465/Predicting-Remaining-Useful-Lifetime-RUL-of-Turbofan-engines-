# Predicting-Remaining-Useful-Lifetime-RUL-of-Turbofan-engines
## Exploring NASAs turbofan dataset
This repo contains the notebooks on the NASA turbofan degradation dataset [2]. The turbofan dataset consists of 4 separate challenges of increasing difficulty. The engines operate normally in the beginning but develop a fault over time. For each challenge, the engines in the train set are run to failure. The timeseries in the test set end 'sometime' before failure. The goal is to predict the Remaining Useful Life (RUL) of each turbofan engine in the test set.  See the table below for a short overview of the challenges.


| Dataset | Operating conditions | Fault modes | Train size (nr. of engines) | Test size (nr. of engines) |
| --- | --- | --- | --- | --- |
| FD001 | 1 | 1 | 100 | 100 | 
| FD002 | 6 | 1 | 260 | 259 |
| FD003 | 1 | 2 | 100 | 100 |
| FD004 | 6 | 2 | 248 | 249 |

The notebooks are used to explore the dataset and try various modeling techniques (both Machine Learning and Neural Networks).
