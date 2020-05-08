# Web-Scraping-on-nytimes.com

What is Web-Scraping ??

It's the process of extracting information from a web page by taking advantage of patterns in the web page's underlying code. Let's start looking for these patterns!

Examining the New York Times article

On July, 2017, the New york Times updated an opinion article called Trump lies. Because this is a newspaper, the information was (of course) published as a block of text. This is a great format for human consumption, but it can't easily be understood by a computer.

When converting this into a dataset, you can think of each lie as a "record" with four fields:

1. The date of the lie.
2. The lie itself (as a quotation).
3. The writer's brief explanation of why it was a lie.
4. The URL of an article claim that it was a lie.

Examining the HTML

To view the HTML code that generates a web page, you right click on it and select "View Page Source" in Chrome or Firefox.

Reading the web page into Python

The first thing we need to do is to read the HTML for this article into Python, which we'll do using the requests library. (If you don't have it, you can pip install requests from the command line.)

Parsing the HTML using Beautiful Soup.

We're going to parse the HTML using the Beautiful Soup 4 library, which is a popular Python library for web scraping. (If you don't have it, you can pip install beautifulsoup4 from the command line.)

1. Extracting the date
2. Extracting the lieExtracting the lie
3. Extracting the explanation
4. Extracting the URL

