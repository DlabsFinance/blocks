# BLOCKS

Blocks is an AMM which sells conditional blocks which payout depending on the value of the asset at expiry

https://www.youtube.com/watch?v=ukqOrri8E7M

Description
Blocks is a hybrid predication market, hedging/speculation platform.
Users buy ERC1155 tokens corresponding to discrete price ranges, which payout if the price lands in that range upon expiry.
Users can easily buy packages of tokens which they can use to hedge AMM positions, crypto holdings, or to speculate on the future state of the market.
Users can also easily approximate traditional and binary options payouts.
Prices are dynamically adjusted using log market scoring rules.

Blocks showcase

How it's made
We built our own math library for exponentiation and logarithms, seeking to keep gas low.
We coded and optimized the log market scoring rules, catered to our application.
We built, tested, and deployed using hardhat.
The frontend is all react with ethers.
We used chart-js for visualizations.

