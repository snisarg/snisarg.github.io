---
layout: post
title:  "Options Cheatsheet"
description: "Reference for basic option trading strategies"
date:   2020-08-25 00:00:00 -0800
categories: blog
comments: true
---

Quick notes about option greeks and basic option strategies for a forgetful person like me.

## Option Stats + Greeks

### Open Interest

- How many options exist in totality.

### Implied Volatility

- Represents the expected volatility of the price of the stock.
- Used as a proxy of market risks.
- Increases when bearish, declines when bullish.
- Directly proportional to the demand of the asset, time left for option expiry.

### Delta

- The amount by which the value of the option moves for every dollar movement in the underlying.
- The more "In the money", the more is the delta. "At the money" deltas are 0.5.

### Gamma

- The amount by which the Delta changes for every dollar movement in the underlying.
- The larger the gamma, the more volatile the price of the option.
- Gamma increases as you get close to expiry.

### Theta

- The amount by which the value of the option drops per day.
- Theta increases as you get close to expiry.

### Vega

- The amount by which the value of the option moves for every 1% change in Implied Volatility of the underlying.
- The price of the option goes up when volatility goes up.
- Vega is higher the further out the option is from expiry. Vega is higher the closer the option is to being "At the money."

## 0 options

### Leveraged stocks

- NOT options, but ETFs that have leveraged assets underlying them.
- Don't have an expiry, which is the advantage over options. Holding these long term is not advisable though because of daily leverage resetting.
- [ETFdb's list of leveraged ETFs](https://etfdb.com/etfs/leveraged/)

## 1 option

### Long Call

- "Buying to open" a long call gives the right but not the obligation to purchase a stock at a predetermined price on a predetermined date.
- The hope is the stock appreciated in value.

### Short Call

- "Selling to open" a short call obligates a trader to sell shares of a stock at a predetermined price on a predetermined date, assuming the short call is in the money.
- The hope is the option doesn’t get exercised so the trader can keep the premium and not give any stocks in exchange.
- Exact opposite of a long call.

### Long Put

- "Buying to open" a long put option gives the right but not the obligation to sell an underlying asset as a specific price at a specific date in the future.

### Short Put

- "Selling to open" or selling a put contract means you take on the obligation of having to buy an underlying asset at a specific price in the future.
- Use this to buy stocks especially during high volatility.

### Covered Call

- Buying 100 stocks AND selling a call of the same stock.

### Protective Put

- To protect yourself from downside in a stock you own. Buy a Put. You lose the premium if nothing happens but safeguard your investment.

## 2 options

### Synthetic Long

- Buying a call and selling a put in the same price and time frame.
- When you want to own the stock at the price, whether it does down or up. The hope is it goes up though.
- This is done to mimic owning the stock. The movement is similar to that. One short and one long position prevents impact from Implied Implied Volatility.

### Bull Call Spread

- Also called Vertical Spread or Long Call Spread.
- Buying a lower priced call and selling a higher priced call.
- Selling the call is to pay for the real call. Unfortunately, the sold call also restricts upside.

### Bear Call Spread

- Selling a lower priced call and buying a higher priced call.
- Shooting for the premium but limiting loss in case value shoots like crazy.

### Bull Put Spread

- Sell a put option and buy an even lower priced put option.
- Lower priced option is to hedge in case the market does really bad.
- “Bull” because we are expecting the stock price to stay flat or go up. “Put” because it’s made up of puts.

### Bear Put Spread

- Buy a put option and sell an even lower priced put option.
- Selling the even lower priced put options limits profits but also downside potential.

### Long Straddle

- Buy a call and put for the same strike price and date.
- Useful during times of high volatility. You’re expecting some movement but don’t know what direction.

### Short Straddle

- Selling call and put for the same strike price and date.
- Expecting no movement in the stock price.

### Long Strangle

- Buying a call and a put at different prices for the same time.
- You’re expecting a huge movement and risking little money as the strike prices are far apart.

### Short Strangle

- Selling a call and put at different prices for the same time.
- Works best when there’s little movement.

### Calendar spread with calls

- Also know as time spread
- Selling a short term call and using that money towards buying a long term call at the same price.
- Looking for the stock to go higher but not immediately. The hope is that the short term call expires.

### Calendar Spread with Puts

- Selling a short term put to use proceeds to buy a long term put at the same price.

## >2 options

### Call Backspread

- Sell at-the-money call option and use that money to buy a lot of out-of-the-money call options.
- Hoping for a very large upward swing by with a conservative approach.

### Iron condor

- Selling a bear call spread and a bull put spread aka straddle with extreme protection.
- You’re expecting stock price movement only within the ranges, and betting on volatility.

### Diagonal Spread with Calls

- Buying a long term call at a lower strike price and selling a short term call at a higher strike price.
- Keep selling short term calls under the protection of the purchase of the single long term call.

### Diagonal Spreads with Puts

- Burying a long term put and selling short term Puts with an even further lower strike price.

### Links

- [Strategy finder tool by TheOptionsGuide](https://www.theoptionsguide.com/option-trading-strategies.aspx)
- [Fidelity's option strategy guide](https://www.fidelity.com/learning-center/investment-products/options/options-strategy-guide/overview)
- [28 option strategies from OptionStrategiesInsider](https://optionstrategiesinsider.com/blog/28-option-strategies-that-all-options-traders-should-know/)
