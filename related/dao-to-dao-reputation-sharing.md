---
description: 'Rawson, Weller (2018)'
---

# DAO to DAO Reputation Sharing

{% embed url="https://docs.google.com/document/d/18GF3f130miEsaASw-TRCHR-qRtbL8y-UsfusV7pXuZg/edit\#" %}



The following is a discussion of DAO to DAO \(D2D\) reputation sharing, specifically in relation to DAOstack’s [holographic consensus](https://medium.com/daostack/holographic-consensus-part-1-116a73ba1e1c) framework, but also applicable to other reputation-based decentralized organization \(dOrg\)\* frameworks, such as the [Colony](https://colony.io/) protocol.  


As DAOs become more popular, specifically on the Ethereum blockchain, it becomes increasingly important to give consideration to their means of bargaining; ie. politicking. A key aspect of DAOs is their unique protocological capability to dissolve and merge to any degree through the use of smart contracts.\*\* The following discussion will outline a general taxonomy of DAO strategy by discussing three separate Reputation sharing tactics DAOs may leverage as [polities](https://en.wikipedia.org/wiki/Polity) and their specific implementations.  
  
  
_\* DAO and dOrg tend to be used interchangeably, regardless of their academic particularities, and are used as such in this document.  
  
\*\* The authors eventually imagine these models as an interoperable dApp_  
  


Why should DAOs share Reputation \(REP\)?

Politics and barter require concession-making and gift-giving. REP is one of three key resources that a DAO can barter with, the other two consisting of the treasury and capability to mint more of its native token, should it possess one. Of the three resources available for barter, REP may be the most valuable resource.\* I am not aware of any empirically tested DAO valuation models for REP. Even though REP cannot be transferred from one individual address to another, it does take on new meaning when DAOs tactically use it to barter.  
  
  
Mutual concessions:

  
DAOs that enter into either bilateral partnerships or more complex alliances may allocate decision-making authority over their respective treasuries to their partner or sub-agencies.\*\* Instead of trading goods or services, they make concessions with REP. As history has demonstrated, bilateral and complex alliances can be effective concessions arrangements\*\*\* that boost network size and allow economic [gains from trade](https://en.wikipedia.org/wiki/Gains_from_trade).  
  
There are downsides to leveraging REP as concession, however: as with corporate mergers and hard forks one side may be in danger of disappearing. Given that DAO agents have limited attention, DAOs that make REP concessions may end up competing for the collective attention of their newly combined network. Together, they may optimize their combined network to be [Pareto efficient](https://en.wikipedia.org/wiki/Pareto_efficiency), but individually, DAOs may not be willing to risk their members migrating over to the partnering organization and leaving the DAO a ghost town. This risk might be mitigated by sharing only a modest amount of REP between organizations, ensuring that members will still have a stronger connection to their root organization after the REP share.  


We expect the benefit to network growth is maximized when the respective DAOs are largely dissimilar. If they share significant membership, there’s less to be gained with mutual concessions, and they ought to consider an outright merger \(to be discussed\). We believe that the best candidates for REP sharing are DAOs that maximize their ratio of:  
  
\[mission alignment\] :: \[network similarity\]  
  


  
  
\* I believe developing better DAO KPIs to measure ‘network size’ and ‘network growth rate’ would help accurate valuation.  
  
\*\* The terms ‘child DAO’ or “sub-DAO” are sometimes used here.  
  
\*\*\* You can have some more complex situations: for instance, the two orgs have separate treasuries, but DAOA holds a 51% REP stake in DAOB, while DAOB only has a 3% REP stake in DAOA; this wouldn’t be dissimilar to a [vassal state](https://en.wikipedia.org/wiki/Vassal_state).  
  
  


  
Promotions:  
  
Promotions are a common tactic to boost cryptocurrency network growth. The [airdrop](https://hackernoon.com/free-cryptocurrency-is-a-real-thing-ce1cc4936fa6) is one such example. DAOs that seek to grow their network can giveaway REP similarly.  
  
Both qualitative and eventually [quantitative](https://hive.one/) curation algorithms may be used by recruiters who seek to giveaway REP to agents or agencies whose attention increases network size or growth rate. Imagine if new DAOs--curated lists--could be algorithmically bootstrapped with a predetermined membership of the most highly curated combination of people; eg. the highest REP holders of every DAO. It’s worth mentioning that airdropping tokens has already been discussed as a [tactic for hostile network acquisition](https://medium.com/@andy_bromberg/paying-to-be-bought-a-token-network-acquisition-blueprint-a3e47d59b134); REP could be given away similarly to acquire the collective attention of another network or a select few agents.\*

  
If a DAO airdropped REP to a curated list of incredible people, how many stay and start immediately adding value to the network? What if that DAO was well endowed?

  
  
\* Special thanks to decentralized governance researcher [Pedro Parrachia](https://twitter.com/parrachia) for bringing this up.  
  
  


DAO mergers:  
  
Outright mergers of REP may be the most effective tactic for highly aligned DAOs with common network membership. We believe there will be many organizations which, with a full REP share, will be greater than their separate sums. While [token merges](https://hackernoon.com/proposing-a-framework-for-friendly-crypto-token-mergers-4601cb4d0638) are outside the scope of this REP focused discussion, it’s clear that the additional aspect of merging treasuries introduces immense bargaining complexity. We suspect DAOs will rarely retain separate tokens if they choose to merge both REP and treasury. It is likely that package deals that balance % REP allocation with tokenomics considerations will be key to dealmaking in full blown mergers.  
  
  
  


#### REP sharing models

  
  
We introduce here three different models for sharing REP, suitable for concession-making and promotions:  
  
  
Individually Proportional model  
  


This model is simple: DAOA reserves 20% of its total REP for DAOB. DAOB REP holders who vote on proposals in DAOA receive a 20% bonus to their vote equal to their proportional reputation within DAOB. The total weight of the reputation of an individual who owns DAOA REP and DAOB REP when voting in DAO A would be represented as so:  
  
REP\_WEIGHTDAO-A, User = \[ .8 \* \( REPDAO-A, User / TOTAL\_REPDAO-A \) \] + \[ .2 \* \( REPDAO-B, User / TOTAL\_REPDAO-B \) \]  


Best used in: Bilateral negotiations  
  
Additional Pros:   Easy to implement. Individually tailored by address. Resilient to both high and low participation from REP-holders in their own DAO and the partner DAO.  
  
Cons: The full REP share \(in this case, 20%\) is only used if 100% of the partner DAO’s REP participates in a vote, which will likely be rare. That means an individual proportional REP share will likely reduce the percent of total REP participation in both DAOs.  
  
  
  
“Winner Take All” Bloc Voting model

  
This model focuses on the DAO as a whole and not its individual agents by implementing a “winner take all” majority and counting DAOB as a single voting bloc. Let’s say DAOA again reserves 20% of its total REP for DAOB. The entire 20% would be allocated based off of a relative majority of participating DAOB voters. If upvotes from DAOB REP holders are greater than their downvotes on a DAOA initiative, an upvote worth  20% is applied within DAOA, and vice versa.  
  


Best used in: Complex alliances of low agent count, where always voting as an entire bloc matters; eg. an Alliance DAO sharing REP with many member DAOs, where it’s desirable for each member DAO to have a single, relatively equal-strength vote.

  
Not suited for: Bilateral negotiations.  


Cons: DAOB’s actions in DAOA are not resilient to low participation. If only a few agents from DAOB vote in DAOA, they will be controlling all of DAOB's influence in DAOA on their own. DAOB's actions in DAOA could easily be misaligned with DAOB's collective values.  


DAOA is vulnerable to being overwhelmed by DAOB if DAOA has low participation. When only a few DAOB REP holders vote on a DAOA proposal, they control 20% of DAOA’s REP, likely making them more powerful than most or all DAOA REP holders. In the case of a complex alliance with participating DAOs, however, this is mitigated.  
  
  
  


Proportionally Representative Bloc Voting model  
  


This model also has partner DAOs voting as a bloc, but allows individual representation within the bloc, which votes yes or no in proportion to REP holders’s votes. DAOB will always vote with 20% of DAOA’s total REP in any DAOB members vote on a DAOA initiative, but that 20% will be split between yes and no votes according. If 80% of DAOB’s participating voters upvote DAOA’s proposal, DAOB will vote16% yes and 4% no on the proposal.  
  
Best used in: Complex alliances of low agent count, yet allows for some proportional representation of the minority truth of DAOB within DAOA.  
  
Not suited for: Bilateral negotiations.  
  
Cons:  DAOB’s actions in DAOA are not resilient to low participation. \(same as above\)

  
DAOA is vulnerable to being overwhelmed by DAOB if DAOA has low participation. \(same as above\)

####   Future Considerations

####   

Token-value in Negotiations  


The above models can be adjusted or partially mediated by the arbitrage between their respective token values or treasury sizes, if they both possess a native token. This could be facilitated through some sort of oracle, but seems susceptible to manipulation risks.

Bridging Tradable and Non-tradable Token Voting  


Generally, more complex voting models can be created by combining REP with varying token-based governance forms. For instance, perhaps a DAO wants to ‘sell’ 10% of their REP through an auction as part of a fundraiser, either once or periodically so, opening a middle ground between the Reputation-based of DAOs like Genesis and the token-based governance of Maker or EOS.  
  
  
Delegate Model  
  


The above models can be adjusted by adding an element of delegation, or multiple delegate layers \(ie. [liquid democracy](https://github.com/DemocracyEarth/dapp)\).

#### Next Steps   

Brainstorming possible applications in the current DAO-scape

  
Between the DAOstack, Colony, and any other merit based decentralized governance frameworks, are there currently DAOs that could immediately benefit from one of these REP-share types?

  
More research  
  


* Are there other valid ways to REP share besides what are listed here, or should these be adjusted?
* How will other factors of DAOs such as their treasuries and interfaces interact with REP shares?

