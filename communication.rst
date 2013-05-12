Communication
#############

There are many times when you'll want to send a message to your
developers, and there are (and should be) multiple possible venues
for that message. There are some messages that are just for fun,
there are some absolutely business-critical messages that will
affect API implementations in production, and there are some
messages that are targeted at gaining more developers. All these
messages belong in different places, summarized here:

-  :ref:`blog`: New features, highlighted apps, relevant events -
   basically, feel good stuff.
-  :ref:`notify-list`: Major bugs, new releases, heads up about
   upcoming changes.
-  :ref:`twitter`: Re-tweets of relevant tweets, tweets pointing to
   blog posts or other links, replies to developers.
-  :ref:`discussion-forum`: Re-posts of notify list/blog/twitter, if
   any of them require discussion.
-  :ref:`newsletter`: Summary or subset of all of the above, but in a
   nice, readable format.


.. _blog:

Blog
****

It used to be that a blog was used for everything, from the mundane
(bugs/outages/release notes) to the new and exciting features. Now,
blogs have turned into such an art form and attracted such a wide
audience from the hardcore developer to the curious pseudo-geek
that it no longer makes sense to put the more mundane items in a
blog. Blogs have become, it seems, a vehicle for marketing, and it
looks a bit strange to market an outage (unless a massive apology
is called for). So, on your blog, focus on the good stuff - the
stuff that will get people exciteed.

New Features
============

When you have a new feature in the API, announce it with a blog
post, and include a demo that shows off the feature. Even small
features can have fun demos, if you get creative enough.

On the Maps API blog, I created a `zombie shoot-them-up`_ to announce
``GScreenOverlay``, a feature that was actually not terribly exciting
and was redundant with existing functionality, and I
created a `digital clock`_ to show off ``GMarker.setImage()``.
You should always, of course, have a demo that shows off the standard
usage of the new feature, but feel free to have some fun with the launch
demo in the blog post.

.. _zombie shoot-them-up: http://googlemapsapi.blogspot.com/2007/10/map-of-dead-screen-overlayed-shoot-em_31.html
.. _digital clock: http://googlemapsapi.blogspot.com/2007/04/gmarkershow-american-for-clock.html

Upcoming Events
===============

When you know of upcoming events related to the API - whether
they're organized by you or an external developer - boost their
attendance by posting about them on the blog. If there are a lot of
events coming up (as often happens in "conference season"), you can
do a summary blog post with the dates and registration links for
each of them. Here's an `upcoming events blog post`_ from May 2008, and
`another post`_ highlighting just a hackathon in Seattle.

Some of the larger events will be relevant to all of your developers,
as they'll be big enough to warrant the cost of flying in, but even if
the smaller events are nowhere near most of your developers, it's still good to
demonstrate that there is a worldwide developer presence. Often at
Google, it can seem as if we only hold events in the bay area and
only care about the developers there, but it's not actually the
case (anymore), and hopefully our recent international events blog
posts demonstrate that.

.. _upcoming events blog post: http://googlemapsapi.blogspot.com/2008/05/upcoming-events.html
.. _another post: http://googlegeodevelopers.blogspot.com/2009/08/upcoming-seattle-geo-apis-hackathon.html

Event Summaries
===============

After an event happens, consider posting a round-up of the event on
the blog - particularly if there are slides or videos from the
talks at the event. A lot of developers like to learn by watching
videos or flipping through slides, so you can get more bang for
your buck by making those resources available online and pointing
to them.

We held a series of talks for a small audience of ~20 geo
developers at our Google Mountain View campus, posted the videos
online, and after linking to them from a `summary blog post`_
and a fewother places, the top videos have 15-20,000 views. It's amazing
that you can hold an event for 20 developers and reach 1000 times
that amount. Never under-estimate the power of the viral internet.

.. _summary blog post: http://googlemapsapi.blogspot.com/2008/04/our-first-google-geo-developer-series.html


Highlighted API Uses
====================

Another way you can use your blog is to highlight different uses of
your API. If you find a third party website that uses the API in an
amazing way, or if you have a partner that you've been working with
that you want to highlight, then ask them to do a blog post that
explains their use of the API and gives some tips.

