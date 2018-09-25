# Logic for stock screening


- [Bluest of the Blue Chips](https://www.screener.in/screens/234/Bluest-of-the-Blue-Chips/?sort=Market+Capitalization&order=desc)
```
(Market Capitalization > 3000) AND
(Average return on equity 5Years > 20) AND
(Debt to equity < 1.5) AND
(Interest Coverage Ratio > 2) AND
( PEG Ratio <= 1) AND
(Profit growth 5Years > 20)
```

- [Discounted Book Value Gems](https://www.screener.in/screens/229/Discounted-Book-Value-Gems/)
```
(Price to book value <= 0.75) AND
( Return on equity >= 15  ) AND
(Average return on equity 5Years > 15) AND
(Debt to equity < 1) AND
(Interest Coverage Ratio > 1.5) AND
(Current ratio >= 2) AND
(Profit growth 5Years >= 15)
```

- [Bulls at discount - WIP](https://www.screener.in/screens/141809/Bulls-at-discount/)
```
(Market Capitalization > 3000) AND
(Average return on equity 5Years > 20) AND
(Debt to equity < 1.1) AND
(Interest Coverage Ratio > 2) AND
( PEG Ratio <= 1) AND
(Profit growth 5Years > 20) AND
Sales growth 5Years > 20 AND
Price to book value < 5 AND
Unpledged promoter holding = Promoter holding
```
