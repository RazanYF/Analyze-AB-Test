# Analyze-AB-Test
On this I will study A/B test to decide whether the company run new page or stay on the old page.

we have 2 dataset to help me for the analysis:
* ab_data has 5 colmns: user_id, timestamp, group, landing_page and converted.
* countries has 2 colmns: user_id and country.
you can find and see more info about the data and the result of the code from html file.

# Installation
you will need to download both the data (.csv) and python code (.ipynb) place them in same folder. this will prevent error not finding file.
If you are working locally and get an error about "No module name", then open a terminal and try installing the missing module using pip install <module_name> (don't
include the "<" or ">" or any words following a period in the module name).

# Resource
there some resource help me on making the A/B test:
* https://pandas.pydata.org/pandas-docs/stable/reference/index.html#api
* https://www.statsmodels.org/stable/generated/statsmodels.stats.proportion.proportions_ztest.html
