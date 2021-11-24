# Index Construction and Management

- The **target market** may be based on 
  - Asset class (equities, fixed income, real estate, commodities, hedge funds)
  - Geographic region (Japan, South Africa, Latin America, Europe)
  - Exchange on which the securities are traded (Shanghai, Toronto, Tokyo)
  - ...
- **Index Weighting** decision determines how much of each security to include in the index and has a substantial impact on an index’s value
  - Price Weighting: In price weighting, the weight on each constituent security is determined by dividing its price by the sum of all the prices of the constituent securities (example: DJIA)
    - Advantage of price weighting is its simplicity. 
    - The main disadvantage of price weighting is that it results in arbitrary weights for each security. In particular, a stock split in any one security causes arbitrary changes in the weights of all the constituents’ securities. 
  - Equal weighting. This method assigns an equal weight to each constituent security at inception.
    - Primary advantage of equal weighting is its simplicity.
    - Disadvantages: first, securities that conistitute the largest fraction of the target market value are underrepresented, and securities that constitute a small fraction of the target market value are overrepresented. Second, after the index is constructed and the prices of constituent securities change, the index is no longer equally weighted. Therefore, maintaining equal weights requires frequent adjustments (rebalancing) to the index.
  - Market-Capitalization Weighting: the weight on each constituent security is determined by dividing its market capitalization by the total market capitalization (the sum of the market capitalization) of all the securities in the index
    - The primary advantage of market-capitalization weighting (including float adjusted) is that constituent securities are held in proportion to their value in the target market
    - Disadvantage is that constituent securities whose prices have risen the most (or fallen the most) have a greater (or lower) weight in the index. This leads to overweighting stocks that have risen in price (and may be overvalued) and underweighting stocks that have declined in price (and may be undervalued)
  - Float-Adjusted Market-Capitalization Weighting
  - In float-adjusted market capitalization weighting, the weight on each constituent security is determined by adjusting its market capitalization for its market float. 
    - Market float is the number of shares of the constituent security that are available to the investing public
  - Fundamental weighting: uses measures of a company’s size that are independent of its security price to determine the weight on each constituent security. These measures include book value, cash flow, revenues, earnings, dividends, and number of employees.
- **Rebalancing and Reconstitution**
  - Rebalancing refers to adjusting the weights of the constituent securities in the index.
  - Index provider rebalances the index by adjusting the weights of the constituent securities on a regularly scheduled basis (rebalancing dates)—usually quarterly
  - Price-weighted indexes are not rebalanced because the weight of each constituent security is determined by its price
  - For market-capitalization-weighted indexes, rebalancing is less of a concern because the indexes largely rebalance themselves. Market-capitalization weights are only adjusted to reflect mergers, acquisitions, liquidations, and other corporate actions between rebalancing dates
  - Reconstitution is the process of changing the constituent securities in an index: constituent securities that no longer meet the criteria are replaced with securities 
that do meet the criteria
  - Reconstitution is part of the rebalancing cycle
  - When one security is removed and another is added, the **index provider has to change the weights of the other securities** in order to maintain the market-capitalization weighting of the index

