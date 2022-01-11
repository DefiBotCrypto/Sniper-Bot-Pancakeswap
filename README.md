# 🚀 Pancakeswap BSC Sniper Bot 🚀

📜 **Web3 Pancakeswap Sniper bot written in python3**

 - Sniping liquidity
 - Anti bot (delay block)
 - 3 Take Profit available
 - 3 Stop Loss available
 - Slippage is configurable
 

**📌 How to run :** You just have to set up the config.json file and then run the PancakeSwapSniper.exe file

**📞 Contact :** https://t.me/DefiBotCrypto

**The bot will soon be available on Uniswap and Quickswap, no additional pricing will be required if you already have the ProBot or ProBot+ version to access the same benefit.**


## 🪙 Price 🪙 
**You have several options with different settings for this bot:** 

- **FreeBot :**
*You have access to all the options of the bot. However, there will be a 10% transaction fee (only for successful purchases) and the maximum gas price is 25.* 
- **ProBot** (200 BUSD) **:**
*You have access to all the options of the bot. However, there will be a 5% transaction fee (only for successful purchases).* 
- **ProBot+** (800 BUSD) **:**
*You have access to all the options of the bot. You will have 
0% transaction fee.*

If you want to have access to the bot's source code, it will be available for an additional 500 BUSD if you take the ProBot+ option

**If you want to take one of the paying options, please contact me on telegram here : https://t.me/DefiBotCrypto and send me in BUSD on the address bsc : 0x3CdD9Af8c9a56d670A0fcc18D7544c6Ca0d0F53a**

## 📚 How to parameter 📚
**You need to open config.json**

 
 - **"WALLET ADDRESS": "** *Add public adresse here*",        
 - **"PRIVATE KEY": "** *Add private adresse here*",
 
 - **"MINIMUM TOKEN RECIEVED": "0",** *You can manage the slippage here by determining the minimum number of tokens you want to have when you buy*

 - **"LIQUIDITY POOL": "BNB",** *You can choose BNB or BUSD as the reference currency for your purchase* 
 - **"AMOUNT IN BNB": "1",** *Amount of your purchase in BNB if you have chosen BNB above* 
 - **"AMOUNT IN BUSD": "500",** *Amount of your purchase in BUSD if you have chosen BUSD above*
 
 - **"SELL MODE": "true",** *True if you want to activate it otherwise false* 
 - **"RATIO": "0.3",** *The percentage of the purchase amount you want to sell, for 0.3, you sell 30% of the current amount* 
 - **"TAKEPROFIT": "300",** *with 300 , If you realize a performance of 300% compared to your purchase price you sell "RATIO"* 
 - **"STOPLOSS": "60",** with 60 , If you realize a performance of -40% compared to your purchase price you sell "RATIO"*

**You can set up to three take profit and stop loss in the config.json file**

 - **"ANTI BOT": "false",** *True if you want to activate it otherwise false, it allows to activate the block delay* 
 - **"DELAY BLOCKS": "5",** *When the bot detects liquidity, it waits 5 block before buying, this is often useful when some listings implement anti-bot strategies*

 - **"MIN LIQUIDITY": "1",** *When the bot detects liquidity, it checks if there is enough liquidity on it before buying* 
 - **"MAX LIQUIDITY": "5000000",** *When the bot detects liquidity, it checks if there is too much liquidity on it before buying* 
 - **"GAS PRICE": "9",** *Allows you to choose the gas price to accelerate your transaction on the blockchain* 
 - **"GAS LIMIT": "500000"** *The maximum amount of gas to execute the token purchase contract*