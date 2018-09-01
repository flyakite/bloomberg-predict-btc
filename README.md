## Bloomblerg Japan Hackathon 2018/09/01

The goal is to predict cryptocurrency price in the future. If possible, predict the timing to buy and sell. Our team decided to use ensemble of different models, semantic text for hype in twitter discussion, technical analysis of historical price and influencse of other finacial markets like stock market and gold market, etc.

This notebook tries to implement the last idea, uses recent Bitcoin price, trade volume, NASDAQ index, OIL ETF index, GOLD ETF index and companies like BLK and BTCS as inputs to predict the BTC/USD price of the next day, given limited amount of time in this hackathon. Of course, the model can be extended to include more factors.