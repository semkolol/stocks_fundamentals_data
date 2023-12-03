# Deepvalue Financial Data
**Populating the most important financial metrics for popular stocks.**
Here, you'll find data on important financial indicators, such as price-to-earnings ratios, dividend yields, but also basics, like Revenue, Net Profit, Stock-Based Compensation and Free Cashflow...

The data is structured in two different ways - one for the quarterly financials `{company-ticker}.json` and one for the annual financials `{company-ticker}-anno.json` or `{company-ticker}.json` for both in one file.

Here is an example, how the data looks like:
`tsla.json`
```
...
{
		"assets": 31872597000,
		"cash": 4954740000,
		"cashflow": -697067000,
		"capEx": 249609000,
		"ceo": "Elon R. Musk",
		"date": "2019-06-30",
		"debt": 9905847000,
		"depreciationAndAmortization": 0,
		"dividendPayoutRatio": 0,
		"dividendPerShare": 0,
		"ebit": -216924000,
		"ebitda": 417076000,
		"employees": 0,
		"eps": -0.15197167565713815,
		"fiscalYear": 2019,
		"fiscalQuarter": 2,
		"grossMargin": 0,
		"grossProfit": 921046000,
		"incomeTax": 19431000,
		"interestExpense": 171979000,
		"netIncome": -408334000,
		"netMargin": -6.430784814847246,
		"operatingIncome": -167458000,
		"operatingMargin": -0.0263726842125488,
		"researchAndDev": 323898000,
		"returnOnAssets": -0.012811444263547148,
		"returnOnCapitalEmployed": 0,
		"returnOnEquity": -0.07144460582150694,
		"returnOnInvestedCapital": 0,
		"revenue": 6349676000,
		"revenueSegments": {
			"products": {
				"0": "Model S/X",
				"1": "Model 3/Y"
			},
			"productsSold": {
				"0": 14517,
				"1": 72531
			}
		},
		"shareholderEquity": 5715393000,
		"sharesOutstanding": 2686908585,
		"stockBasedCompensation": 209863000,
		"ticker": "TSLA"
	}
...
```

Please help to complete the Dataset as complete as possible. If you want to include a company, which is not already included or correct/add additional data, please create a PR.
