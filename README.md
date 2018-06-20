# Wikipedia-Web-Crawler
A simple web-crawler using python

So what's the purpose of this project?

Well, if you are on a wikipedia article's page and keep on clicking the first link of the main article
(Not translation and pronunciations) then you will eventually land up on the "psychology" article's page. 
However this isn't correct all the time. Sometimes there are loops and sometime there's no link to
navigate. So we automated this task using python.

Our little web crawler takes a starting url (link of the current article's page) and a target url(i.e psychology).
Then it keeps on visiting each first link.

Libraries required:

1.BeautifulSoup
2.requests

Run the Main.py file and see the magic. You can change the starting url in the code and give your chosen url.

