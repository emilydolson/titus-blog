Google's AppEngine OneThousand
##############################

:author: C\. Titus Brown
:tags: python,google
:date: 2008-04-07
:slug: freezing-your-ass-off-at-google-with-leslie-and-guido
:category: python


At Google Campfire One, v 2.0 -- introducing AppEngine.

IT'S FREEZING.  The cider ran out.  Brr.

Deploying Web apps is annoyingly difficult.  Technical hurdles, etc.
Need machines.  Blech.  Costly.

AppEngine solves all these problems.  Runs web apps, handles app lifecycles,
apps are run on Google infrastructure can make use of GFS, auth etc. etc. etc.

Components

1. Scalable serving infrastructure
2. Python runtime
3. Soft Dev Kit
4. Web-based admin console
5. Data

Config is in YAML, with mapping done by regexp.

from google.appengine.ext import webapp, looks like Java to me.

Naah, that was mean.  It's python.

Oooh, WSGI built in.

def get, def post -- looks like web.py.  why do people do that?

Using introspection, building SQL-like GQL, to drop stuff into/suck
stuff out of database with proper names.

Django templates.

Single-command deployment.

Scalable serving infrastructure: when app pushed, pushed to multiple fault
tolerant servers.  Any one may fail, but request will always go through.
THE ROADS MUST ROLL.

All Python runtime and many third-party libraries available.  (How do they
deal with security?  What about SQL and ORMs?)

SDK: releasing for Linux etc.

Web-based admin console.  Standard stuff, stats collected in
"near-real time".

Data store.  BigTable. Yah.  Horizontally distributed fault-tolerant system.

No joins in GQL?!  Rationale: joins may need to work across computers and
individual ram capacity.

Send e-mail, make HTTP reqs, auth with Google accounts, use a variety of
frameworks.

Went to get cider, they replenished.  There are also meatballs wrapped in
dough (!?!)  It is still FREEZING.

Guido gets up.  He's on the AppEngine team.

All about making tools for developers.  But hates root password.  Thinks
AppEngine solves this.

"First time Google lets other people run stuff on their servers."

Isn't this a support nightmare?  Software versions etc??  Well, can upload
your own frameworks.

Stdlib emasculated in three ways: writing to the file system is forebidden;
cannot talk directly to the network (urlfetch & mail sending API); no
threads (chuckle, I think GvR not so secretly hates threads).

Python is not the only language (you heard it from Guido).  Perl?  COBOL?
Assembly?

Stuff about admin infrastructure.

Lots of nice error logging/tracking stuff.

Data viewer.  Interactive query.  Nifty.  (Hmm, how do you upload bulks of
data??)

Version control built in. Yay.

Is testing built in???

Adding a domain...

Host limits: 5mn page views a month for a well written application is free.

Over and out.  I'm freezing.  Still.

--titus


----

**Legacy Comments**


Posted by Nick Johnson on 2008-04-08 at 03:53. 

::

   But did you get an invite? ;)

