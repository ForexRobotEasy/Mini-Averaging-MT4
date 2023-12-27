# Mini Averaging MT4

## Description

This code is for a Forex trading robot called Mini Averaging MT4. It is developed by the Forex Robot Easy Team and can be found on their website [forexroboteasy.com](https://forexroboteasy.com/forex-robot-review/mini-averaging-mt4-review-high-risk-forex-trading-tool/).

Mini Averaging MT4 uses a combination of moving averages, MFI (Money Flow Index), and MACD (Moving Average Convergence Divergence) indicators to determine when to open and close positions. It follows a custom strategy that is based on certain indicator conditions.

The code includes necessary libraries for trade execution, moving averages, MFI, and MACD indicators. It also defines some constants such as the symbol to trade (EURUSD), lot size (0.01), stop loss (50 pips), take profit (100 pips), and a flag for enabling or disabling a super averaging strategy.

The code initializes objects for trade execution, moving averages, MFI, and MACD indicators. It also sets custom strategy settings such as the period for fast and slow moving averages, and the MFI level.

There are global variables declared to keep track of the previous moving average value and whether a position is currently open.

The code includes custom functions to open and close positions based on the type of trade action (buy or sell). There is also a function to check indicator conditions and open positions accordingly.

The OnTick() function is called on every tick and it calls the CheckIndicators() function to determine if conditions are met for opening positions.

The OnInit() function is called when the Expert Advisor is initialized. It sets various settings for trade execution such as deviation, stop loss, take profit, and type of order filling.

The OnDeinit() function is called when the Expert Advisor is deinitialized. It closes any open positions.

The OnStart() function is the main program loop that keeps running until the EA is stopped. It calls the OnTick() function and sleeps for 1 second between iterations.

## Product Description

Mini Averaging MT4 is a Forex trading robot developed by the Forex Robot Easy Team. It follows a custom strategy based on moving averages, MFI, and MACD indicators to determine when to open and close positions. The robot is designed to trade the EURUSD symbol with a lot size of 0.01.

The robot executes trades with a predefined stop loss of 50 pips and take profit of 100 pips. It can also be configured to use a super averaging strategy, which implements a grid and martingale system for higher-risk trading.

Mini Averaging MT4 is a high-risk trading tool that aims to generate profits by taking advantage of market trends and momentum. It is suitable for experienced traders who are comfortable with the risks associated with automated trading systems.

Please note that ForexRobotEasy is not the official developer of this product. The code provided here is a sample that can work as described in the product. To find the official developer of this product, please use MQL5. For detailed reviews and trading results of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/mini-averaging-mt4-review-high-risk-forex-trading-tool/).
