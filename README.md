ETF Comparison Analysis: VOO, VTI, QQQ

✅Overview
This project analyzes and compares the performance of three popular U.S. ETFs: VOO, VTI, and QQQ.
The analysis was inspired by the recent IT sector bubble — I wanted to compare ETFs with different levels of IT sector exposure:
	•	QQQ — heavily focused on the IT sector
	•	VTI — broadly diversified across all U.S. sectors
	•	VOO — focused on large-cap companies with moderate IT exposure

The goal is to evaluate monthly drawdowns, trends, and overall performance, and visualize them for clear comparison.

✅Data
The project uses CSV files containing historical price data for each ETF:
	•	FUND_US_ARCX_VOO.csv — VOO ETF data
	•	FUND_US_ARCX_VTI.csv — VTI ETF data
	•	FUND_US_XNAS_QQQ.csv — QQQ ETF data

All datasets are stored in the data/ folder (or at the root if preferred).

✅Methodology
	1.	Data Loading:
Each CSV is loaded into a Pandas DataFrame (voo_df, vti_df, qqq_df).
	2.	Monthly Aggregation:
	•	Group data by Month
	•	Calculate minimum drawdown per month
	•	Ensure months are sorted chronologically using a months_order list
	3.	Visualization:
	•	Charts compare monthly drawdowns and performance across the three ETFs
	•	Trend lines show month-over-month performance for each ETF
	4.	Analysis:
	•	Helps evaluate how different levels of IT exposure affect volatility and returns
	•	Highlights which ETFs are more resilient during market stress

✅Analysis / Results
	•	QQQ experienced the largest drawdowns due to its heavy IT sector exposure.
	•	VTI had smaller declines, reflecting its broader diversification.
	•	VOO was the least affected, with minimal drawdowns.
	•	Overall, all three ETFs recovered after market dips.
	•	Notably, all ETFs were impacted by the U.S. tariff announcement last April, showing how macroeconomic events affect performance.
