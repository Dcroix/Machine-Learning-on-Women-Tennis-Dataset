# Machine Learning on Women Tennis Dataset

Data Scientists are tasked with predicting the players who are likely to win each match based on match play statistics. These include first serve percentage, first serve won, second serve percentage, second serve won, ace, double faults, winner, unforced errors, break points created, break points won, net points attempted and net points won.

Dataset
The data was explored and pre-processed preparing for machine learning modelling. Variables relevant to addressing the problem were considered as explanatory variables for the model which includes the following:

- FSP - First Serve Percentage
- FSW - First Serve Won
- SSP - Second Serve Percentage
- SSW - Second Serve Won
- ACE - Aces Won by Player
- DBF - Double Fault Committed by Player
- BPC - Break Points Created by Player
- BPW - Break Points Won by Player
- NPA - Net Points Attempted
- NPW - Net Points Won

These were the variables that had data through out the 4 Tournaments: US Open, Australian Open, French Open, and Wimbledon. Few missing cases on the dataset were addressed using K-Nearest Neighbor Imputation technique. Undersampling was utilized to reduce the imbalance in the train set while ensuring that it still has more observations than the test set. These were done after the 80-20 train-test split to avoid data leakage.

The response variable labeled "Result" refers to the classification of players with two levels:
- 0 - First Player Lost the Match
- 1 - First Player Won the Match

You can check out the project in this [link](https://github.com/Dcroix/Machine-Learning-on-Women-Tennis-Dataset/blob/main/Machine-Learning-on-Women-Tennis-Dataset.ipynb)
