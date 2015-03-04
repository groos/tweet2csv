# tweet2csv

#### tweet2csv is a script written in Python to query Twitter's search
API and output the results as a CSV. The original has been forked to include updated credentials validation. The updated implementation also uses a different data output which includes the Twitter username. 

## Requirements

tweet2csv requires [Tweepy](http://tweepy.github.com/). The easiest way
to install Tweepy is:

    $ easy_install tweepy

Altnerative installation methods can be [found here](https://github.com/tweepy/tweepy/blob/master/INSTALL)

## Example Usage

Usage typically follows this format:

    $ python tweet2csv.py [QUERY]

So get a list tweets mentioning @user:

    $ python tweet2csv.py "@user"

Or, get a list of tweets mentioning @user and #hashtag:

    $ python tweet2csv.py "@user #hashtag"

Or, just get usernames of people saying "exact phrase":

    $ python tweet2csv.py "'exact phrase'" -c from_user

See [Using the Twitter Search API](https://dev.twitter.com/docs/using-search)
for more examples of queries that can be run against Twitter's Search API

## Resources

* [GET search](https://dev.twitter.com/docs/api/1/get/search)
