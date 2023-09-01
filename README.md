#### Introduction
The App.ipynb notebook creates a simple web application that could be used for monitoring customer satisfaction. It had an educational purpose to learn basics of Flask app creation. 

#### Overview
The application consists of three screens:
- main page: landing page displaying options for a user
- word cloud: provides an overview of key phrases used in the review text
- all reviews by participants: enables the display of all reviews in a tabular form from the SQLite database
- add review: allows users to enter reviews which are saved in an SQLite database.

#### Tech methods
- application is built using Flask and ngrok tools
- the script has been configured to run on Google Colab 
- NLP: word cloud with basic text processing.

#### Possible next steps: 
- web scraping of forum website about a specific product
- sentiment analysis on the text
