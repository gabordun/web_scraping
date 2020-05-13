# web_scraping
A web scraping project with Python (i.e. beautiful soap) to scan the world's most visited websites for certain keywords, to see how 'hot' are some topics.

The aim is to count the unique mentions of Coronavirus (via a pre-defined list of keywords) on the world's most popular websites.

The list of the most popular websites comes from: http://www.ebizmba.com/articles/news-websites

The script scrapes this site for the URLs of the news websites.

After getting the URLs, the script creates a parsed object for every individual websites' startsite content.

Then, according to a pre-defined 'keywords' list, the script counts the number of mentioning of all the keywords and put the results in an output table.

The output table contains the name & the URL of the corresponding website, the number of the keywords' total appearances and a proxy for the size of the site (the last in order to get some comparable measure, it counts the 'a' fields inside the html body of the corresponding website).

Finally, in the last section the output table is saved (optionally on Google Drive). After that, the saved file is imported into Tableau to create a visualization of the results.
