# Financial Analysis Project
Analyzing financial trends, market shifts, regional profitability, and developing a ML model for profit forecasting.

__Business task:__ assess the financial health of a hardware company.

__Project goals:__
* research the financial area:
  - explore how revenue, profit, and margin have changed over time
  - investigate if the market has shifted
  - find out what regions are most profitable
* test a hypothesis about the effect of manufacturing costs on profit margins
* build a ML model for profit predictions
* create a dashboard for the company

__Metrics and ratios__ used for the financial health's evaluation:
* gross revenue
* gross revenue growth rate
* net revenue
* net revenue growth rate
* gross profit
* gross margin
* segment (geographic) margin

__Tools used:__
* Segment margin analysis: for calculation of margins per geographic segment (region)
* Mann-Whitney U test: to test the hypothesis
* Spearman's Rank Correlation: for correlation analysis of manufacturing costs and profit margins
* Linear least-squares regression: for regression analysis to evaluate the linear relationship between manufacturing costs and profit margins
* One-Hot encoding: to encode categorical variables for machine learning (ML)
* Clipping: to transform outliers for ML
* PowerTransformer with Yeo-Johnson transformation: to scale numerical variables for ML
* Linear Regression and Random Forest Regressor algorithms: for profit prediction

__Data description:__
* A database in SQLite format, consisting of 6 tables.
* The company has restricted the ability to load the whole database to CSV. \
  It is not allowed to select all rows from datasets or merge/ group/ manipulate in Python. \
  Only the connection to the database itself can be used.
* Research questions and data manipulation should be done by using SQL queries.
* Only visualization and statistics should be in Python.

_Note:_ The database 'atliq_db.sqlite3' is not added to this repository due to its size & upload limitations. \
It can be downloaded from Google Drive via [this link](https://drive.google.com/file/d/1sGwyFlyBX1zBHrtf3c69nrTejJGohMHU/view?usp=sharing).

__Results:__
* Determined key financial indicators to assess the company's financial health.
* Explored regional trends, and identified a shift in market dynamics.
* Evaluated profitability of the regions.
* Annual cost structure examination showed that profit-to-revenue ratios stay stable across years and regions.
* Segment margin analysis detected that faster manufacturing cost growth than net revenue led to a gross margin decline across all regions.
* Hypothesis testing confirmed a negative impact of rising manufacturing costs on gross profit margin.
* Developed a highly accurate ML model for profit forecasting.
* Created 2 dashboards: Financial Analysis and Regional Trends.
* Prepared a presentation for the company.
* Provided recommendations on:
  - growth strategy
  - cost and profit optimization
  - financial model adjustments
* Offered tailored recommendations for each region.

__Financial analysis dashboard URL:__ [tableau.com/galina.makarchuk/financial_analysis](https://public.tableau.com/views/FinancialAnalysis_17353392284410/FinancialAnalysis?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) \
__Regional trends dashboard URL:__ [tableau.com/galina.makarchuk/regional_trends](https://public.tableau.com/views/FinancialAnalysis_17353392284410/RegionalTrends?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) \
__Presentation URL:__ [tableau.com/galina.makarchuk/presentation](https://public.tableau.com/views/FinancialAnalysis_17353392284410/Presentation?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<img width="1693" alt="Screenshot 2025-01-27 at 12 01 19" src="https://github.com/user-attachments/assets/2ddcd29a-360b-4414-8f3c-083ceb8cff29" />

<img width="1688" alt="Screenshot 2025-01-27 at 11 55 40" src="https://github.com/user-attachments/assets/05920c46-94ec-4469-a43e-dbe227eb41ad" />
