# ML_Sports_Predictions
Gathering data from gambling websites API's on player lines and using historical data to predict favorable lines that beat the bookies odds.

Currently only on data gathering. 

Step 1: Go to https://api.prizepicks.com/projections, and download the most recent updated projections. Then run scraping_v4.py on projections.json. It will give you only single player options. TODO: write a script that combines files made, and then deletes repeat entries based on time and player_id. ideally, route csv to be put into separate folder. Do 1-2 times a day.

TODO: figure out a way to poll URL automatically, with a script, and make it into one large file. Can't access the PP API right now due to a 403 status error.

Step 2: create ML model.
