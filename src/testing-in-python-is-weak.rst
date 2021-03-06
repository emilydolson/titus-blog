Testing in Python is Weak?
##########################

:author: C\. Titus Brown
:tags: python
:date: 2007-03-03
:slug: testing-in-python-is-weak
:category: python


Voidspace makes a `mildly provocative post <http://www.voidspace.org.uk/python/weblog/arch_d7_2007_03_03.shtml>`__ about how testing seems to be more
emphasized in the Ruby community.

I'm not entirely sure I agree, but then again I'm firmly embedded in the
Python testing community and I might have a slightly biased view ;).

What I *am* sure about is that just because Ruby folk (or really, any
bloggers at all) are vehement about a topic doesn't mean that that
topic is actually of great concern to anyone, even the community the
bloggers come from.  To put it more succinctly: just because you *read*
more about testing in Ruby doesn't mean more people *test* properly in
Ruby.

In fact, from what I can tell, testing -- especially agile testing
techniques -- is still quite young.  Despite all the consultant-driven
hype that emanates from the XP community (which is GOOD) I don't think
that testing has even penetrated the cortex of the software
development community, much less into the reptilian inner brain.
I base this opinion on two observations:

 * the testing tools available to most programmers are lousy, even in
   Ruby and Python.

 * apart from a core group of devotedly interested people, I don't
   get the impression that there's much of a testing community in
   Python.  After all, testing should be *pervasive* throughout
   software development at this point... right?

So I think it's premature to conclude that *any* community is
especially good at this, when the tools are so crappy and the
discussion is so limited.

He raises a few more interesting points that I would like to address:

 * Is there a compelling reason to switch to Python for Web dev?

   Yes: I would argue that WSGI and the WSGI testing tools now available
   (viz. `wsgi_intercept <http://darcs.idyll.org/~t/projects/wsgi_intercept/README.html>`__ and `paste.fixture <http://pythonpaste.org/testing-applications.html>`__ are important developments, because *no matter what Web frameworks emerge in the future*, you will have a clear path to deployment and testing.  That's a longer-term guarantee than the hope that Rails does not fork or become fugly.

 * Testing does create beautiful code.  In fact, I think that this effect
   is the dominant reason that testing results in more *maintainable* code.
   More on this next time I'm feel philosophical.

 * Grig does rock.  People seem to underestimate the role that process
   plays in software development, and Grig is good at analyzing and fixing
   processes.  (I much prefer tackling code; it's easier.)

 * Hopefully the TIP list will help with the lack of community discussion.
   There's not much to see if Python people interested in testing don't blog
   about it, which seems to be the case...

Anyway, interesting post, and keep on testing!

--titus
