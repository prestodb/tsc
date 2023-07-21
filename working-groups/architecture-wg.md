# Presto Architecture Working Group Governance

This document describes the basic governance principles for the Presto Architecture Working Group (the “Architecture WG”).

The Architecture WG operates as a working group under the [Presto Technical Charter](https://github.com/prestodb/foundation/blob/main/Presto%20Technical%20Charter%2020191015.pdf), which describes the responsibilities of the Presto Technical Steering Committee (the “TSC”). The Architecture WG is established by the TSC as a working group pursuant to the Technical Charter. Accordingly, the Architecture WG will operate in accordance with the Technical Charter and Presto’s other policies and procedures, supplemented by the details below.

## Purpose

Develop and maintain a public open source roadmap of technical work for the Presto project.

## Scope

* The ultimate output of the Architecture WG is a publicly accessible roadmap of technical work for the Presto project.  Once this roadmap is completed, it shall be updated at a 
set cadence to be determined by the Architecture WG.  It will always be publicly accessible.
  * As of writing, some examples of topics that will come under the Architecture WG's purview include:
    * Determination if an SPI is required for native workers.
    * Determination if an update to the Java SPI is required in light of the native worker SPI.
    * Determination of the scope of optimizer improvements and refactoring.
    * Determination if an update to any public API is required.
    * Determination of scope of work for Presto on Spark, native execution, optimizations, resource management techniques, and other topics.
  * The roadmap will consist of a list of topics, their relative importance (expressed in a way that can be ordered), a link (which may be a placeholder) to a design document, and
a link to an issue which describes the topic in detail for the community.
  * The Architecture WG may also delegate particular individuals to work on detailed plans and ask for updates as time progresses.
* The Architecture WG will not be responsible for the day-to-day management of the Presto project, including releases, overall governance, and community disputes, which is the responsibility of the TSC.
* The Architecture WG will not be responsible for the day-to-day management of the Presto project’s codebase, which is the responsibility of the Presto committers.

## Principles

* **Openness** and **Transparency**:
    * Meetings of the Architecture WG shall be open to all participants who are dedicated to the future development of Presto.
    * Decisions of the Architecture WG will be discussed openly in meetings, mailing list discussions, and/or issue threads.
* **Neutrality**:
    * The Architecture WG should operate in a manner which prioritizes the best interests of the Presto project ecosystem as a whole, and which does not privilege any particular vendor or distributor of Presto-related goods and services.
    * All activities of the Architecture WG shall comply at all times with the [Antitrust Policy of The Linux Foundation](https://www.linuxfoundation.org/antitrust-policy/).
* **Technical merit**:
    * Decisions on roadmap items should be based on technical merit, in light of the goals of aligning with the Presto project codebase and fitting with reasonable expectations of end users of Presto.
    * Participants in discussions should have the opportunity to share, discuss and advocate for the merit of their views. However, not all views will necessarily be followed or implemented.
* **Objectivity**:
    * Roadmap items should be based on objectively-measurable criteria, rather than subjective considerations requiring personal evaluation and determination.

## Governance
* **Working Group**:
    * The TSC is establishing the Architecture WG as a working group of the TSC, pursuant to section 2(h)(iv) of the Presto Technical Charter.
* **Chairperson**:
    * The TSC will appoint an initial Chairperson of the Architecture WG.
    * The TSC may, in its discretion, remove the Chairperson and/or appoint a new Chairperson of the Architecture WG.
    * The current Chairperson will be listed in this document in the section below.
      * Chairperson: [Tim Meehan](https://github.com/tdcmeehan)
    * The Chairperson shall be responsible for:
        * scheduling regular meetings of the Architecture WG community;
        * facilitating open discussion among Architecture WG community participants;
        * assisting the Architecture WG community to seek to reach consensus;
        * recording decisions that are reached by the Architecture WG community;
        * documenting areas of disagreement where consensus cannot be reached, for escalation to the TSC; and
        * keeping the TSC regularly informed about the status of the Architecture WG’s efforts.
    * The Chairperson shall not be responsible for:
        * deciding the outcome of technical decisions if consensus cannot be reached.
* **Meetings**:
    * Participants in the meetings shall comply with the [Presto Foundation Code of Conduct](https://github.com/prestodb/tsc/blob/master/CODE_OF_CONDUCT.md) and all other policies of the Presto Foundation and The Linux Foundation.
* **Decisions**:
    * The Architecture WG aims to operate as a consensus-based community.
    * If there are any decisions where consensus cannot be reached, the Chairperson may escalate the decision to the TSC to resolve the decision according to the Technical Charter.
* **Amendments**:
    * The TSC may, in its discretion, amend this Working Group Governance document from time to time.