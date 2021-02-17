################################
Build/Test/Release Working Group
################################

This repo is the home of the BTR Working Group, hosting:

- `Projects <https://github.com/openedx/build-test-release-wg/projects>`_

Discussion happens in the `BTR category at discuss.openedx.org`__.

__ https://discuss.openedx.org/c/working-groups/build-test-release/30

More details about the working group are at the `BTR page in the wiki`__.

__ https://openedx.atlassian.net/wiki/spaces/COMM/pages/1022099494/Build+-+Test+-+Release+Working+Group

================================
Role definitions and assignments
================================

*Current release: Lilac*

The following roles, with corresponding expectations and assignments, are
defined for the current release cycle.

Group Chair
===========

*Current assignee: @arbrandes*

The group chair is responsible for coordinating efforts that culminate in
getting a new release out and maintaining the current one.  In particular, the
Group Chair will:

* Manage the current release cycle in general, including making sure that
  proper deadlines are established and adhered to
* Facilitate the assignment of roles and tasks
* Coordinate the group's communication efforts, including running periodic
  meetings such as the Biweekly Meetup, and summarizing recent happenings in
  the Biweekly Update
* Try and help solve problems as they come up, bringing them to the attention
  of the right group members

Release Manager
===============

*Current assignees: @nedbat and @arbrandes*

The Release Manager is responsible for the actual cutting of a release, which,
in essence, includes following the steps in the `Process to Create an Open edX Release
<https://openedx.atlassian.net/wiki/spaces/COMM/pages/19662426/Process+to+Create+an+Open+edX+Release>`_.

In addition, the Release Manager will:

* Create public test or release candidate branches as required by the release process
* Merge reviewed PRs into the release master branch (for instance,
  ``koa.master``)
* Notify the Release Testing Coordinator whenever additional testing is needed
  in response to the above
* Tag releases, major and minor, at the appropriate time

Release Testing Coordinator
===========================

*Current assignee: @jfavellar90*

The Release Testing Coordinator is responsible for making sure release
candidates are tested _before_ a tag is made.  The coordinator does not
necessarily have to run tests themselves, but they will:

* Coordinate testing in general, in particular in the days leading to a timed
  release, including the bimonthly minor ones.
* Keep tabs on whatever CI is available, making sure it is running correctly
* Advocate for better testing tools and environments, when necessary
* Coordinate the reaction to test failures, such as bringing them to the
  attention of the rest of the group by opening tickets or commenting in the forum

Release Documentation Expert
============================

*Current assignee: N/A*

The Release Documentation Expert is tasked with building the Release Notes
document prior to a major release.  It involves:

* Tracking down all relevant information,
* Writing a draft document and posting it for community review with
sufficient lead time prior to a release
* Adjusting it as per the former review, and finally releasing a final version
  concomittantly with the major release itself

Bug Triager
===========

*Current assignee: @BbrSofiane*

The group's Bug Triager is, in a nutshell, responsible for proper use of
the group's `issue board
<https://github.com/openedx/build-test-release-wg/projects/1>`_.  In
particular, they will:

* Tag incoming issues with the latest release that is still affected (i.e.,
  "koa.2").
* Prioritize them (in a process that is to be defined)
* Add issues to appropriate milestones (i.e., "koa.3" or "lilac.1").
* Assist in making sure any known release bugs are tracked with individual
  issues.  I.e., if a known bug is not currently tracked, they will create an
  issue for it with relevant information.
* Bring the group's attention to any issues that warrant immediate action
* Help ping assignees when milestone deadlines are approaching


Community Liaison
=================

*Current assignee: N/A*

The Build-Test-Release Community Liaison(s) will:

* Assist the Group Chair in communicating the group's progress in the forum
* Periodically reply to community communication in the Build-Test-Release
  category
* Be on the lookout for any forum posts (i.e., not only on the
  Build-Test-Release working group category) that credibly report
  release-breaking issues, and communicate the issues to the `Bug
  Triager<#bug-triager>`_.


===========================
Historical role assignments
===========================

Koa
===

Group Chair: @regisb
Release Manager: @nedbat

Juniper
=======

Group Chair: @regisb
Release Manager: @nedbat
