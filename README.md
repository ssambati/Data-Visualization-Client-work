# Data-Visualization-Client-work

                                                           <h2># Client Case Work Report</h2>
                                                     <h4> submitted by: Shammy Sriharsha Ambati</h4>
<h2>Client details:<h2>

Name:Charles Robertson

email:Charles.Robertson@verafin.com



Aim of this case work is to explore the data set provided by the client.

<h2>Attribution:</h2>

Data files used for the client work are taken from the link https://www.kaggle.com/san-francisco/sf-registered-business-locations-san-francisco which is hosted on kaggle.

For Grabbing the years information , I took the help of Notebook file present on the data set link https://www.kaggle.com/san-francisco/sf-registered-business-locations-san-francisco

The files which are obtained after data filtering and the Code implemented in Python using Jupyter notebook can be find in my Github Repository.

All the codes implemented in using d3.js and plotly.js are made available here. Results screenshots images in .png format are also provided here.

Code implemented in the data visualization is done with the help of ideas and examples shared in d3.js site. and plotly.js graphics library.

<h2>About the Data:</h2>

<h2>Content:</h2>

This dataset includes the locations of businesses that pay taxes to the City and County of San Francisco. Each registered business may have multiple locations and each location is a single row. The Treasurer & Tax Collector’s Office collects this data through business registration applications, account update/closure forms, and taxpayer filings. The data is collected to help enforce the Business and Tax Regulations Code including, but not limited to: Article 6, Article 12, Article 12-A, and Article 12-A-1. http://sftreasurer.org/registration

<h2>Requirement statement:</h2>

Explore the following dataset that's hosted on kaggle: https://www.kaggle.com/san-francisco/sf-registered-business-locations-san-francisco

It contains over 200,000 businesses in the San Francisco area. In addition to location information, it also has details on ownership, DBA (doing business as) names, and NAICS (North American Industry Classification System) codes.
Could the student explore the dynamics of businesses with multiple DBAs, multiple locations, and a variety of NAICS? Given that each item has a longitude and latitude field, an interactive geographic presentation would certainly be feasible.

<h2>Design:</h2>

<h2>Presentation:</h2>

The charts used for the visualization are

1.PIE CHART

2.Doughnut Chart

3. Scatter plot on Map using Longitude and Latitude information.

<h2>Implementation:</h2>

I implemented the data visualization on NAICS Codes in San Fransisco , to analyse the trends in business sectors of San Fransisco over the years.

To understand this i Visualized two charts , one chart representing the data constituting to all the years present in the data set, and the other chart considering the data between the years "2015-2020" (recent years).

I implemented a jupyter notebook file to achieve the results, and the results are saved into two seperate (.csv files) and uploaded here, code implemented in notebook has also shared here.

Notebook file -> https://github.com/ssambati/Data-Visualization-Client-work/blob/main/NAICS_Codes_Count.ipynb

Csv files -> NAICSCount_2015-2020.csv, NAICSCount.csv

HTML files:

1.BusinessCount_DonutChart.html             ->https://www.cs.mun.ca/~ssambati/DataVis/BusinessCount_DonutChart.html 

2.businessCount_2015-2020_DonutChart.html   ->https://www.cs.mun.ca/~ssambati/DataVis/businessCount_2015-2020_DonutChart.html

3.BusinessCount_PieChart.html               ->https://www.cs.mun.ca/~ssambati/DataVis/BusinessCount_DonutChart.html

4.BusinessCount_2015-2020_PieChart.html     -> https://www.cs.mun.ca/~ssambati/DataVis/BusinessCount_2015-2020_PieChart.html

5.SFmap.html

<h2>Results:</h2>

Doughnut Chart for all the years -> https://github.com/ssambati/Data-Visualization-Client-work/blob/main/NIACS_Codes_Counts_Doughnutchart.png

Doughnut Chart for  2015-2020    -> https://github.com/ssambati/Data-Visualization-Client-work/blob/main/NIACS_Codes_Counts_2015-2020_Doughnutchart.png

PIE Chart for all the years      -> https://github.com/ssambati/Data-Visualization-Client-work/blob/main/NIACS_Codes_Counts_Piechart.png

PIE Chart for 2015-2020          -> https://github.com/ssambati/Data-Visualization-Client-work/blob/main/NIACS_Codes_Counts_2015-2020_Piechart.png

Scatter Map using Latitude and Longitude ->https://github.com/ssambati/Data-Visualization-Client-work/blob/main/SFMap_Lat_Long.png

<h2>Conclusion:</h2>
Outcome:

This Client case study helped me to get the working principle of data visualization in real world applications.


Suggestions:

The Map visualization can be improved by adding more user interactions such as adding filters for selection range, sort by the street name, zoom in buttons etc.


