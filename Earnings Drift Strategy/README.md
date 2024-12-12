Contain the code and analysis for our Earnings Momentum and Quality Strategy (EMQ), completed as part of the Quantitative Portfolio Management course at Chicago Booth, under Professors Ralph S.J. Koijen and Federico Mainardi.

Project Overview

The project explores the idea that market participants are slow to react to new earnings data, leading to temporary mispricing of stocks. Leveraging behavioral biases like the disposition effect and post-earnings drift, we developed a long-short equity strategy that generates alpha by:
	1.	Going long on stocks that strongly beat earnings expectations.
	2.	Shorting stocks that significantly miss earnings expectations.
	3.	Filtering these stocks through quality metrics (Beneish M-Score, Altman Z-Score) to ensure portfolio robustness.

 Key Features

	Economic Rationale:
	•	Behavioral bias in market participants leads to underreaction to earnings surprises.
	•	Investors sell stocks prematurely on positive surprises and hold losing stocks, creating exploitable drift.
	Investment Strategy:
	•	Long stocks with significant earnings beats (10-15% above consensus).
	•	Short stocks with significant earnings misses (10-15% below consensus).
	Applied quality factors:
	•	Beneish M-Score for detecting potential earnings manipulation.
	•	Altman Z-Score for assessing insolvency risk.
	Backtesting Results:
	•	The strategy consistently demonstrated alpha over the test period, outperforming benchmark indices.

 This project was a collaborative effort by:
	•	Katie Fechner
	•	Nathan Frost
	•	Justin Steuer
	•	Lauren Zheng
