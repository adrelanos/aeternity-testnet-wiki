<a href="http://www.aeternity.com/"><img width="160px" src="http://www.aeternity.com/user/themes/aeon/img/aeternity_logo.png" align="left" hspace="10" vspace="10"></a>

<p align = right><a target="_blank" href="https://twitter.com/intent/tweet?original_referer=https%3A%2F%2Fabout.twitter.com%2Fresources%2Fbuttons&text=Aeternity:%20scalable%20smart%20contracts%20interfacing%20with%20real%20world%20data&tw_p=tweetbutton&url=http%3A%2F%2Fwww.aeternity.com%2F&via=aetrnty"><img src="http://s30.postimg.org/j2q6ql27h/Tweet.png"></a>
<a target="_blank" href="https://twitter.com/aetrnty"> <img src="https://s24.postimg.org/4xcf9j8xh/Follow-_Twitter.jpg?2"></a>
</p>
<b>æternity Blockchain – A Functional Oracle Machine<p>

æternity is a [blockchain](https://en.wikipedia.org/wiki/Blockchain) protocol built from scratch in [Erlang](https://en.wikipedia.org/wiki/Erlang_(programming_language)) with speed, efficiency and scalability in mind. It offers a unique hybrid [proof of work (PoW)](https://en.wikipedia.org/wiki/Proof-of-work_system) and [proof of stake (PoS)](https://en.wikipedia.org/wiki/Proof-of-stake) [consensus mechanism](https://www.ibm.com/developerworks/cloud/library/cl-blockchain-basics-intro-bluemix-trs/) that can be used to check [[oracles]], which maximizes their efficiency, as this prevents layering of consensus mechanisms on top of each other. [[State channels]] maximize scalability and privacy by removing the need to store smart-contract code on-chain. Transfer of [tokens](http://cruiserselite.co.in/downloads/btech/materials/second%20sem/4/e-com/UNIT-3.pdf) through channels is done by functional [smart contracts](https://en.wikipedia.org/wiki/Smart_contract) which have access to real-world data through the Oracle. æternity thus renders smart contracts faster, easier to execute, and more fault-tolerant, without degrading their performance or functionality.<p>

æternity's [white paper](Whitepaper_English) was published to introduce this architecture and its potential use cases. æternity is built to be used on a global scale in [prediction markets](https://en.wikipedia.org/wiki/Prediction_market), [synthetic assets’ markets](https://syntheticassets.wordpress.com/) and [a variety of other use cases](https://github.com/aeternity/wiki/wiki/Idea-Box#use-case-ideas-for-%C3%A6ternity).<p>

<b>How Can æternity Blockchain Serve Smart Contract Platforms?<p>

There are three main problems that underlie the presently available smart contract platforms. These include; the lack of sufficient scalability (global use throughput), coding safety and relatively inexpensive access to real-world data and chain governance:<p>

<ol>
<li>The presently prevalent stateful designs render smart contracts, coded for smart contract platforms like Ethereum, rather hard to analyze. Moreover, combining statefefulness with sequential ordering of transactions greatly reduces the scalability of the Blockchain.
<li>The difficulty of introducing real-world data to smart contract platforms, in a trustless, decentralized and reliable manner significantly hurdles the realization of a large number of advantageous smart-contracts applications.
<li>Most smart contract platforms have limited abilities to update themselves to cope with newly emerging economic and technological knowledge.</ol><p>

Recent studies of the state channel technology have proven that, in many instances, storing state on-chain is unnecessary. In most cases, all data can be stored in state channels, and the Blockchain would be only used to settle the economic results of exchange of information and/or to act as a fallout whenever a dispute occurs. This represents an alternative Blockchain architecture approach, which is marked by [Turing-complete](https://en.wikipedia.org/wiki/Turing_completeness) smart contracts that exist in state channels but not on the Blockchain. This would boost scalability as all transactions are independent and can be processed in parallel. Furthermore, this approach means that smart contracts will not write to [shared state](http://wiki.c2.com/?SharedStateConcurrency), which will greatly simplify contracts’ safety and the process of testing and verification.<p>

Decentralized prediction markets like [Augur](https://en.wikipedia.org/wiki/Augur_(software)) and Gnosis are attempting to integrate real-world data with the Blockchain in a decentralized manner via a process that implements a consensus mechanism on smart contracts, on top of the Blockchain. This will result in inefficiencies, and it wo=ill not boost security. So, it is logically better to generalize the consensus mechanism of the Blockchain so that it can provide information on the next [internal state](https://www.cs.nmsu.edu/~rth/cs/cs177/map/intstate.html) as well as on the external world’s state via its own mechanisms. That way we can ensure that the Blockchain’s consensus mechanism dictates the outcome of executing what [complexity theory](https://en.wikipedia.org/wiki/Computational_complexity_theory) describes as an “[oracle machine](https://en.wikipedia.org/wiki/Oracle_machine)”. An oracle machine is a theoretical machine that is far more powerful than a [Turing machine](https://en.wikipedia.org/wiki/Turing_machine) due to the fact that it can bear answers to questions whose answers cannot be computed such as “Who won the Super Bowl in 2016?”<p>

<b>Overview and Applications of æternity:<p>

æternity is a Blockchain protocol that is designed to solve all the aforementioned problems that are challenging smart contract platforms. æternity provides a highly efficient system for transferring value. Practically speaking, æternity represents a global oracle machine that can be utilized to provide decision making services in conjunction with smart-contracts on an enormous scale.<p>

The stateless nature of æternity’s smart-contracts makes it ideal for building a myriad of applications "æpps" that provide scalability and privacy through state channels, while keeping the security of Blockchain and the access to real-world data through Oracles. 
These "æpps" will benefit also from several on-chain features, including:<p>
* Identities: Each account will be associated with a [unique ID number](https://en.wikipedia.org/wiki/Universally_unique_identifier). Users will be allowed to register distinctive names and link them to a data structure’s [Merkle](https://en.wikipedia.org/wiki/Merkle_tree) root.
* On-chain Governance: æternity's on-chain prediction markets projects the information available to the network to one single number between 0 and 1. This number is used to signal to the miners which version of the Blockchain to mine on. This governance mechanism is also used to check the oracles for correctness. Further, certain blockchain variables (price of computation, blocksize, ...) will also be determined by this mechanism.

Some of these "æpps" applications include :<p>

* Wallet: the [wallet](https://en.wikipedia.org/wiki/Wallet_(software)) manages the crypto-currency, æon, [private keys](https://en.wikipedia.org/wiki/Public-key_cryptography), sends and signs transactions. It can also be used to create channel transactions and use apps within the channel network.
* Toll API: Payment channels open the door to a novel type of APIs where a user can pay for every API request. [Toll APIs](https://en.wikipedia.org/wiki/AEternity#Toll_API) mitigate [DDoS](https://en.wikipedia.org/wiki/Distributed_denial-of-service_attacks_on_root_nameservers) problems and simplify the creation of high quality APIs.
* Insured Crowdfunding: [Insured crowdfunding](https://en.m.wikipedia.org/wiki/Equity_crowdfunding#Crowdfunding_insurance) can be implemented via means of [dominant assurance contracts](https://en.wikipedia.org/wiki/Assurance_contract#Dominant_assurance_contracts), which are smart contracts that are created to raise money for a good cause.
* Decentralized Education Marketplace on æternity : æternity's powerful features can be used to disrupt education with Blockchain by creating an open marketplace where students and teachers alike, can trade private or group lessons. It should include social profiles of both teachers and students, gamification etc. Also, by Using æternity oracle, students can allow more than one teacher to rate a test, exam or work in general.
* Supply Chain Management: The supply chain management can be trusted to a smart-contract that is constantly interfacing with the Oracle on æternity. The demand for any product can be fed to the smart-contract through the Oracle. It will automatically trigger the contract to send procurement orders to suppliers, and raw materials providers, taking into consideration the normal delays of each item in the procurement process.
* Others: [Other possible applications](https://github.com/aeternity/wiki/wiki/Idea-Box#decentralized-education-marketplace-on-%C3%A6ternity) include cross-chain atomic swaps, event contracts (e.g. insurance, whistleblowing) and prediction markets. 

The Phase 1 "Friends, Family, and Real Innovators" contribution campaign ran for three days, beginning on April 3rd, 2017. In that time, contributors were able to purchase 1,100 AE for very ETH spent in the first 24 hours, and 1,000 AE per ETH thereafter. The first thousand who contributed 12 ETH or more were also entitled to a limited edition æternity branded Ledger Nano S hardware wallet. In this time period, 2466 contributers generated 139,099,689.485 AE through total contributions of 121,265.614 ETH and 323.5482 BTC. At current fiat to cryptocurrency conversion rates (as of 5/23/17), the USD value translates to $733,736.14 in BTC and $21,955,139.41 in ETH, totaling $22,688,875.55.

[Phase 2, the "Early Adopter" round](https://wallet.aeternity.com/), which begins on May 29th, will be open for three full weeks - or until contributions reach the cap of twenty one million Swiss Francs (CHF). This round will allow contributors to purchase 800 AE for each ETH contributed over the first 24 hours, 750 over the remainder of the first week, 700 AE per ETH over the second week, and 650 ETH over the third week. As in the first round, BTC will also be accepted.

Contributors will be able to use their AE after Phase 2 is complete (most probably in the form of an [ERC20](https://theethereum.wiki/w/index.php/ERC20_Token_Standard) token on the [Ethereum](https://en.wikipedia.org/wiki/Ethereum) network).

The contributor portion will comprise 82% of the initial æternity AE tokens. 17% of funds will be allocated to [Aeternity Anstalt](http://kundmachungen.li/AktuellsteNeugr%C3%BCndungen/Details?nr=FL00025283581&Firma=AETERNITY+ANSTALT&ort=Triesen&datum=11.11.2016), the foundation and the founding team, and the remaining 1% will be allocated to holders of BTC or ETH, accessible when the æternity blockchain launches. 

All will be recorded on the Ethereum Blockchain by a standard [multisig escrow contract](https://en.wikipedia.org/wiki/Multisignature). The AE tokens for the team will be [time-locked](https://www.ethereum.org/dao#time-locked-multisig).

https://blog.aeternity.com/security-transparency-simplicity-1411fad10974

## Learn More
The dedicated Wiki channel on Slack is [HERE](https://pacific-beach-20900.herokuapp.com/), feel free to join us!
_This will be rapidly expanded._

[Whitepaper_English]: Whitepaper_English
[Whitepaper_Korean ]: Whitepaper_Korean
[Whitepaper_Indonesia]: Whitepaper_Indonesia
[Whitepaper_French]: Whitepaper_French
[Whitepaper_Chinese]: Whitepaper_Chinese
[Whitepaper_Russian]: Whitepaper_Russian
[Whitepaper_Español]: Whitepaper_Español
[Whitepaper_Japanese]: Whitepaper_Japanese