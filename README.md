# Mission to Mars - Web Scrapping

The goal of this project is to build a web appliation that scrapes various websites to get data related to Mars and displays the information in a single HTML page.

## Mission_to_Mars_HW Jupyter notebook 

The notebook is mostly used to make sure that the scraping of the data works.

It's divided in four sections:
- NASA Mars News
- JPL Mars Space Images
- Mars Facts
- Mars Hemisphere

## Scrape_mars.py

Once the notebook functionality is finished. This script is used to hold each section as a function in order to return the data to app.py.

## App.py

This code calls scrape_mars's functions, inserts the data into MongoDB and index.html.

## Index.html

HTML code to visualize all the data.
