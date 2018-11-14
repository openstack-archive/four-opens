===========
Open Source
===========

    We do not produce "open core" software.  We are committed to creating truly
    open source software that is usable and scalable. Truly open source
    software is not feature or performance limited and is not crippled. There
    will be no "Enterprise Edition".

We use the Apache License, 2.0. It is:

- OSI approved [#OSI]_.
- GPLv3 compatible [#GPLv3]_.
- DFSG compatible [#DFSG]_.

The most fundamental principle, historically reaching back to the "Four
Freedoms" of the Free Software Foundation, is "Open Source". Any software
developed under the Four Opens must be released under an open source license.
It means being able to study a program, modify it, and redistribute either the
original or the modified version so that others may benefit from your work.

That is a minimum standard for what we mean by "Open Source" in the Four Opens.
Beyond that, we want the software to be truly usable and scalable. This adds
the additional condition that it should not be limited in features or crippled
in performance to artificially enable any business model.

In particular, the "Open Source" principle is strongly opposed the "open core"
model, where source code and features in a proprietary "Enterprise Edition" are
deliberately withheld from the open source software. This model invariably
fails both vendors who promote it and users of the software. On the vendors
side, the ethos of committed open source developers will lead to the withheld
features and shortcomings being addressed as part of the open source version of
the product. In the best case the enhancements are made to the original
version. In the worst case, the software is forked, fragmenting the community.
Either way, the commercial upshot for "open core" is limited and risky. On the
users side, they are unnecessarily given a limited experience, with the
choices of giving up the freedoms that open source software provides by
purchasing the "enterprise" edition, wasting time and resources re-implementing
features or capabilities that already exist, or turning to other projects to
fill their needs.

This model always fails once a community member tries to add a feature that the
open core company product management would prefer to keep in the proprietary
version. That ultimately results in reduced adoption, prevents a community of
equals to be formed, and increases the risk of a fork or emergence of a truly
open competition. It is an especially bad choice for infrastructure software,
where enterprise features (like security or scalability) are desirable for
every user.

The "Open Source" Principle in Practice
---------------------------------------

"Open Source" begins with the choice of license a community applies to its
project. In most cases at the OpenStack Foundation, we use v2.0 of the Apache
License [#apachev2]_. The license meets the requirements of being able
to modify and
redistribute a work. It includes a number of provisions that also protect
end-users by granting copyright and patent licenses to all end users, while
limiting liability to the original copyright holder. This patent protection is
one of the distinguishing features in comparison to other open source licenses,
like the MIT License.

In practice, individual and corporate contributors need to understand the
consequences of contributing code to an Apache Licensed project, particularly
the granting of copyright and patent licenses to all users of the software. To
acknowledge this, many projects require that all contributors sign a
"Contributor License Agreement" (CLA) [#OSCLA]_ or "Developer Certificate of
Origin" (DCO). Typically, a CLA is a stronger statement, attesting that a
contributor has a right to submit work to the project and that they are
granting copyright and patent licenses in accordance with the Apache License
along with their submissions. A DCO, on the other hand, is a bit lighter weight
and is more of a statement (rather than a license) that the developer is indeed
authorized to submit changes to the project and understands that their
contributions will be used in accordance with the license. A CLA, being a
stronger document, is also considered a barrier to entry. A DCO, in contrast,
lowers the barrier to entry by removing the requirement to consent to a legal
document [#CLAvDCO]_.

Apache 2.0 is very liberal in allowing companies to modify and use the code in
any way they want, and doesn't place requirements to release changes (although
it doesn't prohibit them from doing do). This, along with the patent
protections of the license, is one of the reasons why it is so popular. It has
also been used in practice since 2004, and is fairly well understood amongst
the corporate and open source legal communities.

This liberal view on modification does have some downsides, though. It becomes
very easy for companies to withhold enhancements that would be beneficial to
the wider community, or to make changes to their version of the software that
breaks interoperability. While the license doesn't address these directly,
there are guard-rails that a project can put in place to mitigate these risks.
Trademark programs based on interoperability or conformance testing are one
such tool. The OpenStack Foundation uses such a program. In order to qualify
for the trademark, a product can not modify API code (thus adding a stronger
modification restriction than provided by the Apache License), and it must
successfully demonstrate compatibility by passing a suite of interoperability
tests, run against the public API of the product. In this way, the scope of
modifications is limited.

Furthermore, in the case of fast-evolving infrastructure software, it's worth
noting that keeping local changes private is not a great long-term strategy.
Maintaining a delta between code running in production and fast-evolving
upstream open source code is very costly, and gets more difficult as time
passes. Technical debt adds up quickly to a point where paying it back is
impossible. Engaging upstream to propose your local improvements and finally
getting most of them in the open source project itself is the only sane
way forward over the long run.

References
----------
.. [#OSI] https://opensource.org/licenses/alphabetical
.. [#GPLv3] https://www.gnu.org/licenses/license-list.html#apache2
.. [#DFSG] https://en.wikipedia.org/wiki/Debian_Free_Software_Guidelines
.. [#apachev2] https://www.apache.org/licenses/LICENSE-2.0
.. [#OSCLA] https://wiki.openstack.org/wiki/OpenStackAndItsCLA
.. [#CLAvDCO] https://opensource.com/article/18/3/cla-vs-dco-whats-difference
