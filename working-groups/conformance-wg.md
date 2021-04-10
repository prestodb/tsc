# Presto Conformance Working Group Governance

This document describes the basic governance principles for the Presto Conformance Working Group (the “Conformance WG”).

The Conformance WG operates as a working group under the [Presto Technical Charter](https://github.com/prestodb/foundation/blob/main/Presto%20Technical%20Charter%2020191015.pdf), which describes the responsibilities of the Presto Technical Steering Committee (the “TSC”). The Conformance WG is established by the TSC as a working group pursuant to the Technical Charter. Accordingly, the Conformance WG will operate in accordance with the Technical Charter and Presto’s other policies and procedures, supplemented by the details below.

## Purpose

Coordinate the development and ongoing maintenance of the conformance program for Presto.

## Scope

* Establish the conformance definition for downstream implementations of Presto and/or other tools built to interoperate with Presto, for final approval by the TSC.
* Develop a conformance test suite to provide a "pass" or "fail" result based on the conformance definition, for final approval by the TSC.
* Draft the “Conformance Guide” documentation describing the conformance program testing process.
* Work with the TSC and Linux Foundation staff to establish a process by which participants in the Presto conformance program will demonstrate the conformance of their products and services.
* Update the conformance definition and test suite on an ongoing basis to maintain alignment with new significant releases of Presto.

## Out of Scope

* Business plans relating to how conformance program participants will sell or license their products or services.
* Compliance with any requirements other than technical interoperability and compatibility requirements that will comprise the conformance definition.
* Establishing the terms and conditions for the conformance program.
  * The terms and conditions will be established and maintained by Linux Foundation staff.

## Principles

* **Openness** and **Transparency**:
  * Meetings of the Conformance WG shall be open to all participants.
  * Decisions of the Conformance WG will be discussed openly in meetings, mailing list discussions, and/or publicly-visible issue threads.
* **Neutrality**:
  * The Conformance WG should include participants from multiple vendors, users and stakeholders.
  * The Conformance WG should operate in a manner which prioritizes the best interests of the Presto project ecosystem as a whole, and which does not privilege any particular vendor or distributor of Presto-related goods and services.
  * All activities of the Conformance WG shall comply at all times with the [Antitrust Policy of The Linux Foundation](https://www.linuxfoundation.org/antitrust-policy/).
* **Technical merit**:
  * Decisions on what is included in, or excluded from, the conformance definition and test suite should be based on technical merit, in light of the goals of aligning with the Presto project codebase and fitting with reasonable expectations of end users of Presto.
  * Participants in discussions should have the opportunity to share, discuss and advocate for the merit of their views. However, not all views will necessarily be followed or implemented.
* **Objectivity**:
  * To the extent possible, conformance definition elements should be based on objectively-measurable criteria, rather than subjective considerations requiring personal evaluation and determination.

## Governance
* **Working Group**:
  * The TSC is establishing the Conformance WG as a working group of the TSC, pursuant to section 2(h)(iv) of the Presto Technical Charter.
* **Chairperson**:
  * The TSC will appoint an initial Chairperson of the Conformance WG.
  * The TSC may, in its discretion, remove the Chairperson and/or appoint a new Chairperson of the Conformance WG.
  * The current Chairperson will be listed on the [Conformance Program Working Group Github Project](https://github.com/prestodb/conformance-wg).
  * The Chairperson shall be responsible for:
    * scheduling regular meetings of the Conformance WG community;
    * facilitating open discussion among Conformance WG community participants;
    * assisting the Conformance WG community to seek to reach consensus;
    * recording decisions that are reached by the Conformance WG community;
    * documenting areas of disagreement where consensus cannot be reached, for escalation to the TSC; and
    * keeping the TSC regularly informed about the status of the Conformance WG’s efforts, including when the Conformance WG has readied the draft conformance definition and conformance test suite for TSC approval.
  * The Chairperson shall not be responsible for:
    * making sole decisions about what is, or is not, included in the conformance definition or conformance test suite;
    * making decisions about whether any particular vendor or distributor has passed the conformance tests; or
    * deciding the outcome of technical decisions if consensus cannot be reached.
* **Meetings**:
  * As with all other Presto technical meetings, all meetings of the Conformance WG shall be open to the public.
  * Participants in the meetings shall comply with the [Presto Foundation Code of Conduct](https://github.com/prestodb/tsc/blob/master/CODE_OF_CONDUCT.md) and all other policies of the Presto Foundation and The Linux Foundation.
* **Decisions**:
  * The Conformance WG aims to operate as a consensus-based community.
  * If there are any decisions where consensus cannot be reached, the Chairperson may escalate the decision to the TSC to resolve the decision according to the Technical Charter.
* **Final Approval**:
  * When the Conformance WG reaches consensus that the conformance definition and conformance test suite are ready for initial release, as well as for subsequent updates, the Chairperson shall notify the TSC.
  * The TSC retains final decision-making authority over whether the conformance definition and conformance test suite are ready for release.
  * The Governing Board of the Presto Foundation, as part of its oversight of the Presto trademarks, retains final decision-making authority over the launch of the Presto conformance program.
* **Amendments**:
  * The TSC may, in its discretion, amend this Working Group Governance document from time to time.
