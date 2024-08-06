# BidOptimizerDL

Updates on 07/30/2024

1. Identified a precise problem: Training a model to place the optimal bid in a generalized second price auction (as has often been used for internet advertisement slots).
2. Designed a model with inputs, outputs, and specific form to use for this purpose
3. Broken down the computation into specific tasks that we can work on in parallel (I will write these up for everyone's reference in the next message).
4. Identified a couple of questions to answer: How does our algorithm compare to one found in the literature (computational speed, profit maximization, direct competition, etc.)? Does a generalized second price auction or generalized first price auction lead to more revenue?

Tasks for 07/30 - 08/06

1. Ben - Generate data for the auctions: probability distributions for each bidder (either normal distribution, or totally random), a valuation sampled from these distributions.
2. Enhao - Set up the neural networks with the appropriate inputs and outputs
3. Kevin -Write functions which turn bids and valuations into auction outcomes and profits
4. Aoling - Set up a common environment for us to all code in
5. Jacob - Piece all of the functions together. (Even before we finish, you can probably write a master function with references to the functions we are about to write.)