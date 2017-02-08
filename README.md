# Word Calculator Application

## This is a Flask Application that calculates word-frequency pairs based on the text from a given URL.
## https://flask-wordcount.herokuapp.com/

### Tasks

1. Set up a local development environment and then deploy both a staging and a production environment on Heroku.
2. Set up a PostgreSQL database along with SQLAlchemy and Alembic to handle migrations.
3. Add in the back-end logic to scrape a webpage 
4. Process the word counts from the scraped webpage using the requests, BeautifulSoup, and Natural Language Toolkit (NLTK) libraries.
5. Implement a Redis task queue to handle the text processing
6. Implement Angular on the front-end to continously poll the back-end to see if a request is done processing in the queue