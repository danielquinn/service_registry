# Let's write: service registry

## Overview
This service is responsible of keeping track of services within the system.
It is a RESTful way for services to find other services, and ensure that they
are healthy.

### Project requirements
A basic list of requirements can be foud in the `featrues` directory that
highlights the very high overview of how it is supposed to be working. It is
intentionally left like that as the details of implementation are left to you.
Any changes and decisions you make should be reflected in feature files with
corresponding steps implementation for [Behave](http://pythonhosted.org/behave/).
In short, if it is not in feature files, it doesn't exist and has no right to
exist in code.

## Your task
It's fairly simple - you have to write the whole thing. Nah, not really, as 
while it would be impressive - it is a rather massive task for months to write
a beast like this right. Instead I want you to try and write a part of it.

Which part it will be is entirely up to you. You can focus on the API part of
things and write beautiful RESTfull automation for all the services, design an
API for registration and then searching/retrieving, checking health etc. This
would mostly demonstrate your knowledge of architecture, designing, planning
and documenting.

Or you could instead write a solid backend that not only is easy to expand but
also to scale, either from scratch or on top of some existing solution (Celery
is a good example) in which case I would expect installation automation to go
along with it. It doesn't have to be pretty, shell-ridden vagrant would be
plenty. This would certainly highlight your developer aspects, including
knowledge of common problems that come with vertical and horizontal scaling
etc.

Anything else you can potentially imagine is acceptable as well. I do not
expect you to deliver anything that will be finished as that would take days and
I want you to spend no more than 2-4 hours on this. What I want to shine through
is how do you approach this sort of a project, where do you begin and what your
work process is like. For these reasons I would like you to commit as often as
you can, with good, clean commit messages and to provide a note explaining what
you've done, what are your plans for the future (if you were to keep working on
it) and possible problems that are yet to be conquered, preferably with potential
solutions. If there are bugs you've left behind because they would take too much 
time to fix, putting them there will score you big points.

## Summary

In summary have fun and trust me when I say: being honest and true with
everything, from what you know and what you do not know is the most important
part of doing well on this task. When you are done, please open a pull request to
this repo with your solution.
