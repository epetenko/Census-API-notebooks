# Census-API-notebooks
Data notebooks to automatically process Census data and spit out clean datasets.

## What this is

These Pandas notebooks are designed to automatically take Census API data and create our preferred format at NJAM for town and county datasets. I've also included my race and ethnicity notebook, which is not API-based, so you will have to download the required data from the Census website before you begin. Figured it would still save a lot of time.

## What's here:

- Median age
- Median income
- Median commute times
- Median home values
- Population
- Race and ethnicity data in two forms: All of the data (including raw totals), or just the percentages to save on the number of columns and complexity.

## Final result:

Each of the results contains the following:

- Both towns and county values
- the FIPS code for the geography 
- Latest value and its margin of error
- The margin of error's percent of the value (for filtering out high MOEs)
- Same information for the previous year of data
- The current and previous values for NJ
- The current and previous values for the US
- The percent change at the local, NJ and US levels

In the case of monetary values, there are also inflation adjusted and non-inflation adjusted values for the previous years.
