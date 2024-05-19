# <h1 align="center">Adventure Works Dashboard</h1>
![AdventureWorks](https://github.com/nmowens95/Adventure-Works/assets/126295718/5939c368-41b7-45c3-9a1c-48dae7919ec7)

## <h1 align="center">The Why</h1>
Adventure works is a bike company that needed help to gain a better understanding as to what was going on within the bussiness. Thus our goal with this report was to help provide insights for our stakeholders to things such as:
- Provide insight into key KPI's
- Compare regional performance
- Analyze product level trends
- Identify high-value customers

## <h1 align="center">Shortcuts</h1>
| 🚀 | Topic + URL           | 
| - |:-------------|
| 1 | [Data Model](#data-model) | 
| 2 | [Executive Dashboard](#executive-dashboard)  | 
| 3 | [Regional Map](#regional-map)  |
| 4 | [Product Detail](#product-detail)  | 
| 5 | [Customer Detail](#customer-detail)  | 
| 6 | [Raw Data](https://github.com/nmowens95/Adventure-Works/tree/main/AdventureWorks%20Raw%20Data)  |

## <h1 align="center" id="data-model">Data Model</h1>
![ERD adventure works](https://github.com/nmowens95/Adventure-Works/assets/126295718/34fedb6d-d290-42b4-aacc-be75baed3fad)
- Follows a Star and Snowflake Schema, with a representation of downstream connections.
- A seperate measures table was created using DAX calculations for the analysis.
- Price Adjustment and Product Metric Selection were created from Numeric Range and Field model parameters.

## <h1 align="center" id="executive-dashboard">Executive Dashboard</h1>
![executive page](https://github.com/nmowens95/Adventure-Works/assets/126295718/e37c313c-d498-43a8-bfaa-4c74d0ad6316)
- Created for an executive level of detail with quick KPI cards at the top
- Working down we have a revenue trend over time as well as a category bar chart
- We used a matrix to outline a quick show of top products with some rule visuals
- At the bottom we used some basic metrics to outline if goals are being hit and some more quick KPI's

Our Goal here is for a high level stakeholder to come in and be able to quick understand whats going on from a high level. We're able to outline major KPI's and filter quickly to find insight that we may need.

## <h1 align="center" id="regional-map">Regional Map</h1>
![Regional Map](https://github.com/nmowens95/Adventure-Works/assets/126295718/90500c26-8a1b-4d26-bb0c-26bb50891f88)
- We're able to filter by region and compare our total orders
- The top filters will allow for specific granularity of country, with options of one, or many

## <h1 align="center" id="product-detail">Product Detail</h1>
![product detail](https://github.com/nmowens95/Adventure-Works/assets/126295718/d7d27bf3-4bcb-478a-9005-f8da6eb09e8a)
- We can use this page to quickly draw insights into specific products
- There is the ability to filter by profit for quick analysis of profit
- Our area chart gives us insight into our major concerns for the company and quickly tells the story over time

## <h1 align="center" id="customer-detail">Customer Detail</h1>
![customer detail](https://github.com/nmowens95/Adventure-Works/assets/126295718/6ec9dac3-41db-4c0d-9f44-62c36ebbfdf6)
- Able to dive deep into our customers specifically outlining key KPI's for our unique customers and the revenue the bring in on average
- Used a line chart to show our trend over time and provide donut charts, a table and quick cards to outline the most relevant information

## <h1 align="center">What I Learned</h1>
- It's key to understand which stakeholder at what level will need to understand a specific level of granularity
- I got to work with a lot of different DAX expressions to create time series analysis, profit adjustment and much more
- Got practice with data modeling, using power query and designing a basic mobile view

## <h1 align="center">Personal Insight</h1>
- The United States is the largest contributor to orders, next is Australia. There should be a greater empasis on marketing in these regions in order to push further sales.
- Over time as the return rate has increased, though this seems alarming, it is steady in percentage along with total increase of orders. Thus it isn't something to be overly worried about.
