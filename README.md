# surfs_up
Using Python, SQLite, SQLAlchemy, and Flask to analyze and visualize climate data as I prepare to open a surf shop.

# Overview of Project
&nbsp;&nbsp;&nbsp;After visiting Oahu Hawaii, I decided to make a plan to live there.  Opening up a Surf 'n Shake shop sounds like the ideal business.  Doing so would require investors.  After talking to a famous local surfer, it becomes apparent that I should do a weather analysis.  Doing an analysis on the weather will help me determine if I should open the Surf 'n Shake shop in June or December.

### Resources
&nbsp;&nbsp;&nbsp;* Data Source: hawaii.sqlite
<br />
&nbsp;&nbsp;&nbsp;* Software: Python 3.9.7 64-bit, Jupyter Notebook 6.4.5, SQLite, flask

## Results
&nbsp;&nbsp;&nbsp;I decided I needed to perform queries on the temperature, for the months of June and December.  The thought process behind this was to perform a query, convert the query to a list, and then convert that list into a data frame using pandas. After extracting the data, I did a .describe() function to generate descriptive statistics.
<br />
<br />
&nbsp;&nbsp;&nbsp;Temperature Summary Statistics:
<br />
<p float="left">
  <img src="https://github.com/LaszloCravensworth/surfs_up/blob/main/Resources/June_temp.png" width="300" />
  <img src="https://github.com/LaszloCravensworth/surfs_up/blob/main/Resources/Dec_temp.png" width="300" /> 
</p>
<br />


## Summary
&nbsp;&nbsp;&nbsp;The climate year round seemed to be ideal whether in June or December.  June had a slight edge on warmer weather.  Warmer weather would likely result in more shakes and surf boards being sold.  Two more queries were needed though.  I decided to generate descriptive statistics on the precipitation for June and December.  The results are as follows:
<br />
<br />
&nbsp;&nbsp;&nbsp;Precipitation Summary Statistics:
<br />
<p float="left">
  <img src="https://github.com/LaszloCravensworth/surfs_up/blob/main/Resources/June_prcp.png" width="300" />
  <img src="https://github.com/LaszloCravensworth/surfs_up/blob/main/Resources/Dec_prcp.png" width="300" /> 
</p>
<br />
&nbsp;&nbsp;&nbsp;It would appear that June holds a slight edge over December to open up the Surf 'n Shake shop.
<br />
<br />
  * June average temperature is higher than December.
<br />
  * June average rainfall is lower than December.
<br />
  * June has a higher maximum temperature so hotter days are more likely to occur than in December.
