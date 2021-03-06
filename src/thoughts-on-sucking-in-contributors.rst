Thoughts on Getting Contributors Involved
#########################################

:author: C\. Titus Brown
:tags: python,ghop
:date: 2007-11-29
:slug: thoughts-on-sucking-in-contributors
:category: python


In trying to pull together ~50 tasks for the initial Python part of
the Google Highly Open Participation Contest, I ran into some
interesting issues.

**First: it is not easy to find "easy" or "intro" tasks for projects.**

I sent out a lot of e-mails and posted a blog request (well, two) for
help, without specifying exactly why I wanted some intro projects.  I
got a number of suggestions from people.  One friend suggested working
on pygame, pug, and pgu; another friend pointed me towards the Django
"projects for new people" page; someone else pointed me at the
"undocumented modules" page for Python.  None of the pages provided
much in the way of entry points for people who were relatively new to
the project in question, much less those new to Python; most of the
entries were out of date anyway.

This is the reason why there are a bunch of pyblosxom tasks in the
Python GHOP list: Will Guaraldi suggested *plugin testing*, which is
perfect for a 2-3 day project.  The Rosetta Code stuff that Michael
Mol suggested also seemed perfect to me.

Providing a bunch of small, explicit tasks is a great way to suck people in.

**Second: task lists quickly become outdated.**

Check out the Django "intro tasks" page and then look at the tracker
entries; they're either done, or still being argued about.  Either way,
I didn't know where to start in suggesting a task to a student.

Task lists bitrot as quickly as anything else.

**Third: how you ask for help matters.**

Compare http://ivory.idyll.org/blog/nov-07/new-to-python-projects.html to
http://ivory.idyll.org/blog/nov-07/hidden-gems-in-stdlib.html.

I failed to give specifics or limit the problem domain in the first
post, and I slowly got a very mixed bag full of wildly varying tasks;
I later found out that it got picked up by Reddit, which is the only
reason I got anything at all.  In the second post, I asked people for
*opinions* (which they're always happy to give!) and I narrowed the
problem domain substantially.  I still had to pick through the
resulting module suggestions, but it gave me a place to start.

People *love* giving off-the-cuff opinions on specific domains.

**Fourth: people have a tough time coming up with specific tasks.**

The composition of Python's GHOP task list is largely the product of
what I myself could write up easily; `Crunchy
<http://code.google.com/p/crunchy/>`__ features quite heavily because
Andre Roberge was very responsive and wrote up a bunch of good,
specific tasks.  I couldn't figure out a good set of topic domains for
screencasts, so there are relatively few screencast tasks -- even
though screencasts are a great task idea for this kind of project.

Saying "pick a module, any module, and work on it", or "screencast
something", doesn't help new contributors very much.

**Fifth: there seems to be a lot of low-hanging fruit in the stdlib.**

See http://ivory.idyll.org/blog/nov-07/hidden-gems-in-stdlib.html for
a bunch of comments on where the stdlib needs work.

This is the reason why I ended up dragging Doug Hellmann into the GHOP
project: his `Python Module of the Week
<http://www.doughellmann.com/projects/PyMOTW/>`__ posts are excellent
introductions to modules that may be a bit inaccessible otherwise.

The stdlib could use some love.

--titus
