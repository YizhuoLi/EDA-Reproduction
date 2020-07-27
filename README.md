# EDA-Reproduction

This is a recurrence of the results of the conversion from R to Python. 
[Original author](https://www.kaggle.com/philippsp/exploratory-analysis-zillow) uses R to complete the analysis, here I uses Python.

There may be slight differences from the original results, partly because the data is the second edition.

There are some methods, such as geom_smooth, I have not found a more suitable alternative in Python. 
And [ggplot for python](https://github.com/yhat/ggpy) has not been updated for 4 years. 
So for longer-term adaptation, I did not use ggplot for drawing here. 
(Now there have been some problems, for example, because of the changes in Pandas, from ggplot import * will report an error. 
To solve this, the Pandas package needs to be manually modified). 
When encountering such graphics, I will try to find alternatives. If you know of a better plan, please let me know.

Have fun.
