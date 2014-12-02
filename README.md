# Reddit Top 2.5 Million

## What is this?

This is a dataset of top posts from [reddit](http://www.reddit.com). It contains the top 1,000 all-time posts from the top 2,500 subreddits, so 2.5 million posts in total. The top subreddits were determined by subscriber count and are located in the manifest file within.

Ths data was pulled between August 15-20 of August 2013.

Each file is a CSV with the related subreddit as its filename. Each CSV file contains a header line.

[A good example of the structure of this data is here.](https://github.com/umbrae/reddit-top-2.5-million/blob/master/data/serendipity.csv)


### RESEARCH QUESTION
How is corporate media reflected on social media?  How do world events published
in mainstream media reflect sentiment of social media posts?

### NLP
For NLP We will be using nltk.  Install with pip:
sudo pip install -U nltk

### Where we got the data from
https://github.com/umbrae/reddit-top-2.5-million

### News articles

####Newtown school shooting
http://www.endmemo.com/events/evt/2012gunmanassaults.php

####NSA Prism program leaked
http://www.endmemo.com/events/evt/2013usnsa.php

####Boston marathon bombed
http://www.endmemo.com/events/evt/2013bostonmarathon.php

####Facebook IPO
http://www.endmemo.com/events/evt/2012facebookipo.php

We have 3 news articles from NYT, Fox, and CNN for each event.  These are stored as text files under /articles. 

