# Draft plan for Blockchain based research

*First draft*: __Thomas Suau__26/08/23__

Some of those questions are partially answered from developers point of view, but still no academic answer. If you are a professor interested by this topic feel free to [send me an email](mailto:thom.suau@orange.fr?subject=Research%20blockchain%20discussion) to discuss further about possible researchs. 
This plan and especially fundamental part should be regarded from fundamental understanding point of view. Not from some random tools which apparently solve the question. 

*Remark: Each of these questions need to be clarified. They are general and can't be answered as is. For each question a preliminary contextualization work is required.*

## Fundamental part

i) Command Line Interface (CLI) to deploy object (script or code) on-chain and interact with existing entities. 
- How to call a function deployed in a contract (EVM-like) in CLI?
- How to compile and send on the network a Smart Contract (solidity)?
- How to produce Bitcoin script in Raw messages?
- Questions around Nodes monitoring (geth, other clients? and bitcoind).

ii) Development section. Provide a top to date frameworks, libraries and tools in blockchain development.
- What are the last typescript development framework? Make a presentation of [`viem` ts package](https://yarnpkg.com/package?name=viem).
- What are the last advances in React blockchain integrations? *Think also about recursive inscriptions on Ordinals [🎟 imagine a ticket (onchain),🔏 securing art ownership (onchain),🌐 displayed on a website (onchain),©️ with a domain name (onchain)](https://twitter.com/lamachina777/status/1694116798315090252). We can call script deployed on Bitcoin through the Ordinal protocol.*
- Talk and discussions about [Foundry development toolkit](https://www.alchemy.com/dapps/foundry).
- A CLI discussion : possible to be about `hardhat` tool.

iii) Lecture and representation of on-chain data.
- Make use of CLI tools to extract on-chain data.
- State of the art?
- How GraphQL or other NoSQL language can be used to represent on-chain data? (geth GraphQL integration). *Small talk about [Arkham Blockchain Intelligence](https://www.arkhamintelligence.com/) : what tools? what discovers? what community (some famous people)?*
- Pb : retrieve deployed code from on-chain representations.
- How to unlock Bitcoin Taproot capabilities?

iv) Cryptography and architecture challenges.
I think the hardest and most technical part. The goal is to talk and produce research about cryptographic securities consideration and consensus mechanisms.
- What is mean secure?
- Post-quantum cryptography (Christophe Petit)
- What are the actual proof of soundness for major Blockchain protocols? (Bitcoin, Ethereum, EVM-like, Cardano, ...)
- What is the link between layer 1 and 2 assuming Layer 1 is sound under basic Diffie-Helmann assumptions (DH-assumptions)?
- Make a study about Lightning Network and Discret Log Problem equivalence (soundness). 
- Describe the use of Zero-Knowledge Proof protocols in Ethereum Layer 2 (like Starknet, or Zk-Polygon).
- Description of main consensus mechanisms. Are Directed Acyclics Graphs (DAGs) impact consensus mechanisms and how? 
- Consensus mechanisms regards to Proof of Stake.
- What are the consequences of consensus mechanism in Blockchain development?
- Cryptography and architecture: general overview. 


### Applied part

v) Technical application. The goal of this short section is to make the link between each previous part.
- From consensus to smart contract : How to make use of each parts?
- Which tools to use in all a blockchain development process?
- References and state of the art about blockchain development process? Research oriented? Business oriented?

vi) Economy. This part is to wonder economic principles in regards of Blockchain development.
1. Theory
- What is the actual money theory? (By referenced and different economists)
- What is the economy created by Bitcoin?
- What is the economy created by Proof of Stake consensus mechanism? 
- What is the link with numeric economy?
2. Practice
- What future for Euro and Fiat currencies?
- How to use blockchain technology to make monetary experimentation?
- How to build a tokenomic? Economic principles? Business principles? Technical principles?

vii) Law and fiscality. This section should presents state of the art about Law and Blockchain. This should also provide an analysis of waited evolution for the Right with blockchain technology. 
- Numeric laws. EU laws? How Blockchain is it actually considered in legal EU framework?
- What about digital identity in EU?
- How the money is able to evolve according to legal attended framework?
- What about legal tech blockchain based solution in EU countries?
- What about EU technical frameworks to apply legislation? Code provided? Reviews about [European Blockchain Service Infrastructure (EBSI)](https://ec.europa.eu/digital-building-blocks/wikis/display/EBSI/Home).
- What about European Fiscality in the future? Is it related to blockchain technology?
- How the blockchain technology can make evolve tax payment and reliability?
- Other questions...

viii) Health considerations. With the growing importance of pharmaceutical industry and health problems the blockchain technology could apparently be a good solution. 
- What are the main actual uses cases for blockchain based solutions?
- What use can we make of zk-proof in medical records management?
- CRISPR, gene management, genomics, 
- Protection for genetic centralisation data


ix) Computer's applications. AI, system administration, authentication, shared computation,... This section as the last one could join all the meetings in every computers based considerations related to the blockchain technologies. 
- Show where the blockchain is fundamentally ineficient. Show the major purposes of blockchain technology and its tools. Present first blockchain-based solutions to computers problems.
- What links can be do between AI and blockchain? How Blockchain technology and AI can be joined (used together)? Present actual state of the art in this field. Make some Pytorch and smart contract interaction in live.
- What about shared blockchain-based storage like IPFS and ARwave? What about shared computation through blockchain rewarding system? Calculus for astronomy, for biology, etc.

## Some references

This part is mainly notes for myself but it can be interesting to take a look about those.

### Publications target

- [Ethereum Stack Exchange](https://ethereum.stackexchange.com/)

- [bitcoin-dev Digest](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/)

- [Blockchain : Research and applications](https://www.sciencedirect.com/journal/blockchain-research-and-applications)

- [Frontiers](https://www.frontiersin.org/journals/blockchain)

- [Blockchain Journal](https://blockchainjournal.com/articles/) (less academic) 

- [Blockchain](https://www.elspub.com/journals/blockchain/home)

- [International Journal of Blockchain and cryptocurrencies](https://www.inderscience.com/jhome.php?jcode=ijbc)

- [blockchains](https://www.mdpi.com/journal/blockchains)(very young journal)

### Storage/Data sharing

- [Bitbucket](https://bitbucket.org/)

- [THETA.tv](https://www.theta.tv/) : Decentralised streaming platform

- [Odysee](https://odysee.com/) : Decentralised video platform

- [Nostr](https://www.nostrapps.com/) can be a storage system for small publications.


### Fundings

- Gitcoin

- [Geyser Bitcoin crowdfunding](https://geyser.fund)

- Cardano research fundings

- [Get a Grant | Optimism Docs](https://community.optimism.io/docs/governance/get-a-grant/)

- [Get Funding – NEAR Protocol](https://pages.near.org/ecosystem/get-funding/)


- [Case Study: Optimism](https://impact.gitcoin.co/optimism) : How Plasma Group was transformed through an Ethereum scalability research center into a Blockchain project to $2B+ in Impact.

### Blockchain based research

- [University of Nicosia](https://www.unic.ac.cy/blockchain/) : Leading Blockchain Education and Research Since 2013 : Master’s Degrees, Free MOOCs, Academic Certification Programs.

- [EMURGO](https://www.emurgo.io/) : EMURGO is a founding entity of the Cardano blockchain and provides products and services to drive the adoption of Cardano’s Web3 ecosystem.

- [Alrya](https://www.alyra.fr/) : L’école blockchain Votre formation au cœur de l'écosystème blockchain.

- [Université Catholique de Louvain (UCL) : Cryptography and Information System Security](https://uclouvain.be/en/research-institutes/icteam/cryptography-and-information-security.html) :Cryptography and Information Security seek at building tools that enable to secure data and to communicate in a reliable, fair, and private way. Over thirty researchers are active in this field.
Principal Investigators :
Axel Legay, Cristel Pelsser, Olivier Pereira, Thomas Peters, Etienne Rivière, Ramin Sadre, François-Xavier Standaert, Luc Vandendorpe
Research Labs :
Crypto Group, Cloud and Large Scale computing group, Image and Signal Processing Group (ISPGroup), Security and Performance of Networked Systems Group

- [EU Blockchain Observatory & Forum](https://www.eublockchainforum.eu/) :  a European Commission initiative to accelerate blockchain innovation and the development of the blockchain ecosystem within the EU and so help cement Europe’s position as a global leader in this transformative new technology.

- [Blockchain for Europe](https://www.blockchain4europe.eu/) : A Brussels based membership organization for companies driving innovation, integrity and empowerment through blockchain.
We work with policymakers, academics and our member companies to develop a European regulatory framework to support and promote blockchain-based innovation.

- [Brussels Blockchain Week](https://blockchainweek.be/) : The biggest blockchain event in Brussels each years. Focus on regulations. 




