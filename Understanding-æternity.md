# What is æternity?

æternity is a new blockchain-based [smart contract](https://blockgeeks.com/guides/smart-contracts/) platform that synthesizes, streamlines, and expands upon the Bitcoin blockchain, Ethereum smart contracts, and Augur prediction markets. Instead of coding and storing complete contracts on-chain, æternity enables real-world data to interface with smart contracts through the use of a decentralized oracle mechanism. æternity allows true scalability by facilitating an exponential increase in throughputs, which, in turn, will invite mainstream adoption. Trustless, Turing-complete state channels also set æternity apart from Ethereum, the prevailing smart contract platform.

æternity is unique in many ways, but the major innovations are:

- Hybrid PoW/PoS (proof of work/ proof of stake) power grid
- Oracle Machine real-world interface
- State Channels, or "Off-chain transactions" and "Off-chain contracts" execution that will allow for faster transaction time, improving anonymity when executing contracts and while transacting
- Governance via a prediction-based consensus mechanism
- Expanded Merkel-tree navigation and address naming system


# What is the purpose of æternity?

æternity seeks to develop a highly scalable blockchain architecture with a consensus mechanism that is used to support the oracle machine. In other words, the goal is to create a blockchain that is as efficient and cost-effective as possible. With the oracle machine, we can avoid the unnecessary layering of one consensus mechanism on top of another (e.g. Augur and Gnosis on top of Ethereum). With state channels, privacy and scalability will be improved. Tokens in these state channels can be transferred using function-based smart contracts that have access to network-wide oracle answers. By not storing the contract code or state on the blockchain, smart contracts are easier to analyze and faster to process, with no substantial loss in practical usage and fact-based (de facto functionality). Contracts are safer and will not bloat the blockchain.


# What is a blockchain?

A blockchain is a secured ledger distributed among participants' computers and, in this case, governed only by the æternity software. More generally, a blockchain is a distributed database that contains a constantly growing chronological list of unalterable transaction records called "blocks". Each block in the chain consists of bundled transaction data that is cryptographically hashed. In order to prevent tampering of the recorded data in the chain, each block is time-stamped and linked to the previous block in the chain. Typically each node or computer connected to the blockchain network is charged with creating and validating new blocks using various consensus algorithms. Once new blocks are validated, they are appended to the chain. In this way, blockchains serve as the complete record of all transactions on the network from the genesis block to the most recently completed block.


# What is special about æternity and how does it compare to other blockchains?

æternity is built for scalable smart contracts that can interface with real-world data through oracles. 
Other smart contract platforms have experimented with 3rd party oracle machines added on top of the consensus, but this is inefficient and unnecessary. 

In contrast, æternity's oracle is fully integrated into the consensus mechanism and delivers deterministic values (from legacy systems, real-world data, or other blockchains) with which smart contracts may interact.
The oracle system lets data outside the blockchain be instantly implemented in æternity smart contracts, enabling countless business use cases.

![æternity-tech stack](https://github.com/aeternity/wiki/blob/master/images/ae-tech-stack.png)

# What is an oracle?

An oracle is a mechanism to provide the blockchain truths about our world or any element external to the blockchain itself. This is a virtual machine that crowd-sources real-time answers to specific questions using principles of [Prediction Markets](Research-and-Theory#prediction-markets). It can also be used to negotiate fundamental changes on how the system functions, allowing for high adaptability to market demands and other developments. Good examples include weather conditions, currency valuation, competition results, betting results, and any other information accessible to the public.

For more info: [Research and Theory](Research-and-Theory#decentralized-oracles)


# What are state channels?

State channels enable off-chain (or off-network) verification of transactions, data, and smart-contracts. If the verification in the channel fails, the blockchain acts as a judge between parties. This mechanism permits high transnational throughput and parallel processing of smart contracts by allowing their independence from the network. Hence, æternity's strengths lie in the programmability of complex relationships for large numbers of users and in the parallel handling of high volumes of products and information.

State channels allow for increased privacy because only the parties participating in a smart contract know about the contents of that smart contract. When a channel is settled on-chain, the only information put onto the blockchain is the transnational value that was exchanged. No contracting state is stored on-chain, so all channels are independent of each other. æternity's scalable smart contract systems improve upon the centralized scaling solutions that are available today. Transaction speed is limited only by bandwidth.

For more info: [State Channel](http://www.jeffcoleman.ca/state-channels/) and [[State Channels]].


# How does æternity work?

In current blockchains (Bitcoin, Ethereum, etc.), a hard fork is required whenever a system upgrade needs to be done. This leads to heated discussions among all value holders. Even simple changes like correcting arbitrary set variables in the source code (painfully obvious in the block size debate in Bitcoin) or the “DAO” issue in Ethereum seem to be very hard to agree on in a system where not all the users’ incentives are aligned with those of the decision makers. This can cause deep schisms in the community and endanger the value and reliability of the blockchain.

The problem here is that the decision making process for a protocol upgrade or change is not well defined and lacks transparency. More importantly, it still uses legacy mediums like forums and discussion websites, even requiring physical meetups to reach a consensus. It is neither decentralized and nor done on the blockchain. æternity aims to improve this process and thus gain an important competitive advantage.

In fact, æternity’s governance system is part of the consensus. It will use prediction markets to function as efficiently and transparently as possible. This consensus mechanism is defined by a number of variables that determine how the system functions. Those variables can be updated by each new block, from how much it costs to make transactions or ask an oracle, to modifications of fundamental parameters like the block time, block size, and the number of new tokens created per block (inflation). Since the oracle is incorporated in the blockchain consensus mechanism, using its services will be very cheap and will rely on the resilient architecture of the æternity blockchain instead of legacy systems which can be compromised[35].

By having prediction markets determine the value of variables that define the protocol, users can learn how to efficiently improve the protocol. Furthermore, predictions markets can facilitate potential hard fork decisions and help the community reach consensus about which version of the code to use. Each user chooses for himself which variable he seeks to optimize in order to maximize the value of his holdings.

Prediction markets could be the solution to public blockchain governance and allow for a novel way of organizing society and global economic interactions.

For more info: [Governance & æternity](Research-and-Theory#governance--consensus)


# What are æternity token and how are they used and consumed?

The æternity token (aeon/AE) is used to 
- pay fees for holding and æternity account, asking the oracle questions, opening a state channel
- pay for resources consumed through the platform 
- "gas" to power applications built on top of it

An ERC 20 token on Ethereum, representing the AE token, will be distributed after a security audit on the ERC20 contract. Once the main net launches all ERC20 tokens will be exchanged for AE tokens on the æternity Blockchain.


# What are some examples of how æternity can be used?

Toll API: Payment channels allow for a new kind of API where one
pays for every call to the API, possibly every HTTP-request.
Paying to access an API solves DDoS problems, and it makes
it easier to build high-quality APIs that are always available.

Stable value assets: Smart contracts and oracles can be used in combination to program synthetic assets that stay
nearly the same price as a real world asset.

Event contracts: Event contracts pay when an event
happens and don’t pay when an event does not happen according to
the oracle. Event contracts can be used as the basis for many other types of useful applications such as encouraging whistle-blowing and supporting prediction markets.

Micro-payments: æternity's state channels will allow for off-chain, peer-to-peer payments that will open up many revenue generation possibilities for content creators and publishers. While micro-payments are currently possible on other blockchains, transfer/minute and block size limitations prevent many current blockchains from handling micro-payments at scale.  

P2P Bandwidth Sales: State channel supported payments could allow for compensation-based sharing of WiFi hotspots. Think of it like an Uber-for-WiFi. Anyone could offer WiFi to anyone else via their mobile phone for a price. 

The potential applications are limited only by the imagination of the user base. 


# Purchasing and acquiring æternity

The first round to purchase AE tokens was during æternity's public 'Friends, Family and Real Innovators' round which took place on 3rd April 2017, 13:05 GMT and lasted for 72 hours until 6th April 13:05 GMT. This round was open to the public, meaning anyone could participate. At this time, you were able to buy 1000 AE tokens for 1 ETH. Investors in the first 24 hours received an extra 10% for a total of 1100 AE tokens for 1 ETH and the first 1000 contributors above 12 ETH will receive 1 'limited edition' æternity branded Ledger. 

The second round will begin May 29th, 2017. You can participate and follow any updates here: https://wallet.aeternity.com/


Check out the [Wikipedia](https://en.wikipedia.org/wiki/AEternity) page on æternity.