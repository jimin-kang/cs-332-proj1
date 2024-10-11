**Project 1: Bid Analysis**

Part 1: Evaluate Your Bids)
Evaluate how good your bids were given the bid data from the class (coming soon).  Recall, these are bids for a single-item first-price auction with two bidders (you are one of the bidders, and there is a single competitor).

Consider two ways to calculate your expected utility:
- Exact calculation.  You can write a simple formula that evaluates the winning probability for each bid you placed given that the competing bid is a uniform random bid from the bid data. 
- Monte Carlo simulation.  You can simulate the auction many times and average the results.  In each simulation you draw a random bid from the competing bid distribution in the data.

Compare using these two approaches for making the following calculations.  Note that the answer you get from "exact calculation" is the correct answer while the answer you get from Monte Carlo simulation is only an estimate that gets more accurate with longer simulations:

1. Calculate your winning probability and expected utility with your bids submitted in Ex 1.2 for each of your values.
2. Calculate the optimal bids which maximizes your expected utility given the distribution of opponent bids and each of your possible values.
3. Compare the utility you obtained to the optimal utility you could have obtained.  Can you conclude anything about a good strategy in this auction?

Part 2: Empirical Study of Bidding in the First-Price Auction)
In this part, you will expand on your empirical study of bidding in the first-price auction.  One way to expand on this study is the following:
  
Consider devising a bidding algorithm from data.  Suppose you had a small sample of bid data; how would you use this data to devise a good bidding strategy?  How does a good algorithm change with the amount of data you have?  Suppose you have 1 sample?  or 10 samples?  Or what if you have 100 samples?  Evaluate your bidding algorithm using Monte Carlo simulation.

If you are inspired, you are welcome to instead consider other interesting ways of expanding on the study that are about as involved as the suggestion above. 

**Relevant Files**

Data)

bid_data.csv contains the provided bid data submitted by our classmates for in-class exercise 1.2.

Notebooks)

bid_evaluation.ipynb contains the analysis for Part 1 of this project as described above.

Data_limited_experiments.ipynb contains the strategies, data creation and experiments for part two of the project as described above.
