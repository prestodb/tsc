# Presto Native Worker Working Group Governance

This document describes the basic governance principles for the Presto Native Worker Working Group (the “Native Worker WG”).

The Native Worker WG operates as a working group under the [Presto Technical Charter](https://github.com/prestodb/foundation/blob/main/Presto%20Technical%20Charter%2020191015.pdf), which describes the responsibilities of the Presto Technical Steering Committee (the “TSC”). The Native Worker WG is established by the TSC as a working group pursuant to the Technical Charter. Accordingly, the Native Worker WG will operate in accordance with the Technical Charter and Presto’s other policies and procedures, supplemented by the details below.

## Purpose

Develop and maintain an architectural roadmap and tackle integration issues for the Native Worker project, a project for rewriting Presto workers in C++ using the Velox library.

## Scope

* Discuss and resolve integration problems for the Native Worker project, both in standard Presto and Presto on Spark.
* Explore and plan future developments with the Native Worker project.
* Develop a comprehensive architectural roadmap for the Native Worker project, including:
    * Integration with the Connector API
    * Resource management of native clusters
    * Remote function support
    * Constant folding support
    * Configuration and documentation related to the new C++ workers.
* Provide a forum for general Velox project discussions when appropriate and when there is time for such discussions.

## Principles

* **Openness** and **Transparency**:
  * Meetings of the Native Worker WG shall be open to all participants who are dedicated to the future development of the Native Worker project.
  * Decisions of the Native Worker WG will be discussed openly in meetings, mailing list discussions, and/or issue threads.
* **Neutrality**:
  * The Native Worker WG should operate in a manner which prioritizes the best interests of the Presto project ecosystem as a whole, and which does not privilege any particular vendor or distributor of Presto-related goods and services.
  * All activities of the Native Worker WG shall comply at all times with the [Antitrust Policy of The Linux Foundation](https://www.linuxfoundation.org/antitrust-policy/).
* **Technical merit**:
  * Decisions on roadmap items should be based on technical merit, in light of the goals of aligning with the Presto project codebase and fitting with reasonable expectations of end users of Presto.
  * Participants in discussions should have the opportunity to share, discuss and advocate for the merit of their views. However, not all views will necessarily be followed or implemented.
* **Objectivity**:
  * Roadmap items should be based on objectively-measurable criteria, rather than subjective considerations requiring personal evaluation and determination.

## Governance
* **Working Group**:
  * The TSC is establishing the Native Worker WG as a working group of the TSC, pursuant to section 2(h)(iv) of the Presto Technical Charter.
* **Chairperson**:
  * The TSC will appoint an initial Chairperson of the Native Worker WG.
  * The TSC may, in its discretion, remove the Chairperson and/or appoint a new Chairperson of the Native Worker WG.
  * The current Chairperson will be listed in this document in the section below.
    * Chairperson: [Aditi Pandit](https://github.com/aditi-pandit)
  * The Chairperson shall be responsible for:
    * scheduling regular meetings of the Native Worker WG community;
    * facilitating open discussion among Native Worker WG community participants;
    * assisting the Native Worker WG community to seek to reach consensus;
    * recording decisions that are reached by the Native Worker WG community;
    * documenting areas of disagreement where consensus cannot be reached, for escalation to the TSC; and
    * keeping the TSC regularly informed about the status of the Native Worker WG’s efforts.
  * The Chairperson shall not be responsible for:
    * deciding the outcome of technical decisions if consensus cannot be reached.
* **Meetings**:
  * Participants in the meetings shall comply with the [Presto Foundation Code of Conduct](https://github.com/prestodb/tsc/blob/master/CODE_OF_CONDUCT.md) and all other policies of the Presto Foundation and The Linux Foundation.
* **Decisions**:
  * The Native Worker WG aims to operate as a consensus-based community.
  * If there are any decisions where consensus cannot be reached, the Chairperson may escalate the decision to the TSC to resolve the decision according to the Technical Charter.
* **Amendments**:
  * The TSC may, in its discretion, amend this Working Group Governance document from time to time.
