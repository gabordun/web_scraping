# web_scraping
Web scraping project with Python to scan the world's most visited websites for certain keywords, to see how 'hot' are some topics.


The aim is to count the unique mentions of Coronavirus on the world's most popular websites.

The list of the most popular websites comes from: http://www.ebizmba.com/articles/news-websites

The script scrapes this site for the URLs of the mostly visited news websites worldwide.

After getting the URLs, the script creates a parsed object for every individual websites' startsite content.

Then, according to a pre-defined 'keywords' list, the script counts the number of mentioning of all the keywords and put the numbers in an output table.

The output table contains the name & the exact URL of the corresponding website, the number of the keywords' total appearances and a proxy for the size of the site (the last in order to get some comparable measure).

Finally, in the last section the output table is saved (optionally on Google Drive). After that, the saved file is intended to import into Tableau to create a visualization of the results.
