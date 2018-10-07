# visualize_yosemite

Project Proposal

Topic: Yosemite National Park

Requirements of the Project:
Your visualization must include a Python Flask powered RESTful API, HTML/CSS, JavaScript, and at least one database (MySQL, MongoDB, SQLite, etc.)
Your project should fall into one of the below four tracks:
A custom "creative" D3.js project (i.e. non-standard graph or chart)
A combination of Web Scraping and Leaflet or Plotly
A dashboard page with multiple charts all updating from the same data
A "thick" server that performs multiple manipulations on data in a database prior to visualization (must be approved)
Your project should include at least one JS library that we did not cover.
Your project must be powered by a dataset with at least 100 records.
Your project must include some level of user-driven interaction (e.g. menus, dropdowns, textboxes, etc.)
Your final visualization should ideally include at least three views

Overview: 
Hiking and National parks have been trending in the last few years therefore we want to gain an insight on one of the most popular national parks in the country, Yosemite. 

Data Resources:
https://weather.com/weather/today/l/USCA1269:1:US or OpenWeatherMap API - weather for yosemite
https://www.nps.gov/yose/learn/news/newsreleases.htm - Recent Yosemite News
https://www.hikespeak.com/sierras/yosemite/ - Trail head coordinates
https://irma.nps.gov/Stats/SSRSReports/Park%20Specific%20Reports/Traffic%20Counts?Park=YOSE - Amount of visitors dataset for different regions of Yosemite
https://www.nps.gov/yose/index.htm - Yosemite website for scraping
https://irma.nps.gov/Stats/SSRSReports/Park%20Specific%20Reports/Annual%20Park%20Recreation%20Visitation%20(1904%20-%20Last%20Calendar%20Year)?Park=YOSE - annual visitors for Yosemite
https://irma.nps.gov/Stats/SSRSReports/Park%20Specific%20Reports/Annual%20Park%20Recreation%20Visitation%20(1904%20-%20Last%20Calendar%20Year)?Park=YOSE - economic benefit over time for Yosemite
https://www.yosemitehikes.com/hikes.htm - hiking trails

Outline:
Index page
Interactive map of Yosemite
Using Leafly and mapbox to plot map of Yosemite
Create a polygon layer of 7 regions of Yosemite (we will reference visitor data from 1986-present for these regions)
Create a marker layer for trail head markers
Web scrape to display current weather and recent news
Use JQuery to cycle 4 different Yosemite backgrounds
Navbar
Plots/Visuals page(s)
Use Plotly to show visitor data for 7 different regions last 30 years
Use rolling averages to show slider of datasets
Use mongoDB to push data
Possibly use event handlers to switch between 7 regions
Also plot to show visitor data for all of Yosemite in the last 100 years
Plot economic benefits
Hiking Trail table
Filter table of hikes 
Scrape from yosemite hikes


