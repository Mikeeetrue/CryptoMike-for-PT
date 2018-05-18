# CryptoMike-for-PT
CryptoMike Profit Trailer Strategy aka HUMMER strategy

Test these settings with your depo in Test Mode first!

This strategy allows you to trade on pumps as well as use sales data to bet on the best coins and be careful with less sucessfull ones.
It means you have all pairs in your portfolio, you DCA it if needed until you catch a pump or just a solid growth.
After that you buy the pair again and DCA it again before the next pump or the next solid growth.
This strategy is still in beta. It was tested on different markets, but it seems there is no much difference between ETH and BTC

Join my Telegram group: https://t.me/joinchat/Cv9-rxAwCR-4mmmt4_zOZg 

This strategy works perfect with 1 BTC.
In this strategy you only need to set up 4 paramaters:

  1. start_balance = just put here your current balance

  2. DEFAULT_initial_cost = 50% of your balance / number of pairs 

    Example: you have 0.6 BTC and you trade on Binance BTC market (125 pairs): 0.6 x 50% / 125 = 0.0024 is your initial cost

  3. DEFAULT_DCA_max_cost = 100% of your balance / number of pairs  x 1.25 

    Example: you have 0.6 BTC and you trade on Binance BTC market (125 pairs): 0.6 / 125 x 1.25 = 0.006 is your DCA max cost
    
  4. DEFAULT_DCA_buy_percentage = minimum order amount /  DEFAULT_initial_cost x 100
    
    Example: your DEFAULT_initial_cost is 0.0024, and you trade on BTC Binance market (0.0012 is the minimum order)
    then 0.0012 / 0.0024 x 100 = 50
    If your depo is less than 0.6 BTC and the result is more than 50, than use what you see in my DCA 
    If your depo is more than 0.6 BTC and the result is less than 50, than delete the bottom part of my DCA which starts from:
    #----------DELETE EVERYTHING BELOW THIS LINE IF YOUR DEPO IS MORE THAN 0.6 BTC-----------

The average profit is in between 0.5-1% ON EVERY MARKET (even on bleeding)

PT Tracker of the test bot with these settings: http://144.202.113.163:8086
Pass: Mike

Use this strategy at your own risk. No guarantees at all :)
