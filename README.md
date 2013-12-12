altcoin-google-spreadsheet
==========================

Altcoin price tracker into a google spreadsheet.

![Livedemoscreehshot](http://www.lize.it/up/altcoin_screenshot.png)

#How does it work?
Try the [Live Demo](http://goo.gl/RvCxne ) .

It scrapes data from http://coinmarketcap.com . The data is contained in the sheet called *Price Ticker*.

It all goes down to the magic done by importHtml() function with some tricks and parsing.
```
ImportHtml("http://coinmarketcap.com/?"& year(now()) & month(now()) & day(now()) & hour(now()) ,"table",1)
```
#How to use it

There are a few steps needed for having this work on your own spreadsheet: 
- Make a copy of the [Live Demo](http://goo.gl/RvCxne )  and open it
- Past the content of [Code.gs](https://github.com/adv0r/altcoin-google-spreadsheet/blob/master/Code.gs) into a new script
- Create a new trigger that calls the function *transferValue()* every 5 minutes
- Done

If you need help in setting this up, I'll be glad to help. Mail *nico@botcoin.io* and attach some coins if you want to get out of the noise ;) .

#TIPS:	
## Help this project if you think that this project helps you
-  BTC	1NgDPjxNWxTUK9eUExEmAGj4mtiMLGFvYr
-  LTC	LhgAgfFCAo4J6pvg3iyG4eQF5syiEZcXMZ
-  NMC	N79FWuuHCcgNe2YPkenkdQrZXsksFxADuf
-  NVC	4Gprnc172MpPy5hENjdMxBoY6qaHbRMX7G
-  TRC	1DnvtbUEcUGsshAjfqhDf4YTUkHEgxeUci
-  PPC	PFRbFG4WmQPs12A7wGvQwtSXbhsnvZteoT
-  FTC	6vdoqHQohgsGXjzvU2JfArg4U1nGB2MZ53
-  XPM	AXFEykfvr8MJ6n7PdSoR94psQXtqvRaMkM
-  BQC	bMkJLYZsAMN2Si5D8RgQwiwHEbw4sGdMC5
-  MEC	MDbrBWar6ANtiEbhRdVqWyii2gGLAumVjR
-  SXC	S4fntfCLr1hWQZcXnYx9g4ZBZrp8H3zPfF
-  DVC	15YXWsAWNu4mf4Yc6BDZPXTp9PLrUB2dRW

#Discuss it	
  
 [bitcointalk](https://bitcointalk.org/index.php?topic=368226) 
 
 [reddit](http://www.reddit.com/r/CryptoMarkets/comments/1spnk3/online_spreadsheet_with_altcoins_live_data/) 	
