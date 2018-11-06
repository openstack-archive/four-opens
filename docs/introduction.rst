============
Introduction
============

Where do the Four Opens originate from? They came from a need to do things
differently.

Free software started in the 80’s by defining four (initially three)
freedoms [1]_ that any free software should grant its users. Freedom 0 was the
freedom to run the program as you wish, for any purpose. Freedom 1 was the
freedom to study how the program works, and change it so it does your computing
as you wish. Freedom 2 was the freedom to redistribute copies so you can help
your neighbor. Freedom 3 was the freedom to distribute copies of your modified
versions to others. Those freedoms made you free to improve the program, and
release your improvements to the public, so that the whole community benefits.
But free software did not mandate anything about how the software was to be
built to actually encourage this collaboration across boundaries that would
result in benefiting the whole community.

When open source was defined in 1998, it focused on a specific angle (the one
that mattered the most to businesses), which is the availability and
re-usability of the code. That also said remarkably little about how the
software should be built, and nothing about who really controls it. As a
result by 2010 most open source projects were actually closed one way or
another: their core development may be done behind closed walls, or their
governance may be locked down to ensure control by its main sponsor. Sure,
their end product was licensed under an open source license, but those were not
really community projects anymore. 

The control of a specific party over the code is discouraging contributors to
participate: those are seen as free labor and are not on a level playing field
compared to contributors "on the inside", which really decide the direction of
the software. The only option for a disgruntled community is to do a costly
fork of the project, and fragment the limited resources available to work on
that topic. The most extreme case is the open core variant, where a company
maintains the basic functions of the software as an open source "community"
project but keeps advanced "enterprise" features under proprietary licenses.
This inevitably creates tension when a user wants to contribute back an
improvement (like security or scalability) that the controlling entity would
prefer to keep for its Enterprise edition. All this control ultimately hurts
the adoption and the success of the software.

OpenStack was started with the belief that a community of equals, working
together in an open collaboration, would produce better software, more aligned
to the needs of its users and more largely adopted. It was therefore started
from day 0 as an open collaboration willing to include as many individuals and
organizations as possible, on a level playing field, with everyone involved in
designing the solution. This was relatively novel: while a few venerable
projects like the Linux kernel were set up and perdured as truly open
collaborations, most new projects in 2010 were just owned by a "main sponsor"
This is why it was pretty important for us to state in a very concise way what
we really meant by Open. It was also important to clearly distinguish ourselves
from prevalent open core solutions like Eucalyptus, which was then the only
open source cloud infrastructure platform available.

It was from these conditions that "The Four Opens" were born. The first public
mention of them was posted on the then-nascent OpenStack Wiki on June 28,
2010[1]_, before OpenStack was even publicly discussed or announced. The
titles of the Four Opens (Open source, Open Design, Open Development, Open
Community) were set from that day. The content evolved a bit over time on the
Wiki, as implementation details rolled in (for example: public code reviews,
design summits, technical committee, lazy and consensus). The Four Opens
description is now maintained officially in the OpenStack governance
web-site[2]_.

After eight years, the Four Opens proved pretty resilient, consistently
managing to capture the "OpenStack Way" of doing upstream open source
development. Under their rule, the OpenStack community grew from tens of
contributors to thousands. They were instrumental in the success, the quality
and the visibility of the OpenStack software. As this book will show, they also
proved applicable to downstream activities such as user feedback gathering,
marketing, or event management. As the OpenStack Foundation turns to more
generally support Open Infrastructure, the Four Opens will grow beyond
OpenStack. Let's apply them to other nascent open source projects with the same
success.

[1]_ https://wiki.openstack.org/w/index.php?title=Open&oldid=9628
[2]_ https://governance.openstack.org/tc/reference/opens.html