LonelyPlanet wrote an
`informational blog post <http://googlemapsmania.blogspot.com/2007/04/lonely-planet-innovates-using-google.html>`_
for our blog about how they optimized their use of the Static Maps
API for use on mobile phones, and Travellr wrote a
`blog post <http://googlegeodevelopers.blogspot.com/2009/06/travellr-behind-scenes-of-our-region.html>`_
explaining their complex but highly effective clustering technique.
Just make sure that a guest blog post isn't -just- showing off that
developer/company - it needs to be technically useful as well.

If you recently launched a new feature and you want to show off the
different ways that developers are using it, then you can write a
post that summarizes a couple different sites. Before writing this
`blog post <http://googlemapsapi.blogspot.com/2008/04/streetview-in-wild-flourishing-species.html>`_
about the use of the StreetView API, I solicited links in the forum
and promised schwag for any links that I featured. It was a great
way of making new connections and finding good, demo-able sites. I
still show off half of those sites when I present on that API.
Another example is this
`blog post <http://googlegeodevelopers.blogspot.com/2008/07/5-ways-to-use-static-maps-plus-new.html>`_
summing up ways of using the Static Maps API, and framing it as a
series of tips with links, in the hope that other developers would
be inspired to emulate the techniques.

Holidays
========

Finally, you can use your blog for seasonal fun. Yes, you should
probably be spending your holidays with your family, but writing
holiday demos has got to be the second best way to celebrate.

My `first holiday blog post`_ was an app to scratch a valentines day message
in the earth (and I made it count double by having the default message a
dedication to my boyfriend of the time). I then declared March to be the
month of `March Marker Madness`_ and rolled out a series of marker-related
posts, including an `easter egg hunt`_.
For Halloween, I wrote the `zombie shoot-em-up`_, and for Christmas, I wrote
up how we used the Maps API to power the `Santa Tracker`_ (we can track everything
at Google). I celebrated the anniversary of my first holiday blog post
with a Valentine's Day `greeting card maker`_, but since I was single
that year and a bit bitter, I also wrote a
break-as-many-hearts-as-you-can game. Hey, if I was single, there's
a good chance that a portion of my developer audience was single
and feeling the same urge.

As you can see, holidays can be a great opportunity to bring out
the personality and fun in your blog, and give you an excuse to use your
API in new and wacky ways.

.. _first holiday blog post: http://googlemapsapi.blogspot.com/2007/02/write-your-valentines-day-messages-in.html
.. _March Marker Madness: http://googlemapsapi.blogspot.com/2007/03/march-marker-madness-gmarkeroptions.html
.. _easter egg hunt: http://googlemapsapi.blogspot.com/2007/04/marker-managed-easter-egg-hunt.html
.. _zombie shoot-em-up: http://googlemapsapi.blogspot.com/2007/10/map-of-dead-screen-overlayed-shoot-em_31.html
.. _Santa Tracker: http://googlemapsapi.blogspot.com/2007/12/dont-stare-out-window-to-track-santa.html
.. _greetings card maker: http://googlemapsapi.blogspot.com/2008/02/send-geo-located-valentines-day-card.html


Personality
===========

Continuing on that note - an official API blog is still intended to
be authored by individuals, and individuals should maintain their
own personalities. Feel free to inject your individuality,
emotions, and childhood stories into your posts, as that will make
them more readable and bring your audience closer to you. Just
don't go as far as revealing something like your home address -
there are creepy people in the world, and creepy people tend to use
the internet.


.. _notify-list:

Notify List
***********

Some developers don't care about the "fluff" - they're using your
API in production, and they just want to know about the news that
will affect their current code. They don't have the time to sift
through blog posts and forum discussions to find the relevant news.
This is the purpose of the notify list - a read-only announcements
list that contains all business, nothing frivolous: new releases,
major bugs/outages, and heads ups on upcoming changes or upgrades.

New Releases
============

For v2 of the Google Maps API, every new release is potentially relevant to
all developers, as it is unfortunately the case that a new release
may break any version of the API (*not a good practice*). If a
developer is looking at their website and suddenly seeing some new
or different behavior with their map, they know that they can check the notify
list to see when a release happened and determine if it was
related. In our release posts, we describe bugs fixed, link to a
full changelog, and remind developers to post in the forum to
discuss any changes they're seeing. For example, ere's an example post
announcing release `2.171`_ of Maps API v2.

