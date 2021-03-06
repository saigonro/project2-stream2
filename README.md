# Dashboards - US Births | 2000 - 2014

## Overview

### General information
This is Dan Dumitrache's second project for Code Institure bootcamp, Dublin, Ireland January 2018.  It presents graphs related to US number of births between 2000 and 2014. The data the graphs are based on is provided by the US Social Security Administration. The original data-set can be found at (https://github.com/fivethirtyeight/data/blob/master/births/US_births_2000-2014_SSA.csv). 

Git repository can be seen at (https://github.com/saigonro/project2-stream2)
Live version can be seen at (https://project2-stream2.herokuapp.com/)

### Navigation through the website
This is a single page website. To see the whole content just scroll the page.

### Animations and effects
Some of the elements of the website are animated. This was achieved using:
- dc transitionDuration

### Technologies used
This website was created using the following technologies:
- HTML
- CSS + Bootstrap(v4.0) (http://getbootstrap.com/) for styling
- JavaScript (Bootstrap core JavaScript)
- jQuery (Bootstrap requirement) (https://jquery.com/)
- dc.js (https://dc-js.github.io/dc.js/)
- crossfilter.js (https://square.github.io/crossfilter/)
- d3.js (https://d3js.org/)
- MongoDB database
- Flask (http://flask.pocoo.org/)
- Git & GitHub for version control

### Features
- Responsive (mobile first) layout/graphs
- Clear delimited sections
- The user can interact and filter the data in the charts
- Fake dimension (season) created for the pie chart
- The project includes the following type of graphs: bar chart, pie chart, row chart, and line chart
- The data is stored in a MongoDB database
- The project uses Flask to retrieve the data from the database and return it to the browser
- The charts are created by the D3.js library (https://d3js.org/)
- The data is filtered with crossfilter.js

### Remaining Features to be Implemented
- None

### Testing
- All code used on the site has been tested to ensure everything is working as expected
- Site viewed and tested in the following browsers: Google Chrome, Opera, Microsoft Edge, Mozilla Firefox, and mobile browsers

### Viewing the code locally
To view this website locally you have to download the entire repository on your machine, install all the necesary dependencies listed in the requirements.txt file, and run the dashboard.py file.

### Media and Icons
The project does not use any icon pack nor media files with exception of the logo which was designed by the author of this repository.

Logo Dashboard US births 2000 - 2014: (https://github.com/saigonro/project2-stream2/blob/master/static/images/logo-dash.png)

### Wireframes
The wireframes for this project are located in the wireframe folder in the root of the project.
