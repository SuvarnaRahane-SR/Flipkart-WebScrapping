# Flipkart Camera-WebScrapping

# Introduction:- 
Web scraping is the process of extracting data from various websites and parsing it. In other words, it’s a technique to extract unstructured data and store that data either in a local file or in a database. There are many ways to collect data that involve a huge amount of hard work and consume a lot of time. Web scraping can save programmers many hours.

The basic steps involved in web scraping are:

* Loading the document (HTML content)

* Parsing the document

* Extraction

* Transformation

# Used Function :-
Pandas- Here it used for stored scrapping information from website and stored it in csv file.
BeautifulSoup- Beautiful Soup is a Python web scraping library that allows us to parse and scrape HTML and XML pages.
request- The requests module is used for getting HTML content.

# Working :-
Firstly we import all modules that we have needed for further coding.
The next step is to inspect the website that you I want to scrape. Start by opening site in a browser. Go through the structure of the site and find the part of the webpage that i want to scrape.
Next, get the HTML content from a web page. We use the requests module for doing this task. We call the “get” function by passing the URL of the webpage as an argument to this function.
Parsing an HTML Page with Beautiful Soup
The prettify() function will allow us to print the HTML content in a nested form that is easy to read and will help extract the available tags that are needed.
If we want to find an element by class name we will extract the element with the class name.
Pass a tuple to the find_all() function and Beautiful Soup will find all the elements that match any item in that list. And then append that tuple to the empty list.
Then by using Pandas library scrapping information stored in DataFrame. After making DataFrame cleaning the data by using pandas library.
At the end by using Pandas library all information is saved in csv format.

# Conclusion :- Srapping of information of all cameras available on flipkart website using beautifulSoup in python programming on Jupyter Notebook.
