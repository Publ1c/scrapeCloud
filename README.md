# scrapeCloud
Scrape a site and build a WordCloud off of it

Uses BeautifulSoup to scrape a site to create a string. 
String is stripped of punctuation, uninteresting words and then analyzed for frequency resulting in a word to frequency dictionary.
The dictionary is fed through the wordcount function to create a word cloud.

Example from Plato's Republic pulled from Project Gutenberg:
python3 scrapeCloud https://www.gutenberg.org/files/55201/55201-h/55201-h.htm

