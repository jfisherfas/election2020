# Election 2020

Some tools to model the election and make maps on the Congressional
level.  You should be familiar with Python and R.

`fetch.py` Download the US Census American Community Survey 1-Year
data (2005-2019) into a single file by congressional district.  The
districts are coded in a text field which is column 1.  It is best
if you get a developer ID and add it to the end of the string in this
file on your copy but it is not necessary to get this data.

You can find out more here: [How to download all congressional districts from
the census API](https://www2.census.gov/data/api-documentation/how-to-download-all-congressional-districts-from-the-census-api.pdf?)

`join.py` An example of how to create a standard format of congressional
district names that can be used by the Pandas `join` function.

`house.R` Extract house results from R data set by congressional
district for any year and state.  If you have the `politicaldata` and
`tidyverse` and `optparse` libraries, this file will allow
extracts of a congressional election for one year either for a state
or for all states.

`presidential.R` Extract presidential results from R data set by
congressional district for any year and state.  Same as the House of Representatives
example above.

`congressionalmap.Rmd` R notebook to look at maps on the congressional
district level.

Maps are available by individual or groups of states

![2016 Presidential Race](https://github.com/sneakerfish/election2020/blob/main/images/2016.presidential.png)

![2018 House Race](https://github.com/sneakerfish/election2020/blob/main/images/2018.house.png)
