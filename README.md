# Vyper - Optimism Subsidized Audit Grant 2024

## Grant Request

**OP request Locked:** 0

**OP request for User Incentives:** 250,000

**L2 Recipient Address:** `oeth:0x10E13a2bbD74b31A35d419f374e49c891748352B`

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

2. Vyper is already the second most widely used programming language on EVM chains. Our latest release (0.4.0) introduced composability via its module system and a new highly optimized backend (Venom). We worked to drastically increase security with full reviews of the codebase, regular audits, security competition and by working on compiler verification. These features allow Vyper to produce contracts that have smaller bytecode size, lower gas costs and are significantly cheaper to audit compared to other smart-contract programming languages. Vyper's pythonic syntax also make it easy to onboard new developers to web3, as Python is now the most popular programming language (Stack Overflow survey 2024, https://survey.stackoverflow.co/2024/). A recent Twitter poll with 164 participants showed that a majority of developers would pick Vyper and Ape over Solidity and Foundry to start a new project (https://x.com/0xKoga/status/1805524364948893756).

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
2. Vyper is currently the second most popular smart contract language on the EVM (https://defillama.com/languages). The Vyper github repository has over 4,500 stars. There are over 30k Vyper contracts deployed across a dozen chains, securing over $2 billion of value. DeFi projects that use Vyper include Curve, Yearn, Lido, Velodrome, Perpetual Protocol and Adapter.Fi.

### Grant's impact

**Please briefly answer all grant's impact questions**

```
1. Steps to increase user interaction
2. Target audience characteristics
3. User interaction with Optimism
4. Competitors on Optimism:
```

1. We plan to advertise the possibility of getting grant-funded audits to new projects and established projects who are working on Vyper contracts. Projects should be deploying their contracts on the Optimism Superchain and the Vyper team will vet the quality of applicants as well as the potential positive impact of their product on Optimism.
2. Our target audience is developers launching new products on the Superchain as well as existing projects who are switching to Vyper. We expect the former to be developers with a good knowledge of Python but perhaps a more limited experience of web3 building. The latter are existing projects who are rewriting and rewriting existing contracts in Vyper or deploying new Vyper contracts. We will require both our target audiences to be strongly aligned with Optimism and Ethereum.
3. Deploying on Optimism is a pre-requisite for receiving audit funding within the scope of this grant. When assessing projects, we will take into consideration their potential future impact on Optimism (in terms of # contract interactions, TVL, team members).
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

1. We request 250,000 OP or $435,000 USD at current prices. The cost of a high-quality audit will vary depending on the size and complexity of the codebase, but we will enforce a hard upper limit of $100k per project. We plan to fund between 10 and 80% of the applicants' auditing costs based on our analysis of their need. We will not cover 100% of the costs to make sure that applicants maintain skin in the game. We therefore plan to have funding range from $10k to $100k USD per project, with a target of funding 10 Vyper projects overall.
2. We first plan to reach out to our network of high-quality, Vyper-proficient auditors to gather a pool of auditors (1 month). We will then advertise the opportunity of subsidized audits through our network of developers, social media accounts and Vyper events (2 to 3 months). Interested parties will be asked to fill out a form with a link to their codebase, an overview of their project and team, as well as questions about their alignment with and plans for growth on the Superchain. Applications will be screened by the Vyper team (1 month). For successful applicants, we will ask our partner auditors for quotes (1 month) and subsidize audit costs up to $100k per project. 
3. We estimate that each project will get funded within a range of 10 to 20% of the total amount of tokens received. The amount of the subsidy that each project receives will depend both on the amount quoted by our partner auditors for their codebase and on the perceived quality and impact of the project for Optimism. We will not subsidize the entire cost of an audit even if it is below the $100k threshold.
4. We expect to have completed the selection of applicant and calculated the amounts of subsidies to be distributed 6 months after the start of the project. Distribution will start immediately thereafter.
5. The subsidies are meant to help projects deploy on Optimism by subsidizing and potentially speeding up the auditing process. We will select projects based on their impact and long-term alignment with Optimism to ensure that they continue to deploy, grow and bring new users to the Superchain long after their initial deployment.
6. The Vyper optimism multisig for this project is  `oeth:0x10E13a2bbD74b31A35d419f374e49c891748352B`. The multisig will only be used to claim and distribute tokens from this grant. If the OP is not in contracts or this wallet, it has been spent.

### Optimism relationship

**Please briefly answer all Optimism relationship questions**

```
1. Problem solved for Optimism
2. Value proposition
3. Growth potential for Optimism
4. Commitment to building on Optimism
5. Deployment status (exclusively on Optimism, on Optimism and other networks, not yet deployed, etc.):
```

1. Within the scope of the current grant, we help grow the number of active developers and high-quality projects on Optimism by reducing barriers to entry through subsidized audits for Vyper-based projects.
2. We provide value to Optimism by attracting new developers, new protocols and their communities to Optimism. By facilitating audits with high quality auditors, we also improve the overall security of the Optimism ecosystem 
3. Growth potential for Optimism is significant as Python is the currently the most popular programming language among developers and Vyper offers a quick and simple way to onboard them to web3. The Vyper community is very tight-knit and offers excellent support to new developers. By offering audit incentives, we also encourage new projects to deploy on Optimism and bring their community to the Superchain. The improved security from audited contracts will also increase user trust and adoption. 
4. Vyper is a long-time supporter of the Optimism ecosystem, going back to the days of the OVM (which Vyper supported). We have also benefitted from Optimism's grant programs and are committed to help onboard new Vyper users to the Superchain. We will make subsidies conditional on Optimism deployment and alignment. 
5. Vyper is a programming language not a deployed protocol, although several Vyper contracts are already deployed on Optimism. This grant will however specifically target projects deploying exclusively or primarily on Optimism. We will also favor new and upcoming projects over established ones.

### External Contributions:

**Use of Grant-as-a-service provider:** No

**Contributions from non-team members:** No

### Milestones
- Select pool of auditors. The Vyper team will reach out to high-quality auditors with experience in Vyper and request their participation in the project. (1 month)
- Formalize application process and advertise project. We will create a detailed application form for projects seeking audit subsidies. This form will include questions about the project's goals, team background, codebase, and plans for Optimism deployment. We'll advertise this opportunity through Vyper's social media channels, developer forums, and at relevant blockchain events. (2~3 months)
- Select applicants. We'll evaluate applications based on 1. potential impact on the Optimism ecosystem and alignment with Optimism's values and goals, 2. technical merit and innovation, 3. team's capability and commitment to long-term development, 4. audit-readiness (documentation, test suite, completion). (1 month)
- Determine token distribution for successful applicants. Once projects are selected, we'll work with them and our auditor pool to determine audit scope and costs. We'll then decide on the appropriate amount of OP tokens to distribute to each as subsidies. (1 month)
