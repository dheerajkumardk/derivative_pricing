# derivative_pricing

## European Options Pricing
- Using Binomial Tree Model to understand price evolution of the underlying
- Adding call option payoffs at Maturity
- Introducing risk-neutral probabilities
- Calculating option's prices at each node using risk-neutral probability and backward induction of future scenarios discounting at risk-free rate
- Checking condition of Put-Call Parity to hold true in condition of no-arbitrage
- Computing delta at each node to maintain a hedged portfolio
- Adding to the volatility of the underlying asset, matching u and d such that they accounts for the asset's volatility
- Option prices as N increases converges to a certain value

## American Options Pricing
- Using Binomial Tree Model to understand price evolution of the underlying
- Adding call option payoffs at Maturity
- Calculating option's prices at each node comparing European counter-part and the payoff from early exercise
- Option prices as N increases converges to a certain value
- Adding to the volatility of the underlying asset, matching u and d such that they accounts for the asset's volatility
- Computing delta at each node to maintain a dynamically delta hedged portfolio

## Asian Options Pricing
- Using MC simulations to compute price of a call option
- Using `np.random.binomial` to simulate a random path for the underlying's price
- Running multiple simulations to understand the outcome: More the number of simulations, the more accurate it is
- Plotting those mean prices against number of simulations