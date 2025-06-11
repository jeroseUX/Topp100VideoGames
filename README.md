# Top100VideoGames
The following is a time-series analysis of the top 100 video games each year from 2015-2024

This solo project utilizes a custom-created dataset containing the top 100 rated video games of each year for the past 10 years, based on Metacritic scores. The analysis aims to forecast future trends in critic and user scores, as well as identify patterns in game releases.

Libraries Used:

xgboost
sklearn
prophet model
seaborn
numpy
pandas
statmodels
matplotlib

Limitations:

Category Definitions: The dataset lacks clear definitions for categories such as "Indie" or "Action", which may impact the accuracy of analysis.
Review Quantity: Certain games have limited review sets, potentially affecting the reliability of analysis results.
Microtransaction Effects: Reviews from microtransactions may be anomalous, leading to biased analysis.

Conclusions:

The average yearly critic and user scores are forecasted to decrease in 2024 compared to previous years.
Non-Indie games are expected to have higher critic and user scores than Indie games.
Games are predicted to peak in production during the third quarter of the year, with September being the month with the most releases.
User scores follow a similar trend to critic scores but are generally lower.
Note: This analysis relies on a custom dataset, which may not be representative of the broader gaming industry. Results should be interpreted with caution.
