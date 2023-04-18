---
title: Strike Heatmap
publishDate: 2023-04-11 00:00:00
img: /assets/strikes.gif
img_alt: Heatmap of US showing strikes per state
description: |
  A brief look at strikes across the United States using data from Cornell University's ILR Labor Action Tracker. 
tags:
  - Data Science
  - Labor
  - Strikes
  - United States
---

## Motivation

This project began with a desire to apply some technical skills to the labor movement in the United States. I have been inspired by the many union wins in higher education, the union leadership reform movements in the Teamsters and the UAW, and the upcoming strike possibility at UPS with the Teamsters. 

I had seen Cornell's Labor Action Tracker (LAT) before, but I wanted to make something slightly different showing how many strikes are happening per state at a given time. This is somewhat captured in the LAT, but I believe the point of that project is to create a centralized database and show more specific information than what I was thinking of. 

## Technical Details

I chose to use Python to gather the data from the LAT and to produce my final map. I had done some previous passion projects in Python webscraping, but I had never worked with mapping in this way. This was my introduction to shapefiles, and using them in conjungtion with other data to present information. 

### Getting the Data

The first problem was extracting the data from the LAT. I had hoped to just scrape using `requests` and use pandas to parse it, but unfortunately, since this tracker updates in real-time, it is a dynamically generated web page. I reached out to the creators to try and access the data in another form like a spreadsheet, but hearing nothing, I changed tactics. I used Selenium to get a copy of the web page including all of the labor data back to 2021 when the project started. The next problem was that the data needed significant cleaning. The version of the LAT that the end user looks great. Unfortunately, the structure of the data in HTML was quite difficult to parse programatically. 