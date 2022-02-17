# Monte Carlo Simulation using APIs


### Resources

I utilized two APIs:

* The **Alpaca Markets API** used to pull historical stocks and bonds information.  
    
* The **Alternative Free Crypto API** used to retrieve Bitcoin and Ethereum prices.

The documentation for these APIs can be found via the following links:

* [Free Crypto API Documentation](https://alternative.me/crypto/api/)

* [AlpacaDOCS](https://alpaca.markets/docs/)

#### Monte Carlo Simulation

1. Using the Alpaca API to fetch five years historical closing prices for a traditional `40/60` portfolio using the `SPY` and `AGG` tickers to represent the `60%` stocks (`SPY`) and `40%` bonds (`AGG`) composition of the portfolio. Converted the API output to a DataFrame and preview the output.

2. Configured and executed a Monte Carlo Simulation of `500` runs and `30` years for the `40/60` portfolio.

3. Plotted the simulation results and the probability distribution/confidence intervals.
