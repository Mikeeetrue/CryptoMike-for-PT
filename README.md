# CryptoMike-for-PT
CryptoMike Profit Trailer Strategy

What is this? This is my version of Default PT config (which is 2.0.5 CryptoCoyns) but (the most important part):
The market goes up and down. Every strategy ends up with some bags that prevents you from trading those coins, which got stuck in bags. 

Also comparing to the default settings, I trade all pairs without filtering. My research has shown, there is no evidence to trade only some pairs (like TOP30 by coinmarketcap or with the 24h volume more than 1000 BTC).

BUT! These coins continue to go up and down and you miss a chance to ride the waves :)

So what I've invented - I send every bought coins to DCA first after it loses 1% of profit and I give the coin a chance to be DCA'ed and sold. If it was not sold or it didn't go to -1%, I send it to the pending Log.

It gives me another chance to trade the same coin and make profits until it got stuck again.

If it got stuck again - it goes to Pending Log. Bot cancels previous order, merge it with the current one, recalculate the average and put another sell order.

Having my bags in pending order rather than in DCA I benefit from this:
1. I can catch the spike. Usually bot doesn't have enough speed to catch the spike, but a sell order has.
2. I'm able to trade the same coin again and make more profit
3. I'm still DCAing (in my own manner - via Pending Log) coins, so average goes down

As additional benefit with this strategy you will see more small sales which is good for your mental health and prevents from panic sell :)

I highly recommend not to increase initial cost (it's now 0.0013). Yes, it takes a lot of time to load your free depo, but it gives you a HUGE advantage when market goes down (it will, trust me!).


Join my Telegram group: https://t.me/joinchat/Cv9-rxAwCR-4mmmt4_zOZg 
