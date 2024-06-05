# Session 3 materials

This third and final session builds on the previous sessions to expand from scraping one page to scraping multiple pages. We start by stripping back everything we've done before to just 8 lines in [this scraper](https://github.com/paulbradshaw/pythonscraping/blob/main/session3/8lineScraperFERRET.ipynb)

## Bonus material

Once you start to run the same code on multiple pages it is worth creating a **function** that stores all the code we wrote to scrape *one* page, so that we can apply that code in a loop to a list of multiple pages. The [slides about this are in this folder](https://github.com/paulbradshaw/pythonscraping/blob/main/session3/06_creatingFunctions.pdf)

You'll find a [Python notebook in this folder that walks through the principles of writing and using functions](https://github.com/paulbradshaw/pythonscraping/blob/main/session3/04createFunctionsScraper.ipynb). You can download this, then upload it to your Google Drive, and open it as a Colab notebook to run your own copy.

Also in this folder is a [notebook which scraped multiple pages on the police regulator website](https://github.com/paulbradshaw/pythonscraping/blob/main/session3/scraperIOPC_reportsBS.ipynb) (the code no longer works as the page has since changed, but it illustrates a case study of the process). 

There are some [slides about common problems you might encounter when the techniques outlined so far don't work](https://github.com/paulbradshaw/pythonscraping/blob/main/session3/Scraping_surgery_inspect.pdf), and a [notebook outlining some approaches to fetch data that is loaded into a page dynamically](https://github.com/paulbradshaw/pythonscraping/blob/main/session3/05scrapingJSONinspector.ipynb)
