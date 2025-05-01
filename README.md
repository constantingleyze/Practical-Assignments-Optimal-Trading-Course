# Optimal Trading & Machine Learning Course - Practical Assignments Repository

This repository contains the 4 practical assignments (PA) for the *Optimal Trading & Machine Learning* course, offered within the Master's program in Probability and Finance (DEA El Karoui), taught by Charles-Albert Lehalle (lectures) and Sophie Laruelle (tutorials).

These assignments focus on high-frequency transaction data for 4 French stocks (Sanofi, Total, Bouygues, LVMH), three American stocks (Google, Amazon, Apple), and three Japanese stocks (Canon, Panasonic, Sony).

Each `DataFrame` contains all the transactions for the year 2011 for the given asset and has the same format:

- The `Time` index represents the timestamp of the transaction;
- The `TradedPrice` column represents the average price per share of the transaction;
- The `TradedQty` column represents the volume of the transaction;
- The `BidPrice` column represents the best bid price just before the transaction;
- The `AskPrice` column represents the best ask price just before the transaction;
- The `BidQty` column represents the volume at the best bid just before the transaction;
- The `AskQty` column represents the volume at the best ask just before the transaction;
- The `TradedSign` column represents the sign of the transaction (negative for Bid and positive for Ask).

### The 4 assignments are as follows:

- **PA1:** Intraday Curves and Relationships Between Daily Variables
- **PA2:** Signature Plot, Epps Effect, and Link Between Spread and Volatility per Trade
- **PA3:** Stochastic Approximation Algorithms Applied to Optimal Execution
- **PA4:** Fillrates and Market Making

### Notes:
- Mme Laruelle’s course material is attached in the TP3 folder, as it is necessary to read it in order to understand the code implementation.