.. _2.171: http://groups.google.com/group/google-maps-api-notify/browse_frm/thread/5a2abe7b3ba79479


Major Bugs/Outages
==================

It is unfortunately the case that shit happens, and shit is even
more likely to happen to an web API. When a major bug
happens in your API, your goal as an API provider is to eliminate
that bug or find a way to prevent your developers from experiencing
it, and keep your developers informed along the way.

As soon as you discover a bug that affects the majority or a
significantly large number of your developers (or users of their apps),
you should post to the list acknowledging awareness of the bug,
list any known workarounds, and promise that you are working on it.
Once the bug is resolved (hopefully within a matter of hours if
it's a big one), post again to the list and inform developers that
everything is working as expected again. Here's
`the post I wrote <http://groups.google.com/group/google-maps-api-notify/browse_frm/thread/17ed31a7694a0f3b#>`_
when we discovered our HTTP Geocoder's XML output was invalid for
everyone, and here's
`the follow-up <http://groups.google.com/group/google-maps-api-notify/browse_frm/thread/5efe1347cda3b96c#>`_
when it was resolved.

You should develop some criteria for deciding what a critical bug
is for your own API, so that you don't spam the list for little
issues that don't affect many developers (those are serviced fine
in the issue tracker).

Heads Ups
=========

There are times in the (infinite?) lifetime of an API when you will
want to either change the behavior of some existing functionality,
or perhaps even deprecate a piece of functionality. Now, usually,
when you deprecate part of a Web API, you will almost always have
to keep it around for a good while or forever, but atleast you do
not have to make further fixes to it, and you can make sure new
developers do not use it. The notify group is a great way to let
developer know that these kind of API changes are coming.

When you're quite certain that the change is coming (i.e. the
launch is approved or the code is submitted), make a post to the
list that describes the change and the expected nearest date it
could happen. Try to do this post atleast a month in advance, in
case any developers want to change their code. (You may think it's
an easy change to make, but you never know what sort of Q&A/release
process a developer has to go through). Here's a
`post I wrote <http://groups.google.com/group/google-maps-api-notify/browse_frm/thread/2da3acb76e6189a4>`_
about a change in the firing of an event, and here's a
`post <http://groups.google.com/group/google-maps-api-notify/browse_frm/thread/944510a20db1b4ab>`_
about a change in the look and feel to a control. As you can see,
these are the kind of changes that may not necessarily warrant a
change in the documentation, and don't count as a breakage, but may
easily break assumptions that a developer's code makes. So, when in
doubt, let developers know!


Technology
==========

We use a Google Group for our notify list, as that means that it
can be read online, subscribed to via RSS, or subscribed to via
email, and that's the kind of flexibility that developers need. To
get developers to subscribe, we put a subscription box on the
landing page of each API, and we link to it from the FAQ about
support. It would be better if there was a consistent way to link to
notify groups across Google developer products, but since it is a
concept that we introduced only recently, each product has come up
with their own scheme.

In an ideal world, when a developer signs up for your API (e.g. to
get a key), they will be presented with the option to subscribe to
the mailing list - that way you would get every developer on the
list that cared.


.. _twitter:

Twitter
*******

Twitter is often described as "microblogging" - a mini blog post in
140 characters - and it turns out that people love to try and
squeeze their thoughts and status into this small amount of text. I
think that part of the reason for the success of microblogging is
the high bar of actual blogging these days - blogs are now an art
form, and people expect blog posts to be polished and of a decent
length. So, it's not easy to churn out many blog posts in a day -
but hey, 140 characters, you can come up with that during your
potty break.

For a corporate entity like an API, a tweet can be a great way to
communicate the smaller things that don't warrant a full blog post,
but are still interesting to the developer world.

Link tweets
===========

Many tweets in the world are really just links to somewhere on the
web. Why? Well, Twitter asks what you're doing right now, and since
most people using Twitter are on their computer, most people are in
fact visiting a website. Once mobile clients become more and more
popular, this may change, and we may actually get more non-geeky
tweets (e.g. "I'm jumping out of a plane!"). But, people will
always like sharing links - it's the basis of the web's
viral-ness.

