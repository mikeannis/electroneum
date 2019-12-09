<p align="center">
  <img src="https://imgur.com/3FpIaYL.png">
</p>
<h4 align="center">Electroneum is a Fast, Secure, Mobile Based Cryptocurrency </h4>

## Table of Contents

 * [Introduction](#Introduction)
 * [About This Project](#About-This-Project)
   * [Co-Inventor of Blockchain About Electroneum](#Co-Inventor-of-Blockchain-About-Electroneum)
   * [Proof of Responsibility](#Proof-of-Responsibility)
   * [Moderated Blockchain](#Moderated-Blockchain)
   * [See How our Blockchain Functions (Video)](#See-How-our-Blockchain-Functions)
   * [Electroneum Mobile Wallet](#Electroneum-Mobile-Wallet)
   * [Hardware Wallet Support](#Hardware-Wallet-Support)
* [Learn More About Electroneum](#Learn-More-About-Electroneum)
   * [Benefits for Everyone](https://electroneum.com/benefits/)
   * [Electroneum.M1 Phone](https://electroneum.com/m1/)
   * [Mobile Application](https://electroneum.com/features/mobile-application/)
   * [Instant Payments](https://electroneum.com/features/instant-payments/)
   * [ETN Rewards](https://electroneum.com/features/mobile-mining-cloud-mining/)
   * [KYC & AML Complience](https://electroneum.com/features/kyc-aml-compliance/)
   * [Gig Economy: AnyTask](https://electroneum.com/features/gig-economy/)
 * [Development Resources](#Development-Resources)
   * [Building from Source](#Building-from-Source)
   * [Running an Electroneum Node](#Running-an-Electroneum-Node)
 * [Technical Documentation](#Technical-Documentation)
   * [Daemon RPC Documentation](docs/daemon-rpc-documentation.md)
   * [Wallet RPC Documentation](docs/wallet-rpc-documentation.md)
   * [Exchange Listing Guide](docs/exchange-listing-guide.md)
 * [Vulnerability Response Process](#Vulnerability-Response-Process)
 * [License](#License)
 * [Copyright](#Copyright)

## Introduction

Electroneum uses a cryptographically sound system to allow you to send and receive your tokens without your transactions being easily revealed on the blockchain. This ensures that all token transfers remain absolutely private by default, but if necessary, can be proven to a third party by providing specific keys.

**Security:** Using the power of a distributed peer-to-peer consensus network, every transaction on the network is cryptographically secured. Individual wallets have a 25 word mnemonic seed that is only displayed once, and can be written down to backup the wallet. Wallet files are encrypted with a passphrase to ensure they are useless if stolen.

Electroneum (and its group companies) have separately developed proprietary software which can be used in conjunction with this project. This software is subject to separate terms and conditions which are available at https://electroneum.com .

# About this Project

This is the core implementation of Electroneum. It is open source and completely free to use without restrictions, except for those specified in the license agreement below.

The V8 software upgrade (Electroneum v3.0.0.0 release) introduced some fairly radical changes to the Electroneum blockchain, those consisting on a new consensus algorithm we’ve coined as **Proof of Responsibility** and change from a full permission-less blockchain to a **Moderated Blockchain**.

A **Moderated Blockchain**, powered by the **Proof of Responsibility** consensus algorithm, allow Electroneum Ltd to have more control over the blockchain while keeping a good degree of decentralization. This ultimately improves our security while making the blockchain’s commercial & economic model more attractive. Besides these main features, we’ve included a few minor changes that contributes to the blockchain’s operability and scalability.

## Co-Inventor of Blockchain About Electroneum

Following the launch of our Moderated Blockchain, we spoke with **Dr. Scott Stornetta** who is widely known as the co-inventor of blockchain. His work from 1991 is even included in the original [Bitcoin whitepaper](https://bitcoin.org/bitcoin.pdf). He praised our initiatives and the application of our responsible blockchain.

The interview discusses everything from his vision for the future of blockchain to his opinions on the Electroneum project, as well as our approach to educating and enabling people in developing regions to learn new skills and explore new ways to earn.

**[Read the Interview](https://electroneum.prezly.com/founding-father-of-blockchain-scott-stornetta-talks-bitcoin-and-electroneum)**

 
## Proof of Responsibility
We have moved away from **Proof of Work** (used by the majority of cryptocurrencies) to a new way of mining Electroneum that we call **Proof of Responsibility**. It is a decentralised network layer that is run by responsible global organisations operating in the developing world that have been qualified to participate.

This achieves a number of things:

* It means that the **NGOs get the block reward** and they will use it to help the same target people in the countries we are empowering with ETN this year.
* A huge **increase in the security of the ETN network** via our highly trusted nodes makes us insusceptible to a 51% attack on our network.
* **Radically reduces power consumption of the Electroneum blockchain** making it more environmentally friendly than most other cryptocurrencies. Our new blockchain runs on ONE MILLIONTH of the electricity that it took before!
* **It educates NGOs about the Electroneum project** and furthers the legitimacy of all cryptocurrencies by making them valuable to influential organisations.

Since we have moved to **Proof of Responsibility**, these trusted responsible global organisations are now called **Validators** from a technical standpoint in which each **Validator** has its own unique software to verify transactions and a unique Validator Key that only works when applied to the correct daemon distribution.

For better security and 51% attack resistance, this new protocol introduces the concept of **non-sequential blocks** which means that a **Validator** can not create more than one block in sequence and this rule is assured by the network protocol.

A modified version of **Proof of Work** is still used internally by the **Validators** to create blocks on the correct chain. Modifications to the standard **Proof of Work** includes the ability to individually control the mining rate (a.k.a hashing power) of the **Validators** so that it’s easier on the CPU and very energy efficient. This mean that there’s no such a thing like hashing rush, as opposed to the standard **Proof of Work** algorithm in which miners compete with each other to have more hashing power, thus being rewarded with more emissions. Since the **Validators** network hashing power is controlled and stable, an orphan block scenario is very unlikely, enabling Electroneum’s blockchain to unlock transactions much more quicker than a network powered by the standard PoW.

Giving **trusted NGO’s** the ability to be a **Validator** also means that we guarantee the ETN emissions are given to real world entities that have social responsibility to help and make a difference on the life of thousands people while increasing people awareness of ETN, cryptocurrencies in general and enables then to the global economy. This move can already be seen in South Africa with **The Ubuntu Pathways** and **WONDER Foundation** as they are one of many Electroneum Validators.

Ultimately, the network security is drastically improved since it requires a malicious actor to take control over a minimum of two unique daemon distributions and the corresponding Validator’s key in order to actively mess with the blockchain. Even if this scenario come to fruition, we can instantly detect the compromised nodes and revoke their mining access in seconds by broadcasting a message to the whole network. This emergency safety measure is only possible because of our Moderated Blockchain model.


## Moderated Blockchain
We’ve changed the way our blockchain operates to hugely increase the security. We have created a new blockchain model called Moderated Blockchain.

Our moderated blockchain operates two layers:

**Layer One:** A second layer of highly trusted nodes is operated by us (Electroneum) as a company.
**Layer Two:** A decentralised layer where our trusted miners operate their mining servers and handle the ETN transactions.

People already trust Electroneum as a brand, they trust us with the instant payment system, the custodial wallet app system and with the KYC/AML system. This blockchain update utilises that trust to add a new layer of highly trusted nodes to the blockchain.

These highly trusted nodes passively monitor the blockchain for unusual or damaging activity and have the power to shut down that activity in seconds.

<p align="center">
    <img src="https://imgur.com/C2qJqLh.png">
</p>


The whole network is currently composed by 25 Validator nodes in which majority of those nodes are handled by NGOs, giving our Moderated Blockchain a high degree of decentralization. Besides the Validator nodes, exchanges and technical users are free to run their nodes on passive mode, meaning they won’t be able to actively create blocks, but they contribute in broadcasting blocks, transactions and other internal blockchain-related data.

In addition, we have created an emergency mechanism to shut down a Validator node if an unusual or damaging activity is detected. In this case, Electroneum Ltd broadcast a digitally signed message to the network through our trusted nodes operated by Electroneum that inform other nodes about the unusual/malicious activity.

Electroneum’s Validator List can be found at at vl.electroneum.com and the it is a base64-encoded JSON object/list. Each Validator key is generated by a Elliptic Curve Digital Signature Algorithm known as ED25519-Donna. The whole Validator List is also digitally signed three times using this algorithm, once with each of Electroneum's three master keys, in order to assure the information present on the above endpoint does come from Electroneum Ltd and cannot be modified by non-authorized users. The daemon verifies the authenticity of these signatures during startup, or when pulling a new list from the endpoint, before deciding that the list is genuine.

We have implemented a mechanism to pull the Validator list from the network if the domain is not accessible for more than 12 hours. It works on the Peer-to-Peer layer by sending a message to all peers asking for theirs validator list, and then verifies this list according to the same rules as the ones that came from the endpoint. The mechanism can identify potential malicious peer trying to fake their validator list, or a peer asking for the validator list more often than allowed, and block them permanently.

### See How our Blockchain Functions
A valued member of the Electroneum community produced the video below, highlighting the benefits of our Moderated Blockchain and how it works. If you’re interested in learning some of the more technical aspects of our blockchain, go ahead and watch the video below.

[![Electroneum Moderated Blockchain](https://imgur.com/riH79F2.png)](https://www.youtube.com/watch?v=qp2VCybC5s0 "Electroneum Moderated Blockchain")

### Electroneum Mobile Wallet

A secure mobile wallet for digital payments. **[Know more about Electroneum Mobile App](https://electroneum.com/features/mobile-application/).**

* Store all of your ETN in a safe and secure environment.
* Send and receive ETN instantly via a simple QR Code built into the app.
* Get rewarded with up to $3 USD worth of ETN every month.
* 20+ languages supported.
* Quickly check and calculate the value of ETN in Dollars, Rand, Euros etc.
* Top up your mobile airtime and data directly with ETN.
* Introduce new users and earn additional ETN.

<p align="center">
    <img src="https://imgur.com/kWHDKb5.png">
</p>

<a align="center" href="https://play.google.com/store/apps/details?id=com.electroneum.mobile">
    <p>
        <img src="https://imgur.com/L8vpuJT.png">
    </p>
</a>

<a align="center" href="https://itunes.apple.com/us/app/electroneum/id1270774992?ls=1&mt=8">
    <p>
        <img src="https://imgur.com/Seh9Y26.png">
    </p>
</a>


### Hardware Wallet Support

A hardware wallet is a cryptocurrency wallet which stores the user's private keys (critical piece of information used to authorise outgoing transactions on the blockchain network) in a secure hardware device. The main principle behind hardware wallets is to provide full isolation between the private keys and your easy-to-hack computer or smartphone.

Electroneum currently supports Ledger hardware wallet.


<p align="center">
    <img width="650" height="90" src="https://imgur.com/bF7IQM7.png">
</p>

* **The first & only certified hardware wallet on the market**
Ledger is the first and only certified hardware wallet on the market, certified for its security by ANSSI, the French cyber security agency.

* **Integrates a Secure Element (SE), the most secured chip**
Ledger hardware wallets integrate a certified chip, designed to withstand sophisticated attacks, and capable of securely hosting cryptographic data such as private keys.

* **The only device with a custom Operating System for more protection**
Ledger wallets are the only hardware wallet to have their own custom OS (BOLOS) to protect the device against malicious attacks and isolate applications from each other.

* **Genuine check to assure your device integrity at all time**
The genuine check developed by Ledger is an authentication ensuring that your Ledger device has not been tampered with or compromised by a third party.

**See more at [Why should you choose Ledger hardware wallets](https://www.ledger.com/academy/hardwarewallet/why-you-should-choose-ledger-hardware-wallets/)**


## Learn More About Electroneum

* [Benefits for Everyone](https://electroneum.com/benefits/)
* [Electroneum.M1 Phone](https://electroneum.com/m1/)
* [Mobile Application](https://electroneum.com/features/mobile-application/)
* [Instant Payments](https://electroneum.com/features/instant-payments/)
* [ETN Rewards](https://electroneum.com/features/mobile-mining-cloud-mining/)
* [KYC & AML Complience](https://electroneum.com/features/kyc-aml-compliance/)
* [Gig Economy: AnyTask](https://electroneum.com/features/gig-economy/)

## Development Resources

As with many development projects, the repository on Github is considered to be the "staging" area for the latest changes. Before changes are merged into that branch on the main repository, they are tested by individual developers in their own branches, submitted as a pull request, and then subsequently tested by contributors who focus on testing and code reviews. That having been said, the repository should be carefully considered before using it in a production environment, unless there is a patch in the repository for a particular show-stopping issue you are experiencing. It is generally a better idea to use a tagged release for stability.

**Anyone is welcome to contribute to Electroneum's codebase!** If you have a fix or code change, feel free to submit it as a pull request directly to the "master" branch. In cases where the change is relatively small or does not affect other parts of the codebase it may be merged in immediately by any one of the collaborators. On the other hand, if the change is particularly large or complex, it is expected that it will be discussed at length either well in advance of the pull request being submitted, or even directly on the pull request.

### Building from Source

See [Build & Run Documentation](docs/build-and-run.md).

### Running an Electroneum Node

See [Build & Run Documentation](docs/build-and-run.md).


## Technical Documentation

* [Daemon RPC Documentation](docs/daemon-rpc-documentation.md)
* [Wallet RPC Documentation](docs/wallet-rpc-documentation.md)
* [Exchange Listing Guide](docs/exchange-listing-guide.md)

## Vulnerability Response Process

HackerOne is a vulnerability coordination and bug bounty platform that connects businesses with penetration testers and cybersecurity researchers. It was one of the first companies, along with Synack and Bugcrowd, to embrace and utilize crowd-sourced security and cybersecurity researchers as linchpins of its business model; it is the largest cybersecurity firm of its kind. As of July 2018, HackerOne's network consisted of approximately 200,000 researchers, had resolved 72,000 vulnerabilities across over 1,000 customer programs, and had paid $31 million in bounties.

See [HackerOne Electroneum's Page](https://hackerone.com/electroneum).

## License

See [LICENSE](LICENSE).

## Copyright

Copyright (c) 2017-2020, The Electroneum Project

Copyright (c) 2014-2017, The Monero Project

Portions Copyright (c) 2012-2013, The Cryptonote developers