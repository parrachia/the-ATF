---
description: Working Draft
---

# Emergency Procedures

{% hint style="info" %}
This document is a WIP and eventually this copy might become outdated, please refer to the original [here](https://docs.google.com/document/d/1u3kRsXsigK-zntM8A1PkwQPQpPNhOkPMjklgUYgeZ84/edit#).
{% endhint %}

Working Group Link:

### 1\) Essential contacts and roles

**DAOstack core and tech team**

* Tibet Sprague, tibet@daostack.io @Tibetsprague \(Pacific Time\)
* Adam Levi: CTO, [adam@daostack.io](mailto:adam@daostack.io), @leviadam
* Matan Field: Founder, matan@daostack, @MatanField
* Oren: smart contracts and audits
* Nathalia Scherer, nathalia@daostack.io@nathalia\_sch
* Patrick, [pat@daostack.io](mailto:pat@daostack.io), \(Central European Time\)

**ATF members:**

Accountability:

* Pedro Parrachia, @pedroparrachia, Brazilian Timezone
* Francesca Pick, francesca@greaterthan.works, @Franpick, Central European Time
* Dimitry Narozhny, @dmitry2018uhlan

Defense:

*  Daniel Shavit, @cryptodani, Central European Time

Discord Channel: TBC: @attackalerts

### 3\) Severity

A severity scoring is proposed: if a threat is deemed to be above a certain threshold this leads to different levels of alertness and measures, such as the Defcon system in the United States.

Level 1:

* a proposal requests for funds without a supporting document or nonsense
* Certain people vote the same way every time
* Sybill reputation request

Level 2:

* Massive collusion
* Simultaneous sybil attack

Level 3:

* Funds mysteriously disappear from the DAO
* DDOS attack on Alchemy
* Accounts voting without consent of private key owner
* Critical bug in infrastructure used to deploy the Dapp \(such as Infura\)
* Critical bugs at the blockchain level

### 2\) Alerting the DAO

A pollinator can either send a message to the tech team or ATF members listed above. They can also flag the issue in the dedicated discord channel.

This can take the form of simply raising attention to the suspicious proposal up to the compilation of a report if necessary for immediate comprehension of the issue.

Future iterations of the DAO explorer could result in customized bot alerts in order for DAO members to receive alerts about suspicious activity in the DAO.

### 4\) Timing

A response must be drafted and proposed according to the severity using the severity level as a shorthand.

* Level 1: alerts can be handled through traditional communication channels within a reasonable time frame
* Level 2: must be handled within 24 hours
* Level 3:  these should result in an immediate emergency freeze in order to assess the situation

### 5\) Exit and freezing mechanism

In case of an emergency situation with large amounts of funds at risk there would be an emergency exit button which creates a proposal to transfer funds towards a safe multi-sig wallet.

This emergency vote can be activated by a given percentage threshold of reputation requesting it.

Within the timeframe where emergency votes are active and awaiting result all token transfers could be frozen. This could be gamed to block the DAO by continuously uploading emergency exit votes. The number of alerts per person could thus be restrained.

The proposal for developing this exit mechanism can be found here:

6\) Procedure Integrity Check

This document must be conserved and linked to in a decentralized immutable manner in order to prevent malicious manipulation the information hereby contained.

A vote of the DAO must be necessary to adopt a canonical version and for any future amendments.

The necessary quorum \(for example 66.7%\)  shall be determined by the DAO to insert into the governance scheme itself as a global constraint.

### 7\) Incentivizing Defense

* In order to decentralize the role of the defense officer the DAO could put aside a “monitoring bounty” where people raising a relevant alert can get a small reward and thus incentivize all DAO members to monitor the DAO.
* Emergency votes can be incentivized via a prediction market \(such as will the DAO be affected by an emergency exit or not\), the measures of which could provide the signalling to help stakeholders assess risks affecting a DAO.

