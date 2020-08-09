# CrawlerSyllabicDivision
What is it?
------------
This script collects all words with syllabic division available on the [Portal da Língua Portuguesa](http://www.portaldalinguaportuguesa.org/).

Specification
------------
* Collect a page every 3 seconds as specified in [robots.txt](http://www.portaldalinguaportuguesa.org/robots.txt);
* For each letter of the alphabet creates a file (`letter_{}.csv`) containing the syllabic divisions of the words starting with that letter;
* At the end, it generates a file (`letters.csv`) containing all the collected syllable divisions.

Requirements
------------
The following modules are required to run the code:
* [Pandas](https://pandas.pydata.org/docs/user_guide/index.html)
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [Requests](https://requests.readthedocs.io/en/master/)
