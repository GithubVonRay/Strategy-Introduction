# Strategy-Introduction

Strategy one:
Stock Index (Index Future China) momentum breakthrough day trading strategy. Combined price and volume, observed at the beginning of a day, then searched momentum breakthrough chances in the middle. In the back test from 2017 to 2020, with 1,000,000 initial margin (one position a time), total return 1,020,000, with long and short profit symmetry, profit-loss ratio1.99, Kalmar (profit/max drawdown) 29.87. After entering real time simulation test for a while, entered the real market test.

Strategy two:
Stock Index (Index Future China) reverse day trading strategy. Based on the open price, four clustering prices of past few days, etc. Separated into 8 different scenarios, and open in the specific scenarios (larger conditional probability). In the back test from 2017 to 2020, with 1,000,000 initial margin(one position a time), total return 520,000, with long and short profit symmetry, profit-loss ratio 2.38, Kalmar (profit/max drawdown)30.33. Since it used new methodology of developing strategies, further transferred into IC, after simple adjustment, 4-year Kalmar reached 15.03, verifying the overfitting problem of this strategy, entered the real time simulation test.

Strategy three:
Stock Index (Index Future China) fast trend follow day trading strategy. Used intelligent polyline simplification algorithm to identify momentum faster. Based on clustering prices of past few days, candlestick pattern, etc. to follow the trend. In the back test from 2017 to 2020, with 1,000,000 initial margin (one position a time), total return 1,050,000, with long and short profit symmetry, profit-loss ratio 2.38, Kalmar (profit/max drawdown)30.33. 
