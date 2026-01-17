---
title: "Daily Market Return Prediction with Transformer"
collection: research
category: workingpaper
permalink: /publication/workingpaper/transformer-market-prediction
excerpt: 'We apply a Transformer encoder to forecast daily market returns using lagged returns, achieving out-of-sample R-squared improvements and Sharpe ratios exceeding 1.2. The predictability is more pronounced during recessions and elevated sentiment periods.'
date: 2026-01-16
venue: 'Working Paper'
slidesurl: ''
paperurl: 'files/transformers/202509a_HHH.pdf'
bibtexurl: 'files/transformers/reference.bib'
citation: 'Yufeng Han, Ryan Huang, and Guofu Zhou. (2025). &quot;Daily Market Return Prediction with Transformer.&quot; <i>Working Paper</i>.'
---

We apply a Transformer encoder to forecast daily market returns using lagged market returns over horizons of 5, 20, and 60 days. Both the direct model forecasts and post-machine learning forecasts exhibit significant predictive power for next-day returns, while simple averages of past returns do not. Relative to linear predictive regressions, the machine learning forecasts deliver sizable improvements in out-of-sample R-squared. A mean-variance analysis with a risk-aversion coefficient of two shows that the Transformer prediction generates an average return of 30% per annum with a Sharpe ratio of 1.3. The predictability is more pronounced in recessions and periods of elevated investor sentiment. Random Forests and feed-forward Neural Networks also yield economically meaningful, though somewhat weaker, results.
**Co-authors:** Yufeng Han (UNC Charlotte), Guofu Zhou (Washington University in St. Louis)