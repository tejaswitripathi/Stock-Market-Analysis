# Stock Market Analysis
 Use Microsoft Excel to analyze the correlation between the growth rate of the Dow Jones Industrial Average and the unemployment rate in order to assess the hypothesis that the stock market growth rate is not a reliable procyclic economic indicator.

Obtain 5-year data sets of the unemployment rate and DJIA, preferably during periods of relative economic stability in order to avoid outliers. Calculate the coefficient of correlation for each data set, then find the overall average coefficient of correlation. Because the unemployment rate is an anticyclic economic indicator, and assuming that the null hypothesis is true, the resulting coefficient of correlation should be close to 0. If the null hypothesis is false, then the resulting coefficient of correlation should be -1.

Obtained 3 data sets: from 2012-2017, 1992-1997, and 1984-1989. Performed 3 separate hypothesis tests for correlation, for each data set.

2012-2017:
Null Hypothesis: there is no correlation between unemployment rate and stock market growth rate.
Alternative Hypothesis: there is a correlation between unemployment rate and stock market growth rate.
Significance level = 90% (alpha-value = +-0.05)
r = 0.076, t = 0.580 with 58 degrees of freedom.
t > 0.05, so we will retain the null hypothesis. There is insufficient evidence to conclude that there was a correlation between unemployment rate and stock market growth rate between 2012-2017.

1992-1997:
Null Hypothesis: there is no correlation between unemployment rate and stock market growth rate.
Alternative Hypothesis: there is a correlation between unemployment rate and stock market growth rate.
Significance level = 90% (alpha-value = +-0.05)
r = -0.320, t = -2.550 with 57 degrees of freedom.
t < -0.05, so we will reject the null hypothesis. There is sufficient evidence to conclude that there was a correlation between unemployment rate and stock market growth rate between 1992-1997.

1984-1989:
Null Hypothesis: there is no correlation between unemployment rate and stock market growth rate.
Alternative Hypothesis: there is a correlation between unemployment rate and stock market growth rate.
Significance level = 90% (alpha-value = +-0.05)
r = 0.061, t = 0.465 with 58 degrees of freedom.
t > 0.05, so we will retain the null hypothesis. There is insufficient evidence to conclude that there was a correlation between unemployment rate and stock market growth rate between 1984-1989.

The result of our tests is inconclusive overall. We have seen a negative correlation in one out of three data sets, and more testing would be needed to form a conclusion.
