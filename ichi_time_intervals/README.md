# Ichimoku Cloud Time Intervals

Reference: [Investopedia - The Formulas for the Ichimoku Cloud](https://www.investopedia.com/terms/i/ichimoku-cloud.asp)

## Purpose

This indicator provides quick visual to understand where price is trading relative to the Price Highs and Price Lows being used to calculate the average for the Tenkan, Kijun, and Leading Span B lines of the Ichimoku Cloud.

## How does it work?

For each line, three tasks are completed:

1. A "Price High" label is drawn above the candle being used for that particular lines calculation
1. A "Price Low" label is drawn above the candle being used for that particular lines calculation
1. A vertical bar is drawn on the oldest candle within that line's high/low range (e.g. 20 inclusive bars for Tenkan on crypto settings)

The lines are evaluated in the following order: Tenkan, Kijun, Conversion.
Lines can share the same candle for its Price High/Low.
In these cases, Conversion is drawn on top of Kijun, and Kijun drawn on top of Tenkan.


## Settings

Each line has the following user input settings:

1. Show interval info
1. Time period
1. Vertical bar color