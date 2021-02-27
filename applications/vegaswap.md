# Open Grant Proposal

* **Project Name:** Vegaswap.io
* **Team Name:** Vegaswap
* **Payment Address:** vegaswap.eth

*The above combination of your GitHub account submitting the application and payment address will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up: 

### Overview

Vegaswap is a novel AMM protocol which is built as a platform to enable a wider range of DeFi applications. 
Dynamic pricing allows the protocol to adapt to market conditions. 
The economics for market makers and takers are designed to allow for long term viability. 
Governance of the marketplace happens through the Vega governance token.
Cross-chain pools allow for creation and trading in pools on multiple chains.

In the first phase, the development are single pools which are deployed as a smart contract written in inc, deployed on kusama.
The second phase can enable Substrate and Parachains.

Automated Market-making has great potential, but currently has a few drawbacks. Impermanent loss leads to higher fees and slippage than necessary.
And the liquidity is only available on a single chain. Cross-chain pools can enable wider trading.

### Project Details 
We expect the teams to already have a solid idea about the project's expected final state.

Therefore, we ask the teams to submit (where relevant):
* Mockups/designs of any UI components
* API specifications of the core functionality
* An overview of the technology stack to be used
* Documentation of core components, protocols, architecture etc. to be deployed
* PoC/MVP or other relevant prior work or research on the topic

### Ecosystem Fit 

We have deep knowledge in DEX development and AMM, as we as experience with launches and trading on Uniswap and the disadvantages.

## Team :busts_in_silhouette:

### Team members
* Benjamin Cordes
* Jimmy
* Todd

### Contact
* **Contact Name:** Full name of the contact person (e.g. John Brown)
* **Contact Email:** Contact email (e.g. john@duo.com)
* Website

### Legal Structure 
* **Registered Address:** Address of your registered legal entity, if available. Please keep it on one line. (e.g. High Street 1, London LK1 234, UK)
* **Registered Legal Entity:** Name of your registered legal entity, if available. (e.g. Duo Ltd.)

### Team's experience
Blockchain and DEX development since 2013 . Helped bootstrap DEX on Bitcoin 2015-2017. Work on Ethereum, 0x
and many other projects. Work in a variety of languages in distributed systems and blockchain: python, rust, clojure.

### Team Code Repos
* https://github.com/benjyz
* https://github.com/rhacker

### Team LinkedIn Profiles
* https://www.linkedin.com/<person_1>
* https://www.linkedin.com/<person_2>

## Development Roadmap :nut_and_bolt: 

This section should break out the development roadmap into a number of milestones. Since the milestones will appear in the grant contract, it helps to describe the functionality we should expect, plus how we can check that such functionality exists in the product. Whenever milestones are delivered, we refer to the contract to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions it should be clear how the project is related to Substrate and/or Polkadot. We recommend that the scope of the work can fit within a 3 month period and that teams structure their roadmap as 1 month = 1 milestone. 

For each milestone:
* Please be sure to include a specification of your software. Treat it as a contract - the level of detail must be enough to later verify that the software meets the specification.
To assist you in defining it, we created a document with examples for some grant categories [here](../src/grant_guidelines_per_category.md).
* Please include total amount of funding requested per milestone.
* Please note that we require documentation (e.g. tutorials, API specifications, architecture details) in each milestone. This ensures that the code can be widely used by the community.
* Please provide a test suite, comprising unit and integration tests, along with a guide on how to run these.
* Please commit to providing a dockerfiles for the delivery of your project. 
* Please indicate the milestone duration, as well as number of Full-Time Employees working on each milestone, and include the number of days along with their cost per day.
* Deliverables 0a-0d are mandatory and should not be removed, unless you explicitly specify a reason within the PR's `Additional Notes` section (e.g. Milestone X is research oriented and as such there is no code to test)

### Overview
* **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
* **Full-time equivalent (FTE):**  Workload of an employed person ([see](https://en.wikipedia.org/wiki/Full-time_equivalent)) (e.g. 2 FTE)
* **Total Costs:** Amount of Payment in USD for the whole project. The total amount of funding needs to be below $30k for initial grants and $100k for follow-up grants at the time of submission. (e.g. 1.000 USD)

### Milestone 1 Example — Implement Substrate Modules 
* **Estimated Duration:** 1 month
* **FTE:**  1
* **Costs:** 1.000 USD

| Number | Deliverable | Specification |
| ------------- | ------------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | The code will have unit-test coverage (min. 70%) to ensure functionality and robustness. In the guide we will describe how to run these tests | 
| 0d. | Article/Tutorial | We will write an article or tutorial that explains the work done as part of the grant. 
| 1. | Substrate module: X | We will create a Substrate module that will... (Please list the functionality that will be coded for the first milestone) |  
| 2. | Substrate module: Y | We will create a Substrate module that will... |  
| 3. | Substrate module: Z | We will create a Substrate module that will... |  
| 4. | Substrate chain | Modules X, Y & Z of our custom chain will interact in such a way... (Please describe the deliverable here as detailed as possible) |  
| 5. | Docker | We will provide a dockerfile to demonstrate the full functionality of our chain |

### Milestone 2 Example — Additional features
...

## Future Plans
Please include the team's long-term plans and intentions.

## Additional Information :heavy_plus_sign: 
Any additional information that you think is relevant to this application that hasn't already been included.

Possible additional information to include:
* What work has been done so far?

Launchswap contract development over the last 3 months. A dynamic market-maker on ethereum.
https://github.com/rapidtrade-io/vegaswap/

* Are there are any teams who have already contributed (financially) to the project?

Seed funding of 20,000$ to a related project which enabled this work.
https://etherscan.io/address/0x7bc438f01eb804f40f073599d71339a95a1ad7c9

* Have you applied for other grants so far?

No
