# Presto Technical Steering Committee (TSC)

The Presto TSC will be responsible for all technical oversight of the open source Project.

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

The current members of the Presto TSC are:

| Name              | Github       | Term begins  | Term ends   | Affiliation |
|-------------------|--------------|--------------|-------------|-------------|
| Jay Narale        | jaystarshot  | May 21, 2024 | May 1, 2025 | Uber        |
| Andrii Rosa       | arhimondr    | May 21, 2024 | May 1, 2025 | Meta        |
| Tim Meehan        | tdcmeehan    | May 21, 2024 | May 1, 2025 | IBM         |
| Ying Su           | yingsu00     | May 21, 2024 | May 1, 2025 | IBM         |
| Aditi Pandit      | aditi-pandit | May 21, 2024 | May 1, 2025 | IBM         |
| Rebecca Schlussel | rschlussel   | May 21, 2024 | May 1, 2025 | Meta        |
| Beinan Wang       | beinan       | May 21, 2024 | May 1, 2025 | Apple       |
| Zhenxiao Luo      | zhenxiao     | May 21, 2024 | May 1, 2025 | Pinterest   |
| Amit Dutta        | amitkdutta   | May 21, 2024 | May 1, 2025 | Meta        |

TSC membership is open to Presto project committers. Prior to each election, candidates must submit a [self-nomination form](./elections/SELF_NOMINATION_TEMPLATE.md).

Beginning in 2023, the TSC has nine seats. Per the charter, TSC voting member terms are one year and elections occur semi-annually. To establish the semi-annual cadence, three TSC members will be selected by coin toss to serve an initial 1.5 year term. 

The voting process is described in the [TSC charter](https://github.com/prestodb/tsc/blob/master/CHARTER.md#3-tsc-voting).

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

Contributors are encouraged (but not required) to adopt the practice of including [SPDX short form identifiers](https://spdx.dev/about/overview/) in their files.
