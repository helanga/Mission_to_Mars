# Mission_to_Mars
HTML Web scraping on Mars data to create a Flask web application using Python and MongoDB

## Overview
This project consisted on a Python script to scrape text and images from various websites that talked about Mission to Mars. Then, I created a Flask web application with a rendered HTML template designed using Bootstrap to display all the data in a central location without having to gather it manually. The data scraped and displayed was stored in a non-relational Mongo database. Additionally, I was able to connect the scraping script so that each time a button was clicked, the scraping occured once again, the database got updated, and new data was displayed. This button only works under the condition that these webpages don't change their HTML components I used for scraping. And lastly, by using Bootstrap's grid system I was able to create a responsive web app that could accomodate to any device people view it from.

Resources
•	Web pages scraped:
o	https://data-class-mars.s3.amazonaws.com/Mars/index.html
o	https://spaceimages-mars.com
o	https://galaxyfacts-mars.com
o	https://marshemispheres.com/
•	Software:
o	Python
o	Jupyter Notebook
o	Pandas, BeautifulSoup, Splinter, ChromeDriverManager, Flask, PyMongo
o	MongoDB
o	HTML5
o	Bootstrap 3
