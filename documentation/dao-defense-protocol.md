---
description: Draft v0.1
---

# Defense Protocol

[source](https://docs.google.com/document/d/1_99skdvorcwPZllm97bOSak4LSn0z6GtbjSjD9jT4Ao/edit)  


Scope:  
  
The DAO Defense Protocol lists the necessary steps to take in order to prepare, monitor, alert, come to a consensus and defend Genesis and other DAOs from an attack. Genesis members are invited to comment, criticize and contribute to this manual.  
This document follows the “pilot in the plane” principle: focusing on activities that are within our control. No system is foolproof and the question is not if but when an attack will be launched. We might never know how exactly an attack might occur but being able to categorize and detect scenarios faster and draw contingency and response plans will be of crucial help when it finally happens.  


This document is relevant to the Genesis protocol v1 and will be amended as the protocol gets upgraded.  


The DAO Defense Protocol will be submitted to a vote by the Genesis DAO for eventual adoption.  


1. Attack types

An attack on a DAO is not always an outright act of theft but could be the ability to game a system to move funds destined for common good/entreprise into individual hands without consensus of the DAO.  


The exploits can be of a technical, protocolar or political order and procedures and chain of command for a unified response must be adapted to each type.  


Technical attacks are based on bugs in the various technical layers \(smart contracts, multi-sig wallets, Metamask, Ethereum network etc..\).  


Protocolar attacks refer to attacks on the “protocol “itself” how any DAO protocol manages the flow of information, decisions and flaws in the crypto-economic incentive structure of a consensus mechanism. In the case of Genesis this would mainly revolve around bugs in Arc and gaming Holographic Consensus.  


Political exploits are a “feature” not a bug of DAOstack or any other DAO tech stack; to map out so called “social” and “governance” attacks we must resort to comparative politics and find the advantages and flaws in each system and which emergent properties are observed when each of these are ported to on-chain decentralized environment.  


For example if the DAO members follow a Pareto distribution of efforts and rewards \(80% of rep and budget goes to the top 20% of members\) a DAO left to its own devices would inevitably revert to a centralized reputation system in the absence of redistribution/decay/logarithmic transformation function of reputation.  


Seen under this lens any complete taxonomy of attacks must takes into account the lot of political, crypto-economic and social aspects of collective decision making mechanisms.  


In order to remain compilable and readable given a reasonable amount of time and budget for the purposes of the Genesis DAO the list will prioritize research into exploits of the given governance scheme.  


Governance could be seen as an encroachment in itself on the sovereignty of the individual and the benefits one gets in return for this sacrifice has been at the basis of the “social contract” theory.  


Any DAO is in principle a voluntary association of people and we are not in the presence of a coercive entity such as the State. Y yet this protocol by listing attacks surfaces can help DAOs navigate and choose for themselves between different models of governance.  
  


* Sybil/sock-puppets
* Smart contract bugs

The ATF will consult with the DAOstack technical team in order to determine how funds are managed in the ARC framework.  


Insert Solidity and DAO related frequent bugs  


[https://ethereum-contract-security-techniques-an d-tips.readthedocs.io/en/latest/known\_attacks/](https://ethereum-contract-security-techniques-and-tips.readthedocs.io/en/latest/known_attacks/)

![](https://lh3.googleusercontent.com/HA2DrYsEKvo4If_eUO8P_5eYVD2ai7HLEIdCj2JITMZcsR7sfIVhpcx3U8IFWT-IBFLE_W2Bl4IvwlcwcslT674o9jbXAR4_WtwbafbonyLyFv6b_9tyx3YsA6Pu9wE53bmIVOsg)

The DAO Attack  


* Arc based bugs
*  Individual or collusion based 51% attack

This attack occurs when an individual or group of attackers gain control of over 50% a DAOs REP.  


In DAOs with no reputation decay, proposals can pass with a much lower quorum of votes. This means the threshold for a 51% attack becomes much lower \(12-15% of REP in current Genesis Alpha\).  


The ATF should monitor concentrations of reputation and members voting in the same direction at similar times.  
  
  


* Prediction market based \(decentralized lobbying\)

An attacker who cares about political sway over economic considerations  can with enough funding spam the boosted queue and force the DAO to only consider issues relevant to themhimself.  


It could also be used by a competing organization to spam the boosted queue with dummy proposals in order to significantly slow down decision making.  


* Ostracism attack:The DAO voting the banning of an individual, a feature not a bug but could lead to concentrations of power and tyranny of majority.
* Editing Proposals to game the prediction market

Once proposals are editable an attacker might make an untitled or incomplete proposal in the hope that people predict it will fail then edit it, make it adopted and scoop on the GEN.  


* Off-chain or automated bribery

 An attacker could buy off-chain the right to public keys with enough reputation to materially change the outcome of votes.  


This can take the form of an automated bribery contract where people are compensated for the voting attempt in case of failure and given a proportion of the benefits  


* Spamming
* Miner front running:

A polity adopting a DAO protocol for it’s governance would be gameable by miner front running which could profit from off-chain markets arbitrage \(such as stock market or exchanges\) by knowing a few minutes or seconds in advance the DAOs decision.  


* Centralized Hosting of documents:

With a certain number of people getting edit rights on this collaborative document, someone could change information about procedure to follow to slow down response and wreak havoc.  
  


* Centralized Storage of proposals and reference documentation

If most proposals/timelines/review documents are stored using centralized services \(such as Google Docs\) an attacker could easily modify documents and sow confusion within a DAO.  


* Fake proposal

A proposer could make a proposal for a sizable budget for which there is popular demand and not execute.  


The DAO has no way to escrow fund distribution according to execution performance until a dispute resolution mechanism is integrated. Until then it would be recommended to report scams and flag the public address and social identity.  


To avoid abuse by a centralized entity this list will not judge the quality of execution but only report truly suspicious or proven cases of fraud.  


A procedure will be established to prepare a list of potential penalties for malicious actors.  


*  Governance crisis

A DAO could simply find itself with a significant amount of members or a specific subgroup not wishing to be part of the DAO anymore but that want to exert a right on a part of the funds or value created by the DAO.

This could precipitate a crisis where interfering with the proposal creation and voting process become commonplace.  


* Centralized Key Assignment

When a DAO model is adopted by a traditional organization they must be sure not to assign private keys to members from a centralized entity making it vulnerable to account and DAO takeover.  


* Ranked proposals intransitivity attack with vote switching \(Condorcet Paradox\)

In the presence of three or more options where preferences are A&gt;B and B&gt;C but A&lt;C and where votes can switch after a deadline extension there might not be a consensus reached in polynomial time as each stage will have a new potential winner and preference reversal.

This can then lead to infinite votes that block GEN and the boosted queue.  


* Miner front running: Ethereum block miners could front run and know the content of blocks before execution which can lead to insider trading considering DAO critical decisions.
*  Protocol/Core dev team attack

PThe protocol developpement must be as decentralized and transparent as possible to avoid having thea voluntary inclusion of an attack vector in the protocol.  


*  Tyranny of the majority attack

In a majoritarian democracy governance scheme we can end with a tyranny of the majority and expropriation of the DAO’s budget from the collective to the majority group.

*  ATF attack \(quis custodiet ipsos custodes problem\)

The ATF or an impersonator could mislead the DAO into taking an action in the favor of the attacker. ATF members will have to be the subject of particularly scrupulous security measure in order to mitigate this risk. This is also slightly mitigated by the fact that only one person could tip off the rest of the DAO.  


The ATF in conjunction with the wider DAO will determine ways to render the ATF accountable and transparent.  


The ATF will consult with the technical team of DAOstack in order to appreciate the likelihood of each risk.  


*  Targeted freezes

An attacker with many unredeemed transactions and strategically delay redemption in order to block disbursement of the budget by another group with immediate cash needs.  


* Local Knowledge Problem
* Disinformation Campaign

An attacker could influence voters by spreading false information off-chain pertaining to a proposal or the general context in which a DAO evolves.  
  
  


Insert 2 axis chart of attack types according to probability and severity  


1. Monitoring Capabilities

a\) Human warning  


Any member of the DAO can alert the ATF of a suspected attack on this channel @TBD or the entire DAO if urgent on the specific Alert Discord channel.  


b\) Automated warning  


The DAO should fund the development of a dashboard that provides fast and intuitive visualization of Genesis and future DAOs KPIs: members, reputation distribution, numbers of proposals opened, DAO budget and GEN staked, Ethereum, reputation and GEN unredeemed, votes during the selected timeframe \(hour, day, week\). This will allow DAO and ATF members to quickly grasp and analyze the DAOs behavior.  


The DAO will conduct a trial and eventually pay for smart contract monitoring systems which can send a warning message when unusual transactions are detected. This can include phenomenons such as a transaction where a large portion of the DAOs funds are being moved, being several standard deviations higher/lower than usual,  a multitude of transactions originating from multiple accounts  


1. Consensus formation and response crafting procedure

Insert flowchart of information distribution and decision making process  


Genesis attack flow: The ATF will consult internally and with the rest of the DAO to determine the procedure in case of an attack on Genesis.  


It could prove prescient to develop a scale of defense readiness analogous to the DEFCON scale in order to keep different actors battle ready if there is a suspicion of a wave instead of a single attack.  


Define standard and emergency procedure and timeline according to attack severity.  


1. Defense strategies
2. Counter-attacks

In the case of a technical attack the DAO might be able to finance or conduct with their own members a counter attack such as in the story of the DAO and recover a portion of lost funds.

A list of technical experts and a common emergency pot might be reserved by the DAO to quickly activate this possibility.  


1. Proposals

Useful for sending back reputation, too slow to reverse ETH and GEN transactions. There might be a case where the DAO can collectively \(given a minimum quorum\) decide to modify the proposal voting time.  


1. DAO Fork

Any DAO could replicate it’s reputation endowment onto a newly forked replica DAO, this would however not lead to the recovery of lost ETH and GEN funds except in the case of the blockchain network itself forking as in the case of “The DAO”.  


This could be very effective when ETH budgets are allocated to the DAO in small portions so a hack would only lead to the theft of a minimal portion of the DAO’s lifetime endowment and transfering new funds to the safe DAO would be made with minimal friction.  


Conveniently as the attacked DAOs state history is stored on a Blockchain it is possible to have a decentralized transparent point of reference to revert the parameters to.  


Being able to query a DAOs state at any time with a GUI desktop tool or webapp would make it very easy to not only fork in case of attack but also draw interesting inferences about a DAOs activity for empirical and anecdotal research concerning decentralized governance.  


1. Legal

The DAO, especially if used within or in supplement of a  traditional organization can resort to the help of traditional justice system and security apparatus.  


This would be especially relevant for disputes relating to ownership of value or IP or during a hack by a group of recognized hackers.  


e\) Emergency Fund repatriation/Dead-man’s switch  


The DAO might find it useful consider a measure to quickly and under very specific conditions move the funds to another multi-sig wallet in case of suspected or ongoing attack.  
  


1. Preparation
2. Members and dev team education

This document will form the basis for spreading knowledge about attack risks. Specific documents and procedures could be distributed to different actors in a DAO.  


1. Community feedback and participation

Members of the community can at any time add an attack to this list or relate it to the community. It could make sense to reward members that prove to be particularly good at find flaws in the system and reporting them.  


1. Simulations/Drills

Wargames could be prepared in order to simulate how an attack would occur, with precalculated decision trees and payoffs.  


1. Actors role definition

When each member \(of the DAO, the ATF or the DAOstack team\) knows the role they play in an emergency situation it becomes much easier not to cede to panic and take effective action as soon as possible.  


1. “Preview” DAO before pushing critical code updates

A DAO with the same parameters as a live one can be deployed with limited funds before live deployment in order to test out the structure.  


1. Emergency contacts

Different experts will have an address to which DAO and ATF members can turn to in case of an attack or unusual activity. The listed contact would ideally be separate from the main address to risk revealing critical accounts to attackers  


1. White hat bounties

Bounties will be reserved and distributed by the DAO to hackers that report bugs. As the amounts of ETH and GEN taken from the DAO will be far in excess of bounties this could also include reputation as an additional incentive.  


Notes on asymmetric information: If an attacker has full information on the defense strategy of a DAO and can anticipate all it’s moves it might be able to gain an unfair advantage over it.

The DAO must thus consider the degree of confidentiality on the part or totality or information disclosed in this document or developed by the ATF.  