From an API account, there are many websites to link to -
documentation, articles, blog posts, sample code, third party
websites, etc. Just always try to describe the link in a way that
will get people interested on clicking on it, and even better, get
people to re-tweet it (spreading the word around). This might mean
using a few buzzwords, but, hey, it's Twitter - it's basically
everyone competing to out-market one another. Join in the fun. Here
are a few examples:

  What happens if sea levels rise by 6, 10, 18 inches? See what
  happens to your city on this flash map: http://globalfloodmap.org/

  So cool - the power of Google Maps API & jQuery UI together- change
  the look & feel of your map just by theme switching: http://tr.im/szGT


Re-tweets
=========

As noted in the keeping tabs section, you should be constantly
monitoring Twitter for tweets relevant to your API. When you see
something interesting (usually a website using the API), re-tweet
it from your API account. If there's space, try to add your own
commentary to the re-tweet. Here's an example re-tweet that does
that:

  RT @oschicago: On the Road with the Google Maps API: http://is.gd/1hJTo -
  Great article on using GDirections!


Questions
=========

Twitter users love giving their opinion, and generally just love
having something to say. Thus, they love responding to questions
posted by other users. So, a great way of engaging your twitter
audience is to ask questions in your tweets. For an API, the
obvious questions are asking who uses what parts of the API, or who
uses the API for what reasons. You can ask the questions as
standalone tweets, or append them to other relevant tweets. Here's
an example link tweet with a question at the end:

  Orbitz is now using the Street View API on its hotel
  listings! http://tr.im/wBIl - Are any of you
developers using it for hotel search?


Replies
=======

On Twitter, you can reply to users by starting the tweet with their
username. As an API account, you want to avoid having conversations
on Twitter that should be taking place in the forum or issue
tracker instead. So, when possible, use replies to direct
conversations to the proper venue or to give final answers.

When you see a tweet about the API and it mentions a possible bug
or complains about documentation, reply to the tweet and ask them
to post it in the issue tracker. When you see a tweet about a
current big outage in the API (as it will get tweeted about when it
happens), point them to the notify list post about it. The basic
idea here is to make sure Twitter users knows that you're always
listening to their feedback.

Sometimes, Twitter users will direct a message to your account, or
mention it in a tweet, often asking a question or recommending that
you check out a site. Answer their question using the same
technique as above, and if it's a nice site, consider re-tweeting
it.


Authorship
==========

As mentioned in the blog section, it's a good idea to inject some
of your own personality into blog posts. That's true for tweets as
well, but it's a bit tricky. On a blog post, you can include a
byline that indicates who actually wrote the post. On a tweet, you
only have 140 chars - there's no room for a byline, and no
convention for putting one.

One solution, adopted by a few corporate accounts like
`whereivebeen <http://twitter.com/whereivebeen>`_, is to make the
avatar combine the corporate logo with a photo of the usual author,
and make the Twitter profile clearly describe the author. Another
solution, used by accounts with multiple authors, is to come up
with a convention for indicating the author of a tweet, and
describe that convention on the Twitter profile. The fallback
solution is to do nothing, and just use a generally cheery,
informational attitude.

Whatever you do, just be careful about what you tweet. It is very
easy to users to re-tweet something that offends or irks them -
much easier than responding to a blog post - so one slip-up can
turn into a rising trend on Twitter. The general topics to avoid
are competitors, death, sex, religion, race, politics. If for some
reason your tweet does cover one of those topics (e.g. an API
mashup plotting deaths from a recent disaster), send it to a
colleague to a sanity check before posting. I once posted a tweet
that connected the deaths of two famous celebrities with some
recent API news, and that tweet landed our account on
`TechCrunch <http://www.techcrunch.com/2009/06/25/the-web-collapses-under-the-weight-of-michael-jacksons-death/>`_-
it may be just a tweet to you, but it can still blow up in your
face.


Technology
==========

If you've put yourself in charge of twittering for your API, the
chances are that you are already a Twitter user - meaning that you
now have a personal Twitter account and a corporate Twitter account
to maintain. This can be tricky to do, considering that each
require their own login, and considering that Twitter is kind of an
always-on experience.

The first option is to simply have two different browsers, one
logged into each account. That's not ideal if you're a power
Twitter user though, because the Twitter website itself is pretty
basic and doesn't wrap up all the functionality that you should be
using.

