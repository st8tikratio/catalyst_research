# Information
These parameters are the guidelines used to define the Catalyst processes for Fund 9

The pdf enclosed was downlaoded from [here](https://drive.google.com/file/d/1GmgwUGuZ3yE0w3usZdV-ZZw-nP8oPqX5/view)


Fund9 Catalyst Governance is the actual voting process put in place to decide
which proposal will receive funding from treasury
Table 1 summarizes main parameters to be used.
Table 1

|PARAMETER | VALUE | DESCRIPTION |
| -------- | ----- | ----------- |
| **Product/Business/Informative Parameters** | | |
| Direct Voting privacy state | Yes | Are votes public or not? |
|Fund name | Fund9 | |
| Challenges Title and Budget | [The Great Migration (from Ethereum)](https://app.ideascale.com/t/UM5UZBw7N) $500,000 | |
|                             | [DAOs <3 Cardano](https://app.ideascale.com/t/UM5UZBvaV) $1,000,000                   | |
|                             | [Legal & Financial Implementations](https://app.ideascale.com/t/UM5UZBvbn) $500,000   | |
|                             | [Developer Ecosystem](https://app.ideascale.com/t/UM5UZBvNu) $1,000,000               | |
|                             | [Dapps, Products & Integrations](https://app.ideascale.com/t/UM5UZBw78) $7,850,000    | |
|                             | [Cross-Chain Collaboration](https://app.ideascale.com/t/UM5UZBunq) $900,000           | |
|                             | [Challenge & Scouted for Students](https://app.ideascale.com/t/UM5UZBvbE) $100,000    | |
|                             | [Grow Africa, Grow Cardano](https://app.ideascale.com/t/UM5UZBuk1) $500,000           | |
|                             | [dRep improvement and onboarding](https://app.ideascale.com/t/UM5UZBvsJ) $150,000     | |
|                             | [Grow East Asia, Grow Cardano](https://app.ideascale.com/t/UM5UZBvV3) $250,000        | |
|                             | [Building (on) Blockfrost](https://app.ideascale.com/t/UM5UZBvum) $50,000             | |
| Proposals submission fee    | Free                                                                                  | Proposers can submit a proposal for discussion on Ideascale.|
| Funds under control         | 16,000,000 ada                                                                        | Fund will Control 16M ada |
| Funds MIR date              | Date + CR                                                                             | |
| Reward distribution date    | 02/Sep/2022 - 09/Sep/2022                                                             | When funding tx’s actually go out |
| Mechanism to prevent price fluctuation | Proposals will be paid the $ value they requested in ada, according to ada valuation at reward distribution date. 3,200,000ada total rewards for Voters + advisors + referrers + challenge teams will be provided according to ada valuation on reward distribution date. | |
| Fund goals | Attract more developers <p></p> Build real live solutions based on the Cardano blockchain. <p></p> Improve tooling to support human processes in Catalyst | Fund goals to be presented in the Voting App. <p></p> Survey results collected between 4/20 - 5/19. 1045 votes cast, on 31 statements, by 47 unique participants. [Results](https://pol.is/report/r4dafyewbkcrkm8c7exjb). Took top 3 by (yes minus no). Combined 2 / 26 due to similarity, taking the more general “solutions” over “applications”. Broke tie on 10 / 19 based on number of participants + disagreement.|
| Maximum proposals that can be put on the ballot | No limit | |
| Community advisor registration | Through Ideascale | Everyone can register as a Community Advisor. They can’t do CA work in the challenge they are proposing to or are involved with a proposal team.|
| Proposals registration on the blockchain | Rust/Devops dev | The registration of proposals on the blockchain will be done in the future by an elected committee. |
| Voting power threshold | 450,000,000 lovelace. (450 ada) <p></p> Communicate threshold as 500 to account for tx fees | Minimal stake threshold to become a voter, based on the efficiency benchmarks of the voting protocol. <p></p> Specific value of the voting stake threshold will be defined by the protocol benchmarks. <p></p> Note that threshold must be lowered by 50 ada from the amount stated to the community to address registration fees.|
| Registration start time | 07/Apr/2022, 12:00 UTC | Registrations made after 03/06/2021 16:00 UTC are valid. Official registration start time starts an hour after the previous Fund snapshot. | 
| Registration snapshot date | 04/Aug/2022, 11:00 UTC | | 
| Voting period start time| 11/Aug/2022, 07:00 UTC <p></p> Communicate: 11/Aug/2022, 11:00 UTC | (A block height bound to) UTC date and time when voters can start voting on proposals |
| Voting period end time | 25/Aug/2022, 11:00 UTC | |
| Start of tallying | 25/Aug/2022, 11:00 UTC | | 
| End of tallying | 02/Sep/2022, 11:00 UTC | UTC date and time by which the committee shall post the decrypted tally. |
| next_fund_start_time | 04/Aug/2022, 12:00 UTC | When registration phase for the next Fund starts | 
| fund_id | 9 | Fund_id as described in vote plan |
| Jormungandr Tallying optimization | 1 ADA = 1 voting token (i.e. the stake amount in lovelace is divided by 1000000) | How voting power is being proportionally reduced in order to optimize tallying performance |
| Proposal Funding logic (winner selection rule) | Proposals are ranked by the difference of Yes and No votes and funded one by one until challenge budget is exhausted | Proposals are ranked by sum of votes and funded in order. If the amount requested by a proposal is larger than the remaining challenge amount, it is skipped. | 
| Proposal acceptance threshold | 1% of total voting power <p></p> 15% more ‘Yes’ than ‘No’ | At least 1% of the total registered stake must vote on a proposal. <p></p> E.g., there is 1 billion ADA as a total registered stake. Then to be accepted (become an ‘approved proposal’ as well as be eligible for funding), a proposal must be voted by at least 0.01 * (1 * 10^9) = 10 millions of ADA. <p></p> 'Yes'-'No' difference of the stake voted on proposal must be at least 15% <p></p> (e.g., 90% 'Yes' and 10% 'No', or 57.5% 'Yes' and 42.5% 'No', or 100% 'Yes' and 0% 'No', etc.; it is assumed that abstained stake does not vote on the proposal in the current architecture).|
| 
