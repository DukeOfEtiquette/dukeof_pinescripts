# Scaled Ichimoku Cloud

Reference: [Investopedia - The Formulas for the Ichimoku Cloud](https://www.investopedia.com/terms/i/ichimoku-cloud.asp)

h/t to Cloud 9 discord (rinogo1 & Kumoshi & CryptoPl3be)

## Purpose

Draw two differenct Ichimoku Clouds; one scaled to the current timeframe and the second scaled to a user selected timeframe.

## How does it work?

1. Draw a standard Ichimoku Cloud with settings provided by the user.
1. Using the timeframe set by the user (default: Weekly), the values of the first cloud are scaled before being drawn.

Finding the scale:

```
string tfInput = input.timeframe(defval = "W", title = "Scaled Cloud Timeframe", group = scaledGroup)
float chartTFInMinutes = timeframe.in_seconds() / 60
float scaledTFInMinutes = timeframe.in_seconds(tfInput) / 60
float scale = scaledTFInMinutes/chartTFInMinutes
```

## Settings

1. Toggle on/off either cloud
1. Standard cloud settings (e.g. 9/26/52/26, or 20/60/120/30)
1. Toggle on/off lines and fills
1. Change color of lines and fills