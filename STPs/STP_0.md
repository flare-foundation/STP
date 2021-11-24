# STP - Songbird Test Proposal 0

| stp | title                       | status   | type | author | created |
| --- | ---                         | ---      | ---  | ---    | --- |
| 0   |  STP Purpose and Guidelines | Proposal | Meta | ?      | 2021-11-21 |

## Background
Songbird is the Canary Network for Flare. Prior to the launch of the Flare Network (Flare) the protocols that make up Flare at inception are intended to be tested with Songbird. Post the launch of Flare it is envisioned that Songbird will remain the long term testing ground for upgrades to the Flare Network. Changes to Flare will happen via a Flare Improvement Proposal (FIP) process which will result in Songbird Testing Proposals (STP’s) where those changes to Flare require testing on Songbird.

## Songbird governance systems
Songbird has two governance systems:
### Songbird Testing Proposal (STP).
This proposal system is the mechanism by which the initial protocols on Flare and then later ongoing upgrades to Flare are tested. This is detailed below. 
### Songbird Improvement Proposal (SIP).
This proposal process will be elaborated elsewhere but generally defines how a change is made to Songbird. A SIP that breaks compatibility with Flare’s core protocols so as to make future testing of Flare Improvement Proposals (FIP) impossible on Songbird will be automatically rejected unless and until there is a SIP that specifically brings to an end the status of Songbird as Flare’s Canary Network. Naturally whilst Songbird remains Flare’s Canary Network this reduces the set of potential changes that can be made to Songbird.

### STP purpose

The purpose of the STP structure is to allow governance to be exercised by Songbird token holders over changes that are extremely unpopular whilst at the same time not limiting the utility of Songbird for testing. In order to achieve this STP’s will be implemented automatically unless they are rejected with a high threshold. 

### Pre flare launch
Prior to the launch of Flare the simplified Songbird governance process will be as follows: 

1) An STP will be uploaded by the foundation to [this](https://github.com/flare-foundation/STPs) repo. 

2) Voters may delegate their votes at any time up to the deadline. The vote power for calculation will be determined at the expiry of the vote period.

3) The proposal automatically passes and is implemented if < x% of Songbird Token Free Float opposes the proposal.

### Post flare launch
Post the launch of Flare the procedure will be identical from the vantage point of Songbird but step 1 above will be precipitated by the Flare Improvement Proposal process. 

### Free float definition 

All of the SGB that is not held by the Flare Foundation.

## Proposal Strucuture

A valid Proposal, both for STP and SIP will be structured as follows: 

a) A table detailing: #, title, status, type, author, date

c) Brief description. 

c) Technical description. 

d) Link to code repository. 

e) Link to audit report if applicable. 

f) Bug bounty information. 

g) Proposed implementation date range.

h) Voting contract details.

i) Deadline for voting.

### Songbird Testing Proposal Cycles

At Flare launch Songbird and Flare will have virtually identical codebases. Whilst Songbird remains Flare’s Canary Network when Flare Improvement Proposals pass through to implementation stage a Songbird Testing Proposal will then be put forward by the Flare Foundation. If the proposal is not rejected it will be implemented on Songbird. If that proposal is subsequently implemented on Flare the codebases will again converge in all relevant areas. If the proposal is not implemented on Flare the change to Songbird will be rolled back to maintain compatibility.
