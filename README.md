# Crypto_Influencer_Analysis

Introduction :
The cryptocurrency markets have evolved into its own over the last decade as a financial entity. With over 2.5T dollars’ worth of assets being held in various digital currencies and tokens. With 130 billion dollars changing hands every day.​

The market is very seductive to any layman because of the volatility of prices, publicity and promise of exorbitant gains. But there is one challenge how does a layman evaluate these options and who does he turn to for financial planning and advise. ​

Unlike Traditional/legacy markets – Equity, Commodity, etc , there is an absence of certified expects a layman can turn to. This void is currently filled by social media and influencers, many of whom are anonymous, on it. Which begs the question - Should we follow them? Whom to follow? How good or accurate have their opinions? ​

Purpose :

Our project aims to evaluate the value of opinions presented by a selection of crypto influencers who primarily post on twitter. For the purpose of our study, we have chosen 48 of the top 50 influencer handles published by crowdsense.ai.​


##################

Approach - 

Scraping and text mining - 

Twitter and coinmarketcap data is scraped(selenium and tweepy)
Sentiment analysis is performed and tweets are tagged(Textblob)
Topics are modelled using LDA (Gensim)


Calculation of returns and benchmarking of influencers performance - 

Once tagged sentiments expressed are tagged to price movements using the time stamp of the tweet and the price information. 
Percentage return is calculated for 5 different benchmark trades, categorized by time period for which the position held (1 day, 3 day, 7 day , 14 day and 30days). 

Trades - 

Positive sentiment => Long/Buy order is placed and sold at the end of the time period 
Negative sentiment => Short/Sell order is placed and bought back at the end of the time period 


Results - 

For all trades, coins and influencers are aggregated and presented in the .xlsx file 
