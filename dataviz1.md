# Data Visualization: Visualizing Government Debt
October 31, 2021

## I. Working with Web-Based Visualization Tools and Data
General government debt-to-GDP ratio measures the gross debt of the general government as a percentage of GDP. It is a key indicator for the sustainability of government finance. Debt is calculated as the sum of the following liability categories (as applicable): currency and deposits; debt securities, loans; insurance, pensions and standardised guarantee schemes, and other accounts payable. Changes in government debt over time primarily reflect the impact of past government deficits.

<iframe src="https://data.oecd.org/chart/6vtc" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6vtc" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

(Source: [OECD Data: General government debt](https://data.oecd.org/gga/general-government-debt.htm))

## II. OECD Government Debt: The Debt-to-GDP Ratio

The grid of line charts let us visualize the Debt-to-GDP ratio across a number of countries and years. This method is akin to [sparklines](https://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0001OR), which we can easily present the data that need to move within complex multivariate spaces.

<div class="flourish-embed flourish-chart" data-src="visualisation/7691541"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## III. OECD Government Debt:

In this part, we were asked to create a new data visualization using the same data as in the previous one. I chose to use a bubble map as a redesign. A bubble map uses circles of different size to display a numeric value per geographic coordinate. It is nice to use when you have a list of geographic coordinates (i.e., latitude and longitude) and a numeric varaible that can be represented by the bubble size.

To let the data fit into a bubble map format, I pre-processed the data in Excel by averaging the debt-to-GDP ratio over time for each country. Therefore, we would have a single numerial value, an average debt-to-GDP ratio, for each country. The intention of the redesign is to demonstrate the debt-to-GDP ratio worldwide geographically, allowing the audience to match the context with the bubble size without creating a long pause. The interactive plot also allows audience to select a bubble or region, zoom in, and search for more detailed information.

<div class="flourish-embed flourish-map" data-src="visualisation/7692104"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### References
1. Berinato, S. (2019). Good charts workbook: tips, tools, and exercises for making better data visualizations. Chapter 1: Controlling Color. Boston, MA: Harvard Business Review Press.
2. Berinato, S. (2019). Good charts workbook: tips, tools, and exercises for making better data visualizations. Chapter 2: Crafting for Clarity. Boston, MA: Harvard Business Review Press.
