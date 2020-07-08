# Probability of Winning the Lottery

This repository contains a notebook where I  explore the probability of winning the [6/49 lottery](https://en.wikipedia.org/wiki/Lotto_6/49).

In the 6/49 lottery, six numbers are drawn from a set of 49 numbers that range from 1 to 49. A player wins the big prize if the six numbers on their tickets match all the six numbers drawn. 

To explore the probability of winning the lottery I created four main functions described below.
- `one_ticket_probability()` — calculates the probability of winning the big prize with a single ticket
- `check_historical_occurrence()` — checks whether a certain combination has occurred in the Canada lottery data set
- `multi_ticket_probability()` — calculates the probability for any number of of tickets between 1 and 13,983,816
- `probability_less_6()` — calculates the probability of having two, three, four or five winning numbers exactly

The notebook is based on a guided project from Dataquest, an online Data Science bootcamp. The learning goal of the project was to test understanding of theoretical and empirical probabilities, probability rules, and combinations and permutations.

The 649 [data set](https://www.kaggle.com/datascienceai/lottery-dataset) has data for 3,665 drawings, dating from 1982 to 2018. The dataset is originally from Kaggle, see link.
