# Some Datasets for Teaching

## Obtained via Licensing Agreement

__NYT articles, 1905-1925__: I have all articles from the New York Times from thsi date range in XML format. The terms of my license allow me to make subsets and share term frequency tables of the full text.  

## Web-Scraped Collections, Mined from eBooks, etc.

__Oxford English Dictionary Data__: At some point, I scraped the OED's work list and year of first use for like 181k terms. As I undesrtand it, the information in this data can't be copyrighted, but I may have violated the terms of the site when I collected the data. 

__NYT Op-Eds__: Metadata data and full text for op ed columns, 01-01-2017 through 11-09-2018. Metadata includes URLs for HTML versions of op-eds and predicted gender of columnists using the gender package in R. (Note: Please do not use these data without first reading the caveats at https://github.com/lmullen/gender)

__Books of Oz Corpus__: I made a corpus to replicate part of José Nilo G. Binongo's "Who Wrote the 15th Book of Oz? An Application of Multivariate Analysis to Authorship Attribution" for a DA 101 assignment. MY version is actually more complete than Binongo's, as it includes the text of four of Ruth Plumley Thompson’s Oz books--_The Yellow Knight of Oz_, _The Purple Prince of Oz_, _Ojo in Oz_, and _Speedy in Oz_--that Binongo was unable to obtain (due to their being out of print at the time).

__Calvin and Hobbes Sunday Comics__: Web-scrape of 528 _Calvin and Hobbes_ Sunday comic strips. The site idnexes them by the date on which they appeared, so I just scraped every Sunday between November 18, 1985 and December 31, 1995, but that includes several blocks of dates when Watterson was on sabbatical and newspapers were running repeats of old comics. Dates for these repeats are described here: https://www.reddit.com/r/calvinandhobbes/comments/bthbjv/how_many_strips_are_there_a_response_to_a/

__BBC World News America__: 79 episodes of BBC World News America, 01-02-2019 through 05-01-2019, scraped from archive.org. I was going to do a full year of these for an assignment, but I decided to cancel the assignment, so I never finished the scrape. 

__TOC Fiction from Gutenberg__: Approximately 380 works of fiction (some multi-volume), mostly late 19th and early 20th-century, used as comparison sample for a paper on Willa Cather.

## Publicly Available

__Collections as Data @ Pitt__: Digitized objects and metadata from numerous collections at Pitt, as well as "extension layers" of things like OCR text and geotags. See https://cadatpitt.github.io/project/#collections for a description of the included collections and https://github.com/CaDatPitt/data-layers for the data. 

__New York Times Obituaries__: Obituaries scraped from https://archive.nytimes.com/www.nytimes.com/learning/general/onthisday/. On each day of the year, The New York Times featured an obituary of someone born on that day and replaced the HTML for that day the next year, so there are 366 obituaries in total. This is the dataset I used for https://programminghistorian.org/en/lessons/analyzing-documents-with-tfidf. 
