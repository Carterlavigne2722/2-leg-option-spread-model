# 2-leg-option-spread-model utilizing excel 
Objective: Model seeks to determine the expected value from an option spread strategy one long one short at first 

Authored by: Carter LaVigne

Flow: 
- The model works off of the black scholes model developed from the very base mathematics that you use to derive option prices.
- The strategy is to be modeled through a monte carlo strategy of sorts. 
- Equity prices are to be modeled through a spaghetti simulation. 
- This is then aggregated into varying buckets of paths that will then be utilized to provide an expectation value for the strategy.
- The model will compute the varying expectation values of the two leg option spread over each pathway. 

- Models aim is to provide a framework for the strategy that can be utilized to optimize this strategy for specific securities that behave in a certain fashion. 
    - The inputs we can control in application and that will change the expectation value of the strategy are: Strikes, reset of sold option, bid/ask spreads, timeframe(of long dated)

- Eventually there should be a way to allow for a way to quantify and qualify the above controllable inputs. 

