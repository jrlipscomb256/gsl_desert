GSL Desert

Personal Portfolio project: analyze historical Great Salt Lake data, predict future GSL water levels

LONG TERM GOAL/IDEA:

I want to host a site to act as a portfolio display, v0 is a simple web scraper/analysis/website update 
v_inf is a fully 3D/4D time series analysis of water levels of the GSL, many forms of predictions

v0:
1. I need to build a web scraper to hit NWIS water level data for all historical data up to (today) - store it in parquet I guess
2. Analyze for trends in historical data for Exploratory Data Analysis
3. Build Data Science Module Pipeline (local python) to make it easy to add modules in the future
4. Simple regression data science module
5. Build html generator from data + regression results
6. Set up GitHub pages
7. Set up Local CRON job to update html every day/week whatever