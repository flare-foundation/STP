# STP - Songbird Test Proposal 0

stp: | 0  
--- | ---
title: | STP Purpose and Guidelines
status: | Final
type: | Meta
created: | 21-Nov-2021

## Background
Songbird is the Canary Network for Flare. Prior to the launch of the Flare Network (Flare), the protocols that make up Flare at inception are intended to be tested with Songbird. After the launch of Flare, it is envisioned that Songbird will remain the long-term testing ground for upgrades to Flare. Changes to Flare will happen via a Flare Improvement Proposal (FIP) process. This may result in Songbird Testing Proposals (STP’s) should such changes to Flare require testing on Songbird.
## Songbird governance systems
Songbird has two governance systems:
### Songbird Testing Proposal (STP).
This proposal system is the mechanism by which the initial protocols on Flare and, then, later ongoing upgrades to Flare are tested. This is detailed below. 
### Songbird Improvement Proposal (SIP).
The SIP governance module will become active after the launch of Flare. The proposal process will be elaborated prior to that event and will generally define how a change is made to Songbird. A SIP that breaks compatibility with Flare’s core protocols, so as to make future testing of Flare Improvement Proposals (FIP) impossible on Songbird, will be automatically rejected unless and until there is a SIP that specifically brings to an end the status of Songbird as Flare’s Canary Network. Naturally, whilst Songbird remains Flare’s Canary Network, this reduces the set of potential changes that can be made to Songbird.
### STP purpose

The purpose of the STP structure is to allow governance to be exercised by Songbird token holders over changes that are extremely unpopular whilst, at the same time, not limiting the utility of Songbird for testing. In order to achieve this STP’s will be implemented automatically unless they are rejected with a high threshold. 

### Pre flare launch
Prior to the launch of Flare the simplified Songbird governance process will be as follows: 

1) An STP will be uploaded by the foundation to [this](https://github.com/flare-foundation/STPs) repo. 

2) Voters may delegate their votes at any time up to the deadline. The vote power for calculation will be determined at a random chosen block per proposal.

3) The proposal automatically passes and is implemented if < 75% of Songbird Token Free Float opposes the proposal. The free flow amount can be obtained from the [supply](https://songbird-explorer.flare.network/address/0x5059bA6272Fa598efAaCC9b6FCeFef7366980aD7/read-contract) contract. In that contract read the value at API function 3 `getCirculatingSupplyAt` where one should set which block number to be queried.

### Post flare launch
Post the launch of Flare the procedure will be identical from the vantage point of Songbird except that step 1, above, will be precipitated by the FIP process. 
### Free float definition 
All of the SGB that is NOT held by the Flare Foundation.

## Proposal Strucuture

A valid STP Proposal will be structured as follows:

a) A table detailing: #, title, status, type, author, date

b) Brief description.

c) Technical description.

d) Link to code repository.

e) Link to audit report if applicable.

f) Bug bounty information if applicable.

g) Proposed implementation date range.

h) Voting contract details.

i) Deadline for voting.
