# 👩🏻‍💻 Paycheck Protection Program: Data Analysis

The [Paycheck Protection Program](https://www.sba.gov/funding-programs/loans/covid-19-relief-options/paycheck-protection-program) distributed SBA-backed loans that supported businesses and their workforces during COVID-19. Working with the federal [data](https://www.sba.gov/funding-programs/loans/covid-19-relief-options/paycheck-protection-program/ppp-data), I conducted analysis and produced visualizations for work, school, and personal practice. I worked in R, cleaned data, and used various tools to craft visualizations.

_Note: All visualizations were made for the purpose of data exploration._

## Paycheck Protection Program (PPP) Loans: Kabbage, Inc. Online Lender

##### 🗺: R, Tidyverse, Datawrapper

<a href="https://datawrapper.dwcdn.net/JM1yu/1/">
<img src="/images/kabbage-map.png" alt="kabbage map" width="400"/>
</a>

The online lender Kabbage, Inc. is featured in the [ProPublica PPP fake farms story](https://www.propublica.org/article/ppp-farms). To show where Kabbage was lending money, I made a county-level map that shows the percentage of loans in each county that were Kabbage loans.

You can find the R code for analysis in the kabbage-counties-data folder and my visualization here:

- [Kabbage Loans Map](https://datawrapper.dwcdn.net/JM1yu/1/)

## Paycheck Protection Program (PPP) Loans: Barber Shops

##### :bar_chart:: R, Tidyverse, Datawrapper

<a href="https://datawrapper.dwcdn.net/ktM8h/1/">
<img src="/images/barber-shop.png" alt="barber shop bar chart" width="400"/>
</a>

In [Derek Willis'](https://merrill.umd.edu/directory/derek-willis)data journalism class, we used R to analyze [PPP loan data](https://www.sba.gov/funding-programs/loans/covid-19-relief-options/paycheck-protection-program/ppp-data) from a variety of states, counties, and industries. In this case, we were visualizing which states had the largest amount of loan applications to barber shops.

You can find the R code for analysis in the [barber-shop-data folder](https://github.com/jennacohen/data-viz/tree/main/barber-shop-data) and my visualizations here:

- [Undisbursed Barber Shop Loans](https://datawrapper.dwcdn.net/dyiuf/1/)
- [Percentages of Undisbused Loans](https://datawrapper.dwcdn.net/ktM8h/1/)

## Paycheck Protection Program (PPP) Loans: ggplot Analysis

##### :chart_with_upwards_trend::bar_chart:: R, Tidyverse, Tidycensus, ggplot

<a href="https://github.com/jennacohen/data-viz/blob/main/gg-plot/gg-plot-samples.Rmd">
<img src="/images/gg-plot-1.png" alt="GG Plot chart 1- loans approved by date" width="400"/>
</a>

<a href="https://github.com/jennacohen/data-viz/blob/main/gg-plot/gg-plot-samples.Rmd">
<img src="/images/gg-plot-2.png" alt="GG Plot chart 2- states with highest ppp loans per capita" width="400"/>
</a>

In [Derek Willis'](https://merrill.umd.edu/directory/derek-willis) data journalism class, we used R and ggplot to create a variety of visuals to better understand our PPP loan data.

You can find the data in the [gg-plot](https://github.com/jennacohen/data-viz/tree/main/gg-plot) folder and my markdown file containing the ggplot code here:

- [ggplot Analysis](https://github.com/jennacohen/data-viz/blob/main/gg-plot/gg-plot-samples.Rmd)
