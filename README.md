# esp8266-bitcoin-ssid-ticker
A Bitcoin SSID ticker for ESP8266's written in Arduino C/C++

Using this software, your ESP8266 will connect to your wifi-network, get the current Bitcoin price (in euro, but can easily be changed to pounds or dollars) and then start an access point named '📈 1 bitcoin = € 1,-' where 1 is the current going rate.
Then it will wait for 30 seconds, and start over.

![SSID screenshot on a phone][image]

[image]:http://i.imgur.com/ftjEFWD.jpg

# settings
There are two settings at the top of the source file, namely:
```c++
const char* ssid =     "my ssid";       //This is where you put in your home network's SSID to connect to
const char* password = "my password";   //This is where you put in your home network's password
```

This information is required to be able to get the current Bitcoin exchange rate.

# sources
Some code has been borrowed from @nebman 's [btc-ticker-esp8266](https://github.com/nebman/btc-ticker-esp8266).

The idea for this project came from @buzztiaan who referenced @shesek's [bitcoin-ssid-ticker](https://github.com/shesek/bitcoin-ssid-ticker).

## like this?
Buy me some coffee using Bitcoin at 19rh9CsKvXiyx7QZi357Bx6vzkPEjj6veT or [PayPal](https://www.paypal.me/NoxiousPluK)! Thanks!
