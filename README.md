# Vyper - Optimism Subsidized Audit Grant 2024

## Grant Request

**OP request Locked:** 0

**OP request for User Incentives:** 250,000

**L2 Recipient Address:** `0x7e2775779a97F54168AB70B26cA4a8179966c6A4`

**Please briefly explain how we will be able to confirm that the OP has been spent:** If the OP is not in contracts or aforementioned wallet, it has been spent.

### Project Details

**Please briefly answer all project details questions**
```
1. Brief description of the project and what it aims to achieve: 
2. Success potential: 
  a. (Explain why your project is likely to succeed. Consider market demand, technical feasibility, and your team's ability to execute) 
3. Mission alignment: 
  a. (Describe how your project aligns with the goals of the mission request you are applying for.) 
4. Novelty: 
  a. (Highlight what makes your project unique or innovative.)  
5. Will the project be open source? 
6. Free or fee-based for end users? 
7. Is it composable with other projects on Optimism? How?
```

1. Vyper is a pythonic programming language for smart contracts on the Ethereum Virtual Machine (EVM). We aim to become a leading choice for smart contract development by offering superior developer experience, high quality tooling, maximum readability and security.

2. Vyper is already the second most widely used programming language on EVM chains. Our latest release (0.4.0) introduced composability via its module system and a new highly optimized backend (Venom). We worked to drastically increase security with full reviews of the codebase, regular audits, security competition and by working on compiler verification. These features allow Vyper to produce contracts that have smaller bytecode size, lower gas costs and are significantly cheaper to audit compared to other smart-contract programming languages. Vyper's pythonic syntax also make it easy to onboard new developers to web3, as Python is now the most popular programming language (Stack Overflow survey, 2024). A recent Twitter poll with 164 participants showed that a majority of developers would pick Vyper and Ape over Solidity and Foundry to start a new project.

3.  We plan to use this grant to fund audits for new projects written in Vyper. Vyper regularly works with top auditors and security researchers to ensure the security of its codebase. We will use these connections to gather a pool of qualified auditors that we can connect with projects that build on Optimism and use Vyper as their smart contract language. In doing so we will help the Collective grow the number of active developers across the Superchain while driving adoption of Vyper. Projects will be screened based on the quality of their product and their positive impact on the Optimism Superchain. 

4. Vyper stands out by being the only smart contract programming language prioritizing readability and security. Its backend (Venom) offers unmatched performance. We also innovate to improve developer experience, for instance by offering support for popular collaborative tools like Jupyter notebooks and Google Colab, allowing multiple developers to quickly and interactively iterate over their smart contract code.
5. Vyper is released under a permissive open source license (Apache)
6. Vyper is free for all users
7. Vyper can be used to interact with any other contract on Optimism, regardless of their programming language.


### Market Analysis:

**Please briefly answer all market analysis questions**
```
1. Competitors and differentiation
2. Current user base and estimation method
```

1. Vyper's main competitors are other smart contract programming language such as Solidity, Fe and Yul. Vyper differs by its focus on readability, security and simplicity. Vyper is designed to make contract maximally human readable. This translates in a direct reduction (-20% according to auditors) of the time and costs of auditing Vyper contracts. Simplicity translates to more optimized contracts, which have, on average 50% smaller bytecode and less gas costs. Vyper's simple, pythonic syntax and the absence of footguns (operator and function overloading, class inheritance, etc.) makes it easy to onboard new developers already familiar with Python.
2. Vyper is currently the second most popular smart contract language on the EVM (https://defillama.com/languages). The Vyper github repository has over 4,500 stars. There are over 5000 Vyper contracts deployed across a dozen chains, securing over $2 billion of value. DeFi projects that use Vyper include Curve, Yearn, Lido, Velodrome, Perpetual Protocol, Adapter.Fi.

### Grant's impact

**Please briefly answer all grant's impact questions**

```
1. Steps to increase user interaction
2. Target audience characteristics
3. User interaction with Optimism
4. Competitors on Optimism:
```

1. We plan to advertise the possibility of getting grant-funded audits to new projects and established project who are planning to expand their protocol with Vyper contracts. Projects should be deploying their contracts on the Optimism Superchain and the Vyper team will vet the quality of applicants and the potential positive impact of their product on Optimism.
2. Our target audience is developers launching new products on the Superchain as well as existing projects who are switching to Vyper. We expect the former to be developers with a good knowledge of Python but perhaps a more limited experience of web3 building. The latter are existing projects who are rewriting and redeploying existing contracts to Vyper or deploying new contracts written in Vyper. We will require both our target audiences to be strongly aligned with Optimism and Ethereum.
3. Deploying on Optimism is a pre-requesite for receiving audit funding within the scope of this grant. When assessing projects, we will take into consideration their potential impact on Optimism (in terms of # contract interactions, TVL, team members).
4. Our main competitor on Optimism is Solidity. Other languages are hardly represented.

### Metrics improved by OP incentives

**Select the metric specified in the mission request:** # of active addresses interacting with grantee’s contracts

**Fill out your metric objective:** TVL in deployed contract, # of teams, # of devs on teams

### Budget and Plan
    
**Please briefly answer all budget and plan questions:**

```
1. Size of request and justification
2. Plan for accomplishing the project (roadmap)
3. OP tokens distribution (percentages and initiatives)
4. Token distribution timeline
5. Sustainability post-incentives
6. Additional accountability info (smart contract addresses, wallet addresses, etc.):
```

1. We request 250,000 OP or $435,000 USD at current prices. The cost of a high-quality audit will vary depending on the size and complexity of the codebase, but we will enforce a hard upper limit of $150k per project. This gives us a range of $50k to $150k USD per project, which would let us fund audits for 3 to 8 new Vyper projects - assuming mid-term price stability.
2. We first plan to reach out to our network of high-quality, Vyper-proficient auditors to gather a pool of auditors (~1 month). We will then advertise the opportunity of subsidized audits through our network of developers, social media accounts and Vyper events (continuous until grant funds at depleted). Interested parties will be asked to fill out a form with a link to their codebase, an overview of their project and team, as well as questions about their alignment with and plans for growth on the Superchain. Applications will be screened by the Vyper team. For successful applicants, we will ask our partner audits for a quote and subsidize audit costs up to $150k per project. Applications will remain open until funds are depleted. We currently already know of a few new Vyper projects looking for audits and estimate the funds may be depleted within a year. 
3. We estimate that each project will get funded within a range of 12 to 35% of the total amount of tokens received. The amount of the subsidy that each project receives will depend both on the amount quoted by our partner auditors for their codebase and on the perceived quality and impact of the project for Optimism. We may not subsidize the entire cost of an audit even if it is below the $150k threshold.
4. The distribution timeline will be dependent upon the flow of applications. However, once an application is successful we will arrange to transfer the tokens covering the subsidy directly to the auditor - either as OP tokens or after swapping to a stablecoin (depending on the policy of each auditor). We estimate that all tokens will be distributed within a year after reception by the Vyper team.
5. The subsidies are meant to help projects deploy on Optimism by subsidizing and potentially speeding up the auditing process. We will select projects based on their impact and long-term alignment with Optimism to ensure that they continue to deploy, grow and bring new users to the Superchain long after their initial deployment.
6. The optimism Vyper multisig is 
