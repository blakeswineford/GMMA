# Guppy

## Description

Python script for trading based on the Guppy Multiple Moving Average (GMMA) technical indicator. 

## Usage

When you run the script it will ask you to enter a stock ticker, when you do the results will show you how the trades would have performed on the given time period of the script. If you'd like to make changes to this time period, you can do so on lines 13-14.

## About Guppy Multiple Moving Average (GMMA)

The Guppy Multiple Moving Average (GMMA) is a technical indicator that aims to anticipate a potential breakout in the price of an asset. The term gets its name from Daryl Guppy, an Australian financial columnist and book author who developed the concept in his book, "Trading Tactics."

Guppy is composed of 12 exponential moving averages (EMAs). The multiple lines of the Guppy help traders see the strength or weakness in a trend better than if only using one (or two) EMAs. The 12 EMAs are separated into two groups:

A “short-term” group of EMAs.
A “long-term” group of EMAs.
Each group contains six MAs.

The “short-term” group is blue, while the “long-term” group is red.
The trend is determined by the long-term EMAs, signals are given by the short-term EMAs.

You would enter a trade when a trend reversal occurs, which is indicated when one group crosses over the other group.

When the short-term group crosses ABOVE the longer-term group, BUY.

When the short-term group crosses BELOW the longer-term group, SELL.

## TL;DR

The Guppy Multiple Moving Average (GMMA) is a technical indicator that identifies changing trends, breakouts, and trading opportunities in the price of an asset by combining two groups of moving averages (MA) with different time periods.
The GMMA consists of a short-term group of MAs and a long-term group of MAs, both containing six MAs, for a total of 12, and is overlaid on the price chart of an asset.
The short-term MAs are typically set at 3, 5, 8, 10, 12, and 15 periods. The longer-term MAs are typically set at 30, 35, 40, 45, 50, and 60.
When the short-term group of averages moves above the longer-term group, it indicates a price uptrend in the asset could be emerging.
Conversely, when the short-term group falls below the longer-term group of MAs, a price downtrend in the asset could be starting.