The better option is to use a Twitter app or client that includes
functionality like saved searches and also allows for logins from
multiple accounts. For example, `TweetDeck`_ is an AIR app that works across
Windows and Mac and supports both those features. It is a bit scary
that both logins are saved into the same app - it means you need to
be a bit more careful to make sure you don't tweet a personal
status from your corporate account.

A more secure option is to use two different Twitter apps,
one for your personal account, and one for your corporate account.
There are other TweetDeck-like apps like `Seesmic`_, there are browser
extensions like `Chromed Bird`_, and there are webapps that specifically
cater to the corporate tweeters, like `HootSuite`_.
For a small fee, HootSuite
lets you share an account with another user, so if you share
tweeting responsibilities with a colleague, you can both see
the same view of saved searches, pending tweets, and statistics.

.. _TweetDeck: http://www.tweetdeck.com/
.. _Seesmic: http://seesmic.com/
.. _Chromed Bird: https://chrome.google.com/extensions/detail/encaiiljifbdbjlphpgpiimidegddhic
.. _HootSuite: http://www.hootsuite.com


.. _discussion-forum:

Discussion Forum
*****************

The discussion forum should primarily exist for discussion of API
development, and that generally means that most posts will be from
developers. But, since the forum has an active audience, and since
developers like to discuss anything API-related, you can use it as
a place to re-post items from the blog, notify list, or Twitter.
The key is to use your discretion so that you don't dominate the
posts.

For the Maps API, I have a policy of always re-posting in the forum
any message that is posted to the notify list. This does mean that
the good developers get messages twice, but I like giving the
developers a place to discuss the releases, bugs, or upcoming
changes. If you don't give them an obvious way to discuss those
posts, then they will 1) assume that you don't care about their
voices, and 2) email you personally with their thoughts. Both of
these outcomes are undesirable.

As for re-posting blog posts or links that I tweeted, I will do it
every so often. Those posts make for a nice, happy change from the
typical "my app doesn't work posts", and make the forums into a
happier place that hopefully developers will want to be in. This is
a particularly good idea for forums that still have small
communities, as it motivates developers to pay attention to the
forum posts so that they'll see the inspirational or informational
posts, and every so often, they may decide to respond to a forum
post as well. As examples,
`this post <http://groups.google.com/group/google-maps-api-for-flash/browse_frm/thread/00bb53743fc9fe4c#>`_
links to a blog post made on our blog,
`this post <http://groups.google.com/group/google-maps-js-api-v3/browse_frm/thread/92e070b430bb9c3d?hl=en#>`_
announces a new demo and encourages developers to add their demos,
and
`this post <http://groups.google.com/group/google-maps-api-for-flash/browse_frm/thread/1fa8460d90ae9ce7#>`_
links to two cool uses of the API from non-Google developers.



.. _newsletter:

Newsletter
**********

The newsletter is a very "retro" style of communication, but it is
still a good one. It appeals to the people that may not care enough
to read through blog and forum posts, but still want to know
generally what's going on with a product, and they want the
information delivered straight to your inbox. Basically, you make
it as easy as possible for them to keep up to date with your latest
news, and you benefit because they likely would not have paid
attention to any other communication form.

A typical style for a newsletter is a once-monthly summary of all
the recent news in an easy-to-read format. One example of that is
the
`AWS Developer Newsletter <http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=42>`_,
put out by Amazon each month. The newsletter consists of recent
news (a paragraph for each item), new developer resources
(articles, code), highlighted AWS uses, and a summary of upcoming
events.

Some services put out newsletters only when there are a significant
number of new features to announce, and they want to bring those to
the developer's attention. Those newsletters would typically happen
less frequently.

Instead of a newsletter or in addition to it, an API provider can
also send out targeted emails when it has a big announcement that
it wants to make sure all of its developers are aware of. Once
again, Amazon is an example of this kind of communication. Once
every few months, Amazon sends emails informing developers about
its new offerings. These emails may well be replicas of blog posts
elsewhere, but they are probably more likely to be read than blog
posts. People often subscribe to blogs and then forget to read
them, but they don't often completely ignore emails in their inbox.
If you can get developers to agree to receive news via email, you
will likely have a captive audience on your hands.
