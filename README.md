# CS-Cryptsy_Trader
C# Application to Spread and Swing Trade on www.Cryptsy.com Forex style Crypto markets

This app comes with no warranty, if you trade in Crytpo coins you do so at your own risk any losses are your responsibilty

If you like this app and it is useful to you please show your appreciation by donating to the following wallets:

BitCoin:	    1LL5fbhwdFnxDpBtbbWAvZUtLBsvUDHQ36

DashCoin:	    Xep1nAadBMjfWRdBMwyMu2xnFaU5rCedBd

DiamondCoin:	dckdkD7M4UR5hecipSVv9H3EfhN81Hy7Dm

DOGECoin:	    D8UUat3vkSjHpaKW5qjgcftWfBP4XVoC5x

EarthCoin:	  efWcnsCrJsRSBdM4T6JdAp7HjpMk9HXbCz

LiteCoin:	    LUMrftrHV127fhcGy3cBQNPP4LTPgnhqag

LottoCoin:	  LrGpVRJbZUTF2faCZhbYbHGe4tC4xSCAuT

NobleCoin:	  9iGMQPGm4DedkZuSBcDr5SRHFA8xkxp5ij

The application is based around my other repository CS-CryptsyAPIV2_Class

To use the application you will need to register an account on www.Cryptsy.com and create a public and private key.

When the application is first run you will be presented with a Login form:

  At login screen click in the area with all the donation coin addresses

  Press <ALT> twice

  look at the number of the hour for the current system time

  If it is seven in the evening in 24h clock that is 21

  Add two to the number of the hour in 24h format

  This gives us 23, 23rd letter of the alphabet is v

  Press <CTRL> v

  Now the licence screen is displayed so you can enter a password and your public / private key from Cryptsy

  The public and private keys are encrypted and placed in the connection and licence ini files

  When you next login just enter the password you used when licencing to login and decrypt the Public and Private keys again

Trade settings such as MarketID, amount to trade, % Desired Profit can be set in Cryptsy_Trader.ini.

I hope the app brings you as much enjoyment as it has brought me, have fun :)

More about the application:

The application uses CS-CryptsyAPIv2_Class to query www.Cryptsy.com new API v2 (beta) RESTful API.

When the application loads the login window is displayed (details on home to enter your public and private keys are above) The keys are then encrypted using SHA-256 encryption before being saved to an ini file.

After logging on two windows will be presented.

The main window is for Spread Trading.

The child window is for Swing trading and runs under a seperate thread.

SMA and EMA are used along with %R Williams to try and predict market activity when trading.

Both trading bots write logs using seperate threads so that the bots can concentrate on trading.
