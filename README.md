# Web scrapper and nlp media bias classifier

Newspaper Scraper, which uses advanced natural language processing techniques, sentiment analysis, and web scraping to extract summaries, metadata, and levels of polarity and subjectivity from articles on the New York Times' technology section.

Throughout my code, I have placed detailed comments explaining what each method does, its function, and some explanations on complex lines of code. 

Classes 

* main.py: main entry point for the application, this is the class to call when running the application.
* news_extract.py: using beautiful soup this is a web scraper to pull all HTML from a given newspaper web page.
* news_nlp.py: class uses natural language processing to process the textual information given and indicate if any bias is found.
* news_scrape.py: Fundamentally the same as the news_extract.py class although this iteration uses newspaper and article to pull and host the information gained.
* nlp_demo.py: A full implementation of the natural language proccessing functionality.

Dependencies
In order to run and modify this program on your personal machine, you will need to have installed the following packages.

time, random - These packages should be built-in into any version of Python 3 and above.

textblob - Package Install: pip install textblob

newspaper3k - Package Install: pip install newspaper3k

requests - Package Install: pip install requests

bs4 (BeautifulSoup) - Package Install: pip install bs4

It is best practice to use virtualenv within python to host all dependancies.
