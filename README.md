# 14-Deep_Learning
Unit 14: Deep Learning

Two models were trained, one in which the closing price of Bitcoin was predicted based on a rolling window of closing prices, and one in which the closing prices were predicted using rolling Fear and Greed Index data. Similar models were made for both, with window size and batch size differing.

The model that used a window size of 2 previous closing prices most accurately predicted the next closing price, with a loss of only 0.24%. The model that used F&G index data, on the other hand, resulted in 7.1% loss and didn't seem to correlate directly with closing prices.
