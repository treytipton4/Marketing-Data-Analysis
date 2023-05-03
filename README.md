# Marketing-Data-Analysis

In this project we carried out an entire Bayesian modeling process to determine the link between customer characteristics and whether a customer accepted the company's ad campaigns.

The data comes from a kaggle Data Card [shown here](https://www.kaggle.com/datasets/jackdaoud/marketing-data) and is publicly available on [github](https://github.com/nailson/ifood-data-business-analyst-test). It is also available using the fuzzybunnies R Package (called "marketing_data").

We used stan to fit a binomial bayesian model with the response variable being a binary variable stating whether a customer accepted the campaign or not. The predictors were both quantitative and categorical and included customer characteristics such as income, education, marital status, etc. The data contains multiple rows per person, as the company release more than one campaign to each customer.

Here is the HTML of the entire modeling process: [Marketing Bayesian Analysis](https://htmlpreview.github.io/?https://github.com/treytipton4/Marketing-Data-Analysis/blob/master/marketing-bayesian-analysis.html)

Project by Trey Tipton and Brent Gin