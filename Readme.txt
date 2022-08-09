This document explores a dataset containing revenue,budget and users rating for approximately 11000 movies(TMDb).
The original data has 10866 entries and 21 columns.

I removed the columns I am not interested in and tailored the ones I'm interested in using drop column function in pandas.
I did some other data wrangling activities which includes spliting the genres column into seperate genres,used a flat divisor(10)
to group the year to decades and use a flat divisor(1000000) to convert revenue_adj and budget_adj into Million.

I checked for movie budget in million distribution using Histogram,did a value count of each genre category(Univariate exploration),checked for 
average popularity by genre (bivariate exploration) and Visualized the relationship between Genre,Decade and Revenue.




