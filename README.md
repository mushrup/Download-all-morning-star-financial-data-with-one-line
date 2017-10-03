# Download-all-morning-star-financial-data-with-one-line
With the 'All_token.txt' containing all stocks of your interest,
(Seperate by /n) 
Do check the format of 'All_token.txt' in the sample file I uploaded.
Upon running 'python get_ratios.py', you will get csv files of
each stock that is there in you 'All_token.txt'

Also when any error is occuring, plz run 'clean_data.py','pre_randomforest.py','shift.py','drop.py'
and in the end you can run 'random_forest.py' to see the c-score printed.

Anyways, the structured data should look like 08469_lagged_90d.csv
