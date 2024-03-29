# Docs Outline

0. Cloud 9
1. Intro
	- https://www.youtube.com/watch?v=8pDJThPziLA&list=PLHTyNK8CDJBfZrYvZCSb0bkpv3JUAdRmJ&index=5
	a. Settings + Nomenclature
		- https://www.investopedia.com/terms/i/ichimoku-cloud.asp
	b. Examples
	c. TK Lines as Oscillators
	d. Williams Fractals
	e. Applying The Cloud to trading styles and strategies
		- Trading Styles and Strategies: https://www.youtube.com/watch?v=P_F30RoPXh8
2. TK Crosses
	- use vanseke's indicator
	- Bearish TK cross: https://www.youtube.com/watch?v=OYsjtjcId4g&list=PLHTyNK8CDJBfZrYvZCSb0bkpv3JUAdRmJ&index=29
	- Bullish TK recross: https://www.youtube.com/watch?v=nOzxUAq06JE&list=PLHTyNK8CDJBfZrYvZCSb0bkpv3JUAdRmJ&index=31
3. E2E Trades
	- Bearish E2E: https://www.youtube.com/watch?v=L6ZPDV1UsIU&list=PLHTyNK8CDJBfZrYvZCSb0bkpv3JUAdRmJ&index=30
	- Build indicator that detects price interactions with cloud such as, open outside close inside, open inside close inside, open inside close outside, etc.
4. Kijun Bounce
	- The Kijun Bounce: https://www.youtube.com/watch?v=r_C8iFigzZI&list=PLHTyNK8CDJBfZrYvZCSb0bkpv3JUAdRmJ&index=35
.
.
.
N-1. Timeframe Confluences
	- For timeframe content: https://www.youtube.com/watch?v=Di3Jwp1AWpY&list=PLHTyNK8CDJBfZrYvZCSb0bkpv3JUAdRmJ&index=16
N. Complimentary Indicators & Additional Resources
	- Supplemental MA content: https://www.youtube.com/watch?v=YWgPcSRnxco&list=PLHTyNK8CDJBfZrYvZCSb0bkpv3JUAdRmJ&index=18
	- Other indicators: https://www.youtube.com/watch?v=FiMMdTF28nQ&list=PLHTyNK8CDJBfZrYvZCSb0bkpv3JUAdRmJ&index=21
	- Williams Fractals for entries and SL: https://youtu.be/7PRCv2YFBYc?t=827

## FAQs

- What are different styles of trading?
	- ultra-low TF with lev
	- ultra-high TF hodl
	- shades inbetween
	- Each requires consideration of different timeframes to be most efficient
	- Each carries varying risk/reward and amount of attention required to "babysit" the trade
		- hodl buys and forgets, very low effort. trading lev on 5 min chart requires constant vigilance.
- What is a signal to enter a trade?
	- Handful of cloud signals
- What is a signal to add to a trade?
	- Williams Fractals
- What is a good SL?
	- Williams Fractals
- What is a good TP?
	- Fibs, yearly pivots
- How do I determine a position size?
	- Measure risk/reward of trade
	- Scale position based on that measure
- How do I measure risk/reward?
	- Voodoo, mostly.

## Timeframe Confluences

LTF = LowerTimeFrame
LTF_TP = LowerTimeFrame_TimePeriod

HTF = HigherTimeFrame
HTF_TP = HigherTimeFrame_TimePeriod

(LTF*LTF_TP )/ HTF = HTF_TP

- The 1D kijun (60 timeperiod) is the 3D 20 timeperiod SMA
	- LTF = 1440mins (1d * 24hrs * 60mins)
	- LTF_TP = 60
	- HTF = 4320mins (3d * 24hrs * 60mins)
	- HTF_TP = 20
	- (1440*60) / 4320 = 20

- BUILD TOOL that has dropdown and num input for LTF/HTF/HTF_TP
	- Outputs LTF_TP
	- Build combinations for each input as output