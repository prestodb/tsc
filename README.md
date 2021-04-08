# Presto Technical Steering Committee (TSC)

The Presto TSC will be responsible for all technical oversight of the open source Project. 

## Presto Technical Charter

The Presto Technical Charter is located in [CHARTER.md](CHARTER.md)

## Collaboration Tools

### Mailing List

The TSC for Presto Foundation can be reached at their [mailing list](https://lists.prestodb.io/g/presto-tsc).

### Slack

The Presto Foundation maintains a [Slack Workspace](https://join.slack.com/t/prestodb/shared_invite/enQtNTQ3NjU2MTYyNDA2LTYyOTg3MzUyMWE1YTI3Njc5YjgxZjNiYTgxODAzYjI5YWMwYWE0MTZjYWFhNGMwNjczYjI3N2JhM2ExMGJlMWM) for communication and collaboration. The [Presto Foundation Slack Workspace](https://join.slack.com/t/prestodb/shared_invite/enQtNTQ3NjU2MTYyNDA2LTYyOTg3MzUyMWE1YTI3Njc5YjgxZjNiYTgxODAzYjI5YWMwYWE0MTZjYWFhNGMwNjczYjI3N2JhM2ExMGJlMWM) is open for anyone to join. 

Once you join the The [Presto Foundation Slack Workspace](https://join.slack.com/t/prestodb/shared_invite/enQtNTQ3NjU2MTYyNDA2LTYyOTg3MzUyMWE1YTI3Njc5YjgxZjNiYTgxODAzYjI5YWMwYWE0MTZjYWFhNGMwNjczYjI3N2JhM2ExMGJlMWM), you can participate in any public channels.

### Calendars and Meetings

The Presto Foundation maintains a [public calendar](https://calendar.google.com/calendar/embed?src=linuxfoundation.org_vrjlva5b0u73ps75fvnv5sasi4%40group.calendar.google.com&ctz=America%2FChicago) for TSC meetings. These meetings are open for anyone to join.

### CLA

Everyone must sign the Presto CLA prior to making a contribution. You may either sign the CLA on your own, or your company can sign it for you. At a high level, if you aren't covered by a CLA, you will be notified the first time you open a PR. Please see our [documentation on the process](./CLA.md).

## Members

The TSC voting members are initially the [Project’s Committers](https://github.com/prestodb/presto/wiki/committers), and the current TSC chair is Tim Meehan ([@tdcmeehan](https://github.com/tdcmeehan)). At the inception of the project, the Committers of the Project will be as set forth within the "CONTRIBUTING" file within the Project’s code repository

https://github.com/prestodb/presto/blob/master/CONTRIBUTING.md

## Policies and procedures

The Presto TSC is governed by the [Technical Charter](CHARTER.md).  The Charter provides a foundational structure for the TSC on topics such as its scope, how to make decisions, and how to make changes to itself.  At the same time, it grants the TSC a high degree of freedom when determining how to implement the policies of the Presto Foundation.

The following policies and procedures have been adopted by the TSC.

### Making decisions

Per the [charter](CHARTER.md), wherever possible the TSC will attempt to make decisions by consensus.  In circumstances where consensus is not possible or if a vote is explicitly required, a majority (or higher, if required by the governance) of TSC voting members must approve in order for the action to proceed.  Votes will be taken over email, and documented in the next meeting.

### Merging PRs into the TSC repository

Pull requests that do not change the charter or governance of the TSC can be merged into this repository provided the following conditions have been met:

* There are no outstanding objections
* There are two approvals by TSC members
* The PR has been open for at least 72 hours

Pull requests that change governance of the TSC (excluding the charter) must be open for at least 14 days, unless consensus is reached in a meeting with quorum of voting members.

Pull requests that change the charter of the TSC must meet any requirements in the [charter](CHARTER.md).

If consensus cannot be reached, a pull request may still be landed after a vote by the Voting members to override outstanding objections.

### Fast-Tracking PRs

Special exception is made for pull requests seeking to make any of the following changes to this repository:

- Errata fixes.
- Editorial changes.
- Meeting minutes.
- Updates to team lists.
- Doc fixes.

Charter changes cannot be fast-tracked.

To propose fast-tracking a pull request, apply the ***fast-track*** label. Then add a comment that TSC members may upvote. If someone disagrees with the fast-tracking request, remove the label. Do not fast-track the pull request in that case.

The pull request may be fast-tracked if two TSC members approve the fast-tracking request. To land, the pull request itself still needs two TSC member approvals.

TSC members may request fast-tracking of pull requests they did not author. In that case only, the request itself is also one fast-track approval. Upvote the comment anyway to avoid any doubt.

### IP Policy

The [Presto Foundation IP policy](https://github.com/prestodb/tsc/blob/master/CHARTER.md#8-intellectual-property-policy) is defined in the [charter](CHARTER.md), and it applies unless an exception is explicitly approved by the TSC.

#### Copyright notices

Presto Foundation follows the [community best practice](https://www.linuxfoundation.org/blog/2020/01/copyright-notices-in-open-source-software-projects/) of not requiring contributors to add a notice to each file.

#### SPDX

Contributors are encouraged (but not required) to adopt the practice of including [SPDX short form identifiers](https://spdx.org/ids-how) in their files.
