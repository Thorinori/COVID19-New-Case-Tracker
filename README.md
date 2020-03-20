# COVID19-New-Case-Tracker
Using Plotly, Pandas, and data from https://github.com/CSSEGISandData/COVID-19 to generate a map of new COVID-19 cases within a timeframe


To run locally:
1) Install Plotly (https://plot.ly/python/getting-started/ , also follow the Jupyter Notebook support section)
2) Install Pandas (https://pandas.pydata.org/getting_started.html)
3) Install Jupyter (https://jupyter.org/install)
4) Run Jupyter wherever you put Tracker.ipynb

To run online: 
1) Go to https://notebooks.azure.com/Thorinori/projects/covid-19-new-case-tracker
2) Clone the Azure Repo 
2) Press "Run on Free Compute"

Shared Info:
To generate a map for a timeframe, use generate_new_map(start, end) where start and end are strings formatted "1/22/20" (mm/dd/yy).

If you want to see the total number of cases instead of the new cases within a period of time, set start and end to the same date.

Example Output:

![Example Map](https://github.com/Thorinori/COVID19-New-Case-Tracker/blob/master/newplot.png)
