# ML for crypto

## Intro

I've made this list during researching ML for predicting cryptocurrencies for my university project. This list describes only my opinion on the projects listed below.

## Repos

> Just google repo's name to find it. If you find link to the repo - submit a PR, please.

* algo-coin is an extensible trading platform - backtesting/trading/transaction cost modelling.
* algo-trading-crypto - paper implementation, 4 coins, NLP (twitter) + marked data, 0.67 prec, 0.8 acc
* AlphaPy - looks too complex. portfolio management.
* bitcoin-price-prediction - no benchmarks, no tests, implements the 'Bayesian regression for latent source model' method for predicting price variation of Bitcoin. You can read more about the method at https://arxiv.org/pdf/1410.1231.pdf.t
* BitCoin-Value-Predictor - 100% NLP (hadoop/spark/keras), big data solution, but project is almost empty, not sure that team could implement it
* BitcoinForecast - 9 minutes, keras, just paste dataset and go
* bitpredict - 0.08 R2, 23 features, based on order-book
* BitVision - TA + FA + sentiment, no benches, cool flowchart, 3 models, confusion matrixes, data included!
* BTCpredictor - code in matlab, disclaimer "doesn't match current market behaviour"'
* btctrading - multiclass classification
* coinpusher - "neuronal" (:smile:) networks. Clarified docs/code, but performance seems awful.
* crypto-signal - docker, trading automation, alerting, some TA, but no prepared strategy
* Crypto-trading-bot - extended crypto-signal, but without docker, but with improved TA and strategies
* cryptocurrency-analysis - in R, the guy is on the right way, some analysis/correlations plot.
* CryptocurrencyPrediction - nothing interesting, many keras models, but they predict past.
* deep-learning-bitcoin - just a high/low/price_returns model on conv net, nothing interesting. 70% for binary classification (UP/DOWN). training with 1 mln records won't help. Model defenitely needs data preprocessing.
* deep-trading-agent - something meaningful: complex thing with Docker support, implements DeepSense 🔥
* fooltrader - trading platform with backtesting
* freqtrade - HFT bot/trading system, not a prediction model
* gekko - well-known trading bot
* Krypto-trading-bot - another trading bot, not a prediction model. market making.
* Multidimensional-LSTM-BitCoin-Time-Series - looks like an interesting project, there is a link to the blogpost in README, but results looks strange. It may be the case, when network predicts the past
* NextBigCrypto-Senti - twitter nlp analysis based model
* Emsu/prophet - Prophet is a Python microframework for financial markets. Prophet strives to let the programmer focus on modeling financial strategies, portfolio management, and analyzing backtests. It achieves this by having few functions to learn to hit the ground running, yet being flexible enough to accomodate sophistication.
* pytrader - bot with ML capabilities
* R2 Bitcoin Arbitrager - arbitrage framework
* samaritan - Golang, backtesting/trading bot, write algorithm from hand
* Speculator - a good try, some TA
* TensorFlow-Bitcoin-Robot - "A Bitcoin trade robot based on Tensorflow LSTM model.Just for fun.". WTF? Ah, ok, for fun.
* tribeca - market making trading bot with backtesting
* tweetwise - nlp approach
* understanding_crypto_with_sentiment_analysis - another NLP approach

## Papers:

* http://trap.ncirl.ie/2496/1/seanmcnally.pdf - predicting the price of btc using machine learning
* http://www.diva-portal.org/smash/get/diva2:1110776/FULLTEXT01.pdf - Predicting Bitcoin price fluctuation with Twitter sentiment analysisEVITA STENQVISTJACOB LÖNNÖKTH ROYAL INSTITUTE OF TECHNOLOGYSCHOOL OF COMPUTER SCIENCE AND COMMUNICATION

### Author

Vladimir Metnew <vladimirmetnew@gmail.com>