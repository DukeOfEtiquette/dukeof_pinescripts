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

## Notes

### Time Intervals

- PH or PL for a particulor time period can be "ahead" or "behind" each other, relative to time
- PH or PL for multiplie time periods (tenkan, kijun, conversion) can have the same value
- PH or PL of one time period can be "behind" or "ahead" of a diff time period. relative to time
- PH or PL of one time period can be above or below a diff time period, relative to price
- During an uptrend, the following can be observed:
	- The PL for each time period are separate with lower periods being higher than higher periods
	- The PH for each time period is the same value
	- If the PH is the current bar, the trend is very strong
- During a downtrned, the following can be observed:
	- The PH for each time period are separate with lower periods being lower than higher periods
	- The PL for each time period is the same value
	- If the PL is the current bar, the trend is very strong