---
title: PopGen dev
permalink: wiki/PopGen_dev
layout: wiki
---

Development page for the PopGen module.
=======================================

Abstract
--------

The [PopGen](PopGen "wikilink") module will contain modules to handle
population genetics data.

Philosophy
----------

Most of the existing Bio.PopGen features are of non-core population
genetics functionality. This was seen as feature (and not as a bug) in
order to start building a module with functionality where newbie crass
errors would not have dramatic consequences. Currently, with the
experience accumulated is is possible and desirable to concentrate on
core population genetics functionality (i.e., statistics).

Also worth noticing is that we wrap existing functionality whenever
possible. For instance we don't provide our own coalescent simulator,
but we provide wrappers to an existing one which is established and
widely used (SIMCOAL2).

Future Goals
------------

The fundamental goal is to have support for "classic" population
genetics operations (statistics). This should be provided in an
extensible, easy to use and future-proof framework. Code exists (see
below on how to find it), but will probably be refactored. Below there
is also a with list where you can add your desired features.

In the pipeline
---------------

Currently (i.e., for the near term) the following new functionality can
be expected

-   STRUCTURE support
-   LDNe support

Code
----

The official production code is available on CVS.

Some of the development code is informally hosted on github:

-   <http://github.com/dalloliogm/biopython---popgen/commits/master>

How to contribute
-----------------

Your contribution is most welcome, please have a look at the [General
Biopython contribution guidelines](Contributing "wikilink"). Join us on
the biopython-devel mailing list and tell us about your ideas!

Informal development versions can be found, for now, on github where you
can create a free account, and then click on the 'Fork' button
(something like <http://github.com/dalloliogm/biopython---popgen/fork>)
and then start working on your separated branch.

Wish list
---------

-   support for a binary format - like [HDF5](http://www.pytables.org)
    or this one:
    [snpfile](http://lists.open-bio.org/pipermail/biopython/2008-December/004830.html)
-   support for database: it is frequent to carry analysis on a big
    scale, so it is not unfrequent to use databases to store data
