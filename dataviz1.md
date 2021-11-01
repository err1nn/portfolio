# Data Visualization: Visualizing Government Debt
October 31, 2021

## I. Working with Web-Based Visualization Tools and Data
General government debt-to-GDP ratio measures the gross debt of the general government as a percentage of GDP. It is a key indicator for the sustainability of government finance. Debt is calculated as the sum of the following liability categories (as applicable): currency and deposits; debt securities, loans; insurance, pensions and standardised guarantee schemes, and other accounts payable. Changes in government debt over time primarily reflect the impact of past government deficits.

<iframe src="https://data.oecd.org/chart/6vtc" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6vtc" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

(Source: [OECD Data: General government debt](https://data.oecd.org/gga/general-government-debt.htm))

## II. OECD Government Debt: Using Grid of Line Charts

The grid of line charts allows us to visualize the Debt-to-GDP ratio across a number of countries and years. This method is akin to [sparklines](https://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0001OR), which we can easily present the data that need to move within complex multivariate spaces.

<div class="flourish-embed flourish-chart" data-src="visualisation/7691541"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## III. OECD Government Debt: Using Bubble Map Chart

In this part, we were asked to create a new data visualization using the same data as in the previous one. I chose to use a bubble map as a redesign. A bubble map uses circles of different size to display a numeric value per geographic coordinate. It is nice to use when you have a list of geographic coordinates (i.e., latitude and longitude) and a numeric varaible that can be represented by the bubble size.

To let the data fit into a bubble map format, I pre-processed the data in Excel by averaging the debt-to-GDP ratio over time for each country. Therefore, we would have a single numerical value, an average debt-to-GDP ratio, for each country.

<div class="flourish-embed flourish-map" data-src="visualisation/7692104"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Discussion
The gird of line charts provides the big picture and the concise details to the audience simultaneously. It is a good approach especially for large and complicated information that need to be displayed in one chart; the chart gives valuables cues for trends and comparison to the audience. However, lack of sufficient contexts or backgroundn information, one would easily get lost as seeing the graph.

The intention of the redesign is to demonstrate the debt-to-GDP ratio worldwide geographically, allowing the audience to match the context with the bubble size without creating a long pause and eye travel. The interactive plot also allows audience to select a bubble or region, zoom in, and search for more detailed information. But the tradeoff is that we sacrificed the trend of ratio changes over time.

Overall, I like both graphs since they do not have clutter or redundancy that has been discussed in class and the textbook. They also capture and showcase the most important information, and are well-presented to the audience.
