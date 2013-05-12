Mention Monitoring
------------------------------------

It's important to find out what the world thinks of your API, and
to find out what they're doing with it. There's a lot you can find
out from just paying attention to the comments on your forum and
issue tracker, but not every developer will channel their thoughts
into those places. Some will write about it on their blogs, some
will rant or rave about it on their social network, some will issue
press releases. The general strategy is to subscribe to searches
using keywords associated with your API across various searchers.

Keywords
^^^^^^^^

The first step is to determine what keywords you'll be searching.
Your API might have an official title, but that title might be too
long for the average developer to use, or perhaps there are
nicknames for it. For example, we have an API officially called
"The Google Maps API for Flash". I in no way expect developers to
type that out, and I can't be bothered to do it myself most of the
time. So, keywords for that might be "flash maps api", "flash maps,
"google maps flash api", etc. Our JavaScript API, since it was the
first mapping API we offered, is typically just called the "Google
Maps API", but since the class name for creating a map in that was
GMap, developers also tend to abbreviate it as simply "gmaps". So,
appropriate keywords for that API would be "google maps api",
"gmaps api", etc.

Google Alerts
^^^^^^^^^^^^^

Google provides a service called Google Alerts, and it basically
lets you subscribe to new results for particular search terms, or
new search results that link back to a particular page. They're a
great way of seeing what the web is saying about a particular
topic, and people use them for lots of reasons. Many of us nerds
with low self-confidence have a vanity search (for our name) so we
can see what the world thinks of us (hopefully good things). You
can setup an alert and subscribe to that via
daily/weekly/as-they-happen alerts, and even subscribe to it as an
RSS feed (?). I have daily alerts set up for all of my searches, so
that I go through them once a day and see if there's anything of
interest.

Twitter Searches
^^^^^^^^^^^^^^^^

Google can index nearly the entire world, but apparently that
mostly excludes Twitter. For the most part, Google Alerts will not
show you many results from Twitter -- simply because they happen
too fast and from so many different account pages, I suppose -- so
you need to setup a separate Twitter search to track your API. The
basic twitter search functionality can be accessed from
search.twitter.com, and you can enter any query there and refresh
the page when there are new results. For a bit better experience,
you can use a Twitter client like Tweetdeck (AIR desktop app) or
PeopleBrowsr (web app), and you can ask those apps to notify you
when there are new results for your specified search terms. In
addition to the keywords you came up with earlier, you should
consider searching for those phrases with the whitespace stripped,
as tweeters like to turn everything into a hash tag (e.g. "google
maps api" becomes "#googlemapsapi"). If you have a Twitter account
for the API itself (which I recommend), then you should of course
also be monitoring mentions of that account's name. Note that once
people know the account username, they will tend to use that as the
hashtag as well, so having an account is a good way of
standardizing the hashtag used.
Twitter search has been a good way of finding out that a service is
down or broken - tweeting is so much easier to do than posting in a
forum or issue tracker, so people take to that first as a place to
complain about an issue. So, try to monitor it somewhat real-time,
so that you know something's wrong as soon as the twitterverse
does.
