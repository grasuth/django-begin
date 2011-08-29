Django Begin
============

Experiments with setting up django projects, from start to deployment, with ease and simplicity.

Aim
---

The aim is to assemble tools and scripts to create a django project with support for integration testing
and deployment, to allow almost instant deployment onto staging or live servers and then to go on
supporting changes and adjustments with ease.

In a few bullet points, I guess that means:

* Lightweight and simple
* Not too prescriptive
* Feels just 'right', like django style
* Covers 80% of django project and deployment setup

There, that's not too hard to achieve :-)

What needs to be done
---------------------

Here are a few notes that cover the set of items that need to be dealt with when creating a django project.

* create project filesystem (manage.py etc)
* set up settings files
* add wsgi adapter
* .ignores for git and subversion
* add deployment scripting
* add requirements dir, requirements.txt
* load requirements
* set up tests (if needed)


Useful References
-----------------

The following are good references for all of this:


