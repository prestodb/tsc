# Presto Technical Steering Committee (TSC)

The Presto TSC will be responsible for all technical oversight of the open source Project.

## 2021 Elections

Elections are now open for all TSC seats.  If you'd like to nominate yourself, please fill out the following template and send to [operations@prestodb.io](mailto:operations@prestodb.io):

```
# TSC self-nomination

**Name:**
**Email:**

### Please provide 2-3 sentences on your involvement in the Presto project

### Please provide 3-6 sentences on what you aspire to achieve on the TSC

### Do you currently hold any formal leadership roles within the Presto community?

### Do you commit to attending the monthly TSC calls?
```

Nominations will be accepted through **Thursday, November 4th, 2021**.

## Presto Technical Charter

The Presto Technical Charter is located in [CHARTER.md](CHARTER.md)

## Collaboration Tools

### Public Mailing List

The TSC for Presto Foundation can be reached at their [mailing list](https://lists.prestodb.io/g/presto-dev). This list is intended for public technical discussions.

### Slack

The Presto Foundation maintains a [Slack Workspace](https://slack.prestodb.io) for communication and collaboration. The Slack is open for anyone to join and participate in the public channels.

### Calendars and Meetings

The Presto Foundation maintains a [public calendar](https://calendar.prestodb.io) for TSC meetings. These meetings are open for anyone to join.

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
