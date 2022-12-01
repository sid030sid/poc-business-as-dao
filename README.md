# Proof of concept for running a business as a DAO

## About
This project aims at creating a generic DAO contract unlocking all advantages of running a business as a DAO. To determine these perks, this project also has the goal to scientificially research pros and cons of businesses being DAOs.

## Tech stack
The generic DAO contract is coded in [Soldidity v0.8.17](https://docs.soliditylang.org/en/v0.8.17/) and is tested by the hardhat framewor which uses [Mocha](https://mochajs.org/), [Chai](https://www.chaijs.com/), and [Ethers.js](https://docs.ethers.io/v5/).

## Installation
1. clone repo
2. run ```npm install``` to install all needed libraries
3. run ```npx hardhat run scripts/deploy.js``` to deploy contracts to local environment
4. run ```REPORT_GAS=true npx hardhat test``` to test contracts with a report on gas

## Research: pros and cons of businesses being DAOs
### Abstract
TBA

### Introduction
TBA

### Research procedure / roadmap
1. define (DAO, business [ Which businesses does this research consider])
2. what are the consequences of being a DAO for the considered businesses
    - effect on organisation (t cannot be a Kaufmann anymore, for which types of businessesisit possible to be a DAO?)
    - effect on productivity
3. what novel features does a business get if it is a DAO?
4. for which businesses does it make sense to be a DAO?

### Definitions
- DAO: what is a DAO? 
    - ["most important aspect of DAOs is that they are collectively owned and managed by their members"](https://moralis.io/dao-smart-contract-example-dao-guide/)
    - "decisions are easily governed by proposals and voting"
- business:
    - Which businesses are able to be a DAO?
        1. DAO compatable businesses: public companies (--> EquityToken), associations/communities, NGOs, ...
        2. DAO uncompatable businesses: GmbH (since not all people sh),
    - Which businesses does this research consider: public company, family business, middle sized company, associations ... etc.)?


### Main part
- How do DAO contracts look like as of now? 
    - https://moralis.io/dao-smart-contract-example-dao-guide/

- What does this research's generic DAO contract do differently (e. g. locking of employee's salary)?
- Perks of DAOs in general?
    1. ["By automating the implementation of rules, a lot of tension and the need to trust anyone else can be eliminated."](https://moralis.io/dao-smart-contract-example-dao-guide/)

### Conclusion
TBA