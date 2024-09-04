<div style="text-align: center;">
  
![laina_v1](https://github.com/Laina-Protocol/.github/assets/84379059/a39f08c8-02c7-4468-844b-34f2dfb288b5)

</div>

https://laina-de.fi/lend

## About Laina
Laina is a low fee, trustless, and easy-to-use decentralized loan platform. We are focusing on making a simple and efficient DeFi product, where there is minimal need for token swapping or liquidity other than what is used for lending. Our vision is to change DeFi by making it accessible and understandable for everyone, regardless of their technical knowledge or financial status. By providing efficient single-token lending pools, we eliminate the complexities often associated with multi-token systems.

## Current status
Laina is currently in panel review for Stellar Community Fund (SCF) #29 activation award. After we have been granted the funding we will immediately start developing Laina according to the plan presented in the application and below.

## Development road-map
# Stage 1 - Initialization
In this initial stage we will develop Laina as proposed in the funding application. After the first stage we will have working smart contract running on the Stellar test network and we have collected feedback from the stellar community. We will found a company/foundation for the development of Laina.

### Deliverables:
#### ✨ MVP testnet contract
We will be developing a fully functional loan contract for a single token (testnet native) with a second test-token allowed as collateral. The contract will allow the basic functionalities e.g. lending, borrowing, liquidations, variable interest rates, and health-factor. The contract will be deployed only to the Stellar test network at this point.

**Tasks**
- [ ] Develop a factory contract that will be deployer for both loans and lending pools. This contract acts as an interface for initialization. (Estimated 100 hours of work)
- [ ] Develop the contract for lending pools. The contract will be built modular so it will be easy to use for any asset. (Estimated 90)
- [ ] Develop the contract that will be used for individual loans. This is deployed by the factory contract for every loan borrowed from the pools. (Estimated 70 hours of work)
- [ ] Study, test, and decide on which price oracles to use. (Estimated 40 hours of work)

Total estimated workload is 3 weeks and 300 working hours (two developers, 50h/week). Used hours: 0/300

#### 🔍 MVP contract tests
We will write detailed and thorough tests for the MVP contract specified in the first deliverable. Additionally, we will create a project page for Laina under the Stellar Developer Discord channel in the Community fund projects section. In this project page and general discussions in the Stellar Developers Discord channel we are aiming to gather feed-back from minimum 10 individuals. We’ll then create a written report of the feedback that we have gathered.

**Tasks**
- [ ] Create functional tests for each of the contracts
- [ ] Create fuzz tests for the whole system
- [ ] Create a detailed project page in the Stellar community fund channel
- [ ] Get a test group from the people of Stellar ecosystem, friends and family. Gather feedback from them and report it.

Total estimated workload is 1 weeks and 100 working hours. Used hours: 0/100

#### :fire: Simple and easy-to-use UI
A browser UI will be built for Laina. The web application will allow the user to view their Laina-contracts, as well as interact with all of their functionality: lending, borrowing & liquidations.

The application will be a full-stack Astro & TypeScript application, with bindings for Laina-contracts. Preliminary UI designs for the application are already drafted, and attached below.

**Tasks**
- [ ] Finalize the wireframe
- [ ] Develop the first version of the UI
- [ ] Connect Laina smart contracts with the UI and host it
- [ ] Adjust according to well-founded feedback

Total estimated workload is 2 weeks and 200 working hours. Used hours: 0/200
