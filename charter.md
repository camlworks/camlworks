# Caml Works Charter

<br>

*DRAFT*

<br>

Caml Works is a **voluntary** association of **active** open-source project
**owners** for the purpose of providing long-term project **continuity**.

The members of Caml Works are interested in a large, independent, grass-roots
community of OCaml users and developers, with a large variety of cooperating
and competing projects. Caml Works seeks to address one issue that arises as
such projects become increasingly successful, which limits their growth:
uncertainty about the continued availability of their owners.

Caml Works seeks to address this issue without interfering with project owners'
ownership rights in any way, and without interfering in any way with the owners'
ability to derive benefit from the success of their projects.

<br>
<br>

*For project owners*

<br>

## 1. Continuity

The only purpose of Caml Works is to provide a backup in case a project's owner
becomes unavailable for an extended period of time.

Project owners grant Caml Works administrative access to their projects. If a
project owner becomes absent for, say, three months, Caml Works can choose
people to merge bugfixes and do a release of the project. In case of a longer
absence, for example, six months, Caml Works can choose a maintainer for the
project from the project's own community, or take other steps to make sure the
project continues to work technically and organizationally, to reduce
uncertainty and indecision.

Caml Works does not otherwise use the administrative rights granted by owners to
their projects, except by explicit mutual agreement.

Caml Works should, within reason, mimic the style in which the project was run
by the owner. The project should continue to use the same communication
channels, URLs, and interact with the project's community in approximately the
same way, avoiding any unnecessary disruption.

Projects are welcome to have their own ownership structure and succession
plans. These take precedence over Caml Works.

<br>

## 2. Ownership

Project owners retain full ownership and control of their projects and cannot be
separated from their projects by Caml Works in any way, except by explicit
mutual agreement.

Projects can be disassociated from Caml Works by their owners at any time for
any reason, especially including if this charter changes in a way that is not
acceptable to a project owner.

Unless explicitly agreed otherwise, project owners remain owners during an
absence, and can resume their active ownership of their projects upon return.

<br>

## 3. Activity

Caml Works is for active project owners, and growing projects whose owners see
benefit to their projects having a degree of institutional backup.

Project owners advertise their projects, involve their stakeholders, develop
their projects' user and contributor bases, communities, communication
channels, and spread technical knowledge about their project.

Indeed, in case of the absence of a project owner, Caml Works would likely seek
a maintainer from the project's own community, and this is made easier by the
owner having developed it. In other words, Caml Works does not provide a pool
of backup maintainers, but a pool of backup adminstrators that can choose a
maintainer, though these pools may overlap in practice.

Note that this also means that Caml Works is not obligated to actively maintain
a project to the same extent as an absent owner. Rather, Caml Works is
obligated to help a project's interested community continue the project without
undue disruption, but the speed at which the project continues to develop will
naturally depend on the project's remaining community.

Project owners are welcome to seek funding for their projects from any sources,
associate with anybody, whether also involved with Caml Works or not, and
otherwise pursue the success of their projects in any reasonable way.

Likewise, maintainers chosen by Caml Works in the event of the extended absence
of project owners can work with funding and should continue to pursue the
success of the projects in any reasonable way, but subject to this charter's
requirement of not causing any undue disruption for the project's community, by
continuing to work in the same style as the owner.

<br>

## 4. Operation

Caml Works operates the [camlworks](https://github.com/camlworks) organization
on GitHub. This organization is optional for project owners. Its primary
purpose is to make it easy for owners to grant Caml Works backup administrative
access to projects, by moving their projects into it.

It is also possible for project owners to grant access to projects separately,
without moving their projects to the GitHub organization, including if the
projects are hosted on a different platform.

For a project associated with Caml Works, the project owner:

1. Publicly states that they are participating in Caml Works, whether by
   transferring the project to the camlworks org, by a note at the bottom of the
   README, or otherwise.
2. Grants Caml Works members sufficient access rights to fully administer the
   project.

In the event of the extended absence of the owner, Caml Works members will take
steps as described in the rest of this charter. The public statement (1) is
needed for third parties to be able to confirm that the owner has indeed
allowed Caml Works to act on their behalf in accordance with this charter,
using the access rights (2).

If a project's owner chooses to disassociate a project from Caml Works, and the
project is hosted under the camlworks org, Caml Works members must assist the
project owner with transferring the project out of the org.

<br>

## 5. Protection of Caml Works

Caml Works does not have a code of conduct and does not itself encourage project
owners to adopt any particular code of conduct, except as they see fit.

However, in the extremely unlikely case that the actions of a particular project
owner could cause extensive damage to the reputation of Caml Works, Caml Works
can disassociate itself from the owner and, therefore, their projects. The
owner still retains ownership of their projects.

Note that this section exists only for extreme cases. These kinds of actions
have never actually been observed in the OCaml community by the authors of this
charter as of the time of its writing.

Internally, rather than a code of conduct, Caml Works itself is vaguely
governed by long-established norms of kindness and hospitality that are
widespread across all major enduring cultures, religions, and philosphical
movements worldwide, and Caml Works does not seek to introduce or subscribe to
anything else in this regard.

<br>
<br>

*The internals of Caml Works*

<br>

## 6. Members

Caml Works *members* are a pool of backup administrators for projects associated
with Caml Works.

Members are drawn from project owners, major contributors from projects'
communities, representatives of projects' institutional users, major
decision-makers and contributors in the OCaml community at large, long-standing
opam repository maintainers, and other such pools. Note that not every project
owner has to be a member, though, typically, if a project is associated with
Caml Works, its owner is qualified to be a member.

Caml Works members must have a solid professional reputation and a long-standing
and ongoing productive association with OCaml, whether as open-source
contributors or as users.

Anyone can nominate potential members, but the nominations of project owners
should be considered especially, as project owners have the best knowledge of
their projects' communities. New members are accepted by the Caml Works chair.

<br>

## 7. Projects

Decisions about associating Caml Works with a project or taking action on a
project whose owner is absent are taken by informally gathered groups of the
members of Caml Works, in accordance with their interests and expertise. For
example, a project can be associated with Caml Works if there are at least two
or three members that would be interested, ready, and have sufficient knowledge
of its community to administer it if needed. This can include new members from
that project's community nominated by the project owner during discussions about
associating.

Interested members should decide about associating Caml Works with a project
based on its overall high quality, the reputation and general reliability of
its owner, its ability to address a need in the OCaml community, whether it has
a developing user and contributor base. In general, a project associated with
Caml Works should have a high ratio of quality to the amount of non-owner
maintenance it is likely to need. Another factor in favor of associating with a
project is a large pool of potential maintainers.

Mutually competing and incompatible projects may be associated with Caml Works.
Caml Works doesn't seek to create a consistent set of tools and libraries, but
to help widely develop the OCaml community, including through direct
competition of well-developing, active projects.

The rest of the members of Caml Works are available to provide an additional
backup in case members with expertise are unavailable.

<br>

## 8. Chair

The chair of Caml Works is a final backup for the decisions of Caml Works.

Note that none of the members, nor the chair of Caml Works, can make any
decisions within projects, except in the extended absence of their owners in
accordance with the rest of this charter. The chair and members only make
decisions internally to Caml Works.

The chair of Caml Works must nominate a sequence of delegates from among the
members, to act as the chair in case of the extended absence of the chair. The
chair of Caml Works must grant delegates administrative access rights to
everything uesd by Caml Works itself: the GitHub organization and all of Caml
Works' public communication channels.

<br>

## 9. Publication

This charter is [published](https://github.com/camlworks/camlworks) on GitHub.
Decisions about changing the charter, associating with projects, disassociating
from projects, taking action on a project, accepting new members, and
nominating the delegates of the chair, are discussed and communicated in Caml
Works' public channel: [on GitHub](https://github.com/camlworks/camlworks).
Decisions are made on the basis of the rough consensus of interested members.
The chair facilitates the discussions. All discussions are offered due time.

Members don't have to participate in discussions they are not interested in.

If a group of members forms informally, upon need, to address an issue with a
project, and they would not like the overhead of running a wide discussion,
they may choose to notify the chair, and the chair must notify the rest of the
members in at least the public channel, and may notify certain likely
interested members additionally otherwise.

Also published on GitHub are the lists of associated projects, Caml Works
members, the chair, and the delegates.
