Introduction
------------

Welcome to the handbook!
Before diving into the particulars of developer support,
it's important to realize what developer support is,
why it's important, and where I'm coming from in writing this.


Background
^^^^^^^^^^

A few years ago, there were only a handful of APIs on the web.
Now, there are thousands, and there is almost an expectation that
a web application or data provider will provide an API.

By providing an API, you can enable developers to use their creativity
and skill to extend your products to new environments, to handle new use cases,
or to appeal to new users. In the best of worlds, you can make
your product more compelling while also giving developers an opportunity
to make a living off your product API. For example: Twitter started with a simple
web interface but also a simple API, and because of that API, developers
were able to create the clients that users wanted, so Twitter got more users
and developers got more money.

Most of the time, it is not enough to simply provide an API.  You also need to
support the developers that are currently using the API, improve the API to
better meet the balanced needs of the product direction and developers, and
encourage more developers to start using the API.  All of this is a cycle: when
you have a good API, more developers will want to use it, which means you will
have more developers to support, and you will need to keep improving the
API to meet their needs. To do it right, you need to understand the commitment
that you are making when you decide to provide an API.  You need to realize that
you will need someone support the API, someone to maintain that API (if not
improve it), and often you will want someone to "evangelize" that API - and you
will need these somebodies (whether it's one person or many) for the foreseeable
lifetime of the API. If you are not willing to invest that much time and
resources into the API, you should reconsider your decision to provide one.

In this handbook, I mostly cover the first aspect of providing an API: support.
It is probably the least glamorous aspect, but on the other hand, it is vital.
You can have the best API in the world, but if people post in your forums and
the response is just crickets chirping, then the developers will not stick
around for very long.  On the other hand, if you treat your developers well,
then they will (for free) provide you with valuable insights about ways to
improve your API, and they will evangelize your API for you.

The area of developer support is quite new, and there isn't much written about
how to do it - what works, what doesn't. Given the increasing number of APIs,
and I hope, the increasing number of people attempting to support API
developers, we need to start documenting our field. This handbook is a first
attempt.


Guiding Principles
^^^^^^^^^^^^^^^^^^^

The chapters in this handbook deal with specifics, but are all based on these
general principles:

 * **Care about your developers**:
   Call me a sap, but I think that you can't really do a good job at
   supporting developers if you don't actually care about their success
   with your API. If your heart doesn't ache a little when you realize
   you've introduced an API bug that breaks a developer's site, or
   if you don't get a little shot of glee when you see a developer's finished
   app, then this may not be the right role for you.
 * **Empathize with your developers**:
   Put yourself in your developer's shoes. If you were a developer of your API,
   how would you want to be treated?
   I was a Maps API developer before I became the Maps API support
   engineer at Google, so I had the fortunate experience of knowing exactly what it felt
   like. If you don't, you can simulate that experience to a certain extent
   by trying to accomplish some task with your API, and not letting yourself
   use any internal resources. Force yourself to read the public docs
   and search the public forum for answers, and remember what is good
   and bad about that experience.
 * **Keep your developers informed**:
   As the API provider, you are the holder of a massive amount of useful
   information: you know how the API works, you know when you've released a new
   version, you know your roadmap. The more information that you can convey
   to developers, the easier it is for them to use your API.
   For any piece of information you have about your API, your default should be
   to share that information, and if you decide not to, you should have a good,
   thought-out reason for that decision. (There are valid reasons - just
   make sure you're not withholding without one).
 * **Listen to your developers**:
   As they use your API, your developers will have questions, they will have
   comments, and they will have suggestions. Your developers should have a place
   (or multiple places) to make their thoughts known, and you should make it
   known that you are listening to them. Some folks worry that listening to
   developers means that you must do what they tell you to, and that's not the case.
   Most of the time, developers are just happy that they've been heard.
 * **Appreciate your developers**:
   Everyone likes to be appreciated for good work - even if they don't *need* to
   be appreciated. If a developer is helping you do your job by making the API
   more successful (then by samples, articles, or forum posts), you should let
   them know you sincerely are thankful for their help.

If you read nothing else in this handbook, simply remember those principles,
and they can guide you in making the right decisions.


About the Author
^^^^^^^^^^^^^^^^

I'm Pamela Fox, and I've spent the last four years supporting the developer
community for various Google APIs.  I started on the Maps API, back when Google
had only a handful of APIs and we were very new to this game, and then spent a
year on the Wave APIs.

In my role as an API support engineer, I am basically the middleman (middle
woman) between the API developers and the API engineering team, and I am tasked
with making sure that API developers are successful. This means monitoring the
forum for unaswered questions, reporting bugs to the team, collating the top
feature requests, creating sample code, writing articles, authoring blog posts,
presenting at conferences, training paying customers, and more. It's a fun role
because it involves a lot of different skills, and it brings a wide range of
technical and sociological challenges.

In this role, I have learned a lot about what it means to succesfully support a
developer community, and I want to share those learnings through this handbook.


Intended Audience
^^^^^^^^^^^^^^^^^

At Google, I come from a team called Developer Relations, and many
of my peers in this team have the same role as me, but for our other APIs. This
information is most directly targeted at them.
However, there are many other people who interact with the API
developer community at some point during their day, and this information is
still highly relevant to them - the API tech lead, product manager, engineering
team, marketing team, technical writer, support team, etc.
