## Deprecation Notice

As of October 2022, some parts of this repository is deprecated due to the discontinuation of the FTX service, which is a critical dependency for this project. FTX is no longer operational, and as a result, the code in this repository may not function as intended or may be entirely non-functional.

### What Does This Mean?
- Existing code will be replaced with other methods to pull market data from different sources [Working]
- For more information see [Other risks or opportunities to be explored](#-other-risks-or-opportunities-to-be-explored:) and *Counterparty exposure*
- For even more info go to: https://en.wikipedia.org/wiki/Bankruptcy_of_FTX
---

# First analysis of a semi-risk adjusted trading strategy (BTCUSD)

# Introduction:
Introduced by a faceless Satoshi Nakamoto in a 2008 whitepaper as a “Peer - to - Peer Electronic Cash System, 
Bitcoin and its corresponding market have since experienced multiple 80%+ crashes followed by equally dramatic 
recoveries and head-turning all-time highs during periods of volatile price discovery. 
Although the Bitcoin market is still too immature in its market capitalization and lacks concrete regulatory standards 
to be considered an independent asset class, large corporations such as MicroStrategy and Tesla, as well as some developing 
nations have begun seeking exposure to Bitcoin for various use cases. Considering the terminal supply of Bitcoin and 
the current trajectory of the Bitcoin market, it is quite likely that its corresponding markets may eventually be susceptible 
to large-scale influence by a single entity with the largest balance sheet (ex. gold and silver). However, due to the limited 
liquidity of the current market - among other factors (lagging regulations, sourcing ethics (ex. grandma's retirement funds and 
US companies do not want to hold Bitcoin mined from sanctioned countries or those obtained 
illegally) -  institutional (big money, smart money) activity in this market is still low, allowing the prop and independent 
investors a unique opportunity period to accumulate Bitcoin ahead of further adoption*. While dollar cost averaging should be 
the preferred strategy for most investors who wish to take advantage of the window of opportunity, the following analyses 
seek to experiment with components of a more risk-on strategy, with the assumption that the Bitcoin market undergoes long periods 
where price is ranging and that during those periods, price action reflects the psychology of novice traders with highly leveraged positions. 


# Some limitations identified in the first analysis:

 * This is a strategy that would be the most effective in ranging to locally trending markets - but not in highly trending markets.

 *As with all most high turnover strategies, it will be impossible to maintain a consistent alpha(edge) - since each trade 
utilizing this strategy will serve as another input to be analysed in the corresponding market according to the Efficient Market Hypothesis.
The spread for this particular strategy, even if proven effective under various market conditions, will inevitably thin 
and likely invert over time. Smaller, staggered entries/exits, and smaller position sizes will yield lower returns on average, 
but it may help in maintaining the edge over a longer timeframe. 




# Other risks or opportunities to be explored:

* Arbitrage 
	* Low risk low reward
	* Slippages and frontrunning

* Further risks
	* Counterparty exposure
		* Exchanges
			* Ethical concerns: Exchanges that offer derivatives, mainly highly leveraged perpetual products, 
			may benefit from customer liquidations because a small portion of each position margin (0.05% for BTC pairs) 
			is transferred to the respective “insurance funds” by the liquidation engines to subsidize unforseen losses 
			due to slippages. It is unclear how the insurance funds are treated on the exchanges’ balance sheets, or 
			whether these entities can or do borrow against their customers’ insurance funds in some form.

* Additional opportunities for optimization:
	* Various hedging methods through a combination of spot and corresponding derivatives products 
	* Position sizing
	* Laddering entries and profits
	* Other indicators (consensus = increased probability of significant price movement)



