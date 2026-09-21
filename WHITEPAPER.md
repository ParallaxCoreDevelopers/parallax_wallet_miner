# Parallax (PLX) Whitepaper

## Independent Scrypt Proof-of-Work Cryptocurrency

**Project:** Parallax  
**Ticker:** PLX  
**Network:** Parallax Mainnet  
**Consensus:** Proof of Work  
**Mining Algorithm:** Scrypt  
**Native Asset:** PLX  
**Official Website:** https://parallaxcoin.xyz/  
**Block Explorer:** https://explorer.parallaxcoin.xyz/  
**Source Code:** https://github.com/ParallaxCoreDevelopers/parallax_wallet_miner  

---

## 1. Introduction

Parallax (PLX) is an independent open-source Proof-of-Work cryptocurrency operating on its own blockchain.

PLX is the native currency of the Parallax network. It is not an ERC-20, BEP-20, or other token issued on top of an external blockchain and therefore does not have a token contract address.

The Parallax blockchain begins from its own Genesis Block 0 and maintains its own independent transaction and block history.

Parallax uses the Scrypt Proof-of-Work mining algorithm and is designed around a straightforward model in which miners contribute computational work to produce blocks, validate transactions, secure the network, and receive newly generated PLX as block rewards.

The official Parallax Core application combines a full blockchain node, native wallet, integrated Scrypt miner, security features, and network diagnostic tools in one Windows desktop application.

---

## 2. Project Objectives

Parallax was created around several core objectives:

- Maintain an independent public blockchain.
- Use Proof-of-Work consensus and Scrypt mining.
- Allow users to independently operate full nodes.
- Provide a native wallet without relying on custodial services.
- Make mining accessible directly through the official desktop application.
- Keep blockchain activity publicly verifiable.
- Publish the project source code for independent review.
- Develop an open network that can support miners, nodes, exchanges, explorers, and other services without requiring centralized control of the blockchain.

Parallax is designed as a native cryptocurrency network rather than as a token project built on an existing smart-contract platform.

---

## 3. Parallax Blockchain

The Parallax network maintains its own blockchain and Genesis Block 0.

### Mainnet Genesis Block

Genesis block hash:

`72b26135d67f262b8f9c33277c4be8499482d3cba475bc36291f6729dea08ae5`

Genesis transaction:

`f350acf4761d6947161447bde2720fa39e77fb11509ccd7314a0701253e157da`

The blockchain can be independently inspected through the public Parallax Explorer:

https://explorer.parallaxcoin.xyz/

The explorer provides public access to blockchain information including:

- Blocks
- Transactions
- Addresses
- Mined PLX supply
- Network statistics
- Blockchain height
- Network hashrate

Parallax maintains its own chain history and does not share historical blocks with another cryptocurrency.

The software is based on established open-source Bitcoin-family technology, but the Parallax blockchain itself begins independently from its own Genesis Block 0.

---

## 4. Proof-of-Work Consensus

Parallax uses Proof-of-Work consensus.

Miners perform computational work to search for valid blocks. When a valid block is produced and accepted by the network, it extends the Parallax blockchain.

Proof-of-Work provides several functions:

- Orders transactions into blocks.
- Makes alteration of historical blockchain data computationally expensive.
- Allows independent nodes to determine the valid blockchain.
- Distributes newly generated PLX through mining.
- Provides an open mechanism for network participation.

Parallax uses the **Scrypt** Proof-of-Work algorithm.

Scrypt is a widely implemented mining algorithm supported by existing mining software and hardware.

---

## 5. Mining and Block Rewards

PLX enters circulation through blockchain mining.

The current Parallax block subsidy is:

**50 PLX per block**

Miners may participate using the integrated miner provided with Parallax Core or compatible external Scrypt mining software.

Mining is not dependent on ownership of a special token, staking balance, or validator permission.

Participants contribute hashing power and compete to produce valid blocks according to the network consensus rules.

Mining statistics and network hashrate can be independently observed through the Parallax block explorer.

Parallax may also be mined through compatible mining pools where supported. Pool payout policies are determined by individual pool operators and do not alter the underlying blockchain block reward.

---

## 6. Parallax Core

Parallax Core is the official Windows software for interacting with the Parallax network.

It combines several functions in one application:

**Full Node. Wallet. Miner. Security. Network Tools. One application.**

### Full Blockchain Node

Parallax Core can download, verify, and maintain a local copy of the Parallax blockchain.

Running a full node allows a user to independently verify network activity rather than relying entirely on a third-party service.

### Native PLX Wallet

Parallax Core contains a native wallet for:

- Sending PLX
- Receiving PLX
- Managing addresses
- Viewing transaction history
- Managing locally controlled wallet data

Users remain responsible for protecting their wallet files, passwords, backups, and operating systems.

### Integrated Mining

Parallax Core contains integrated Scrypt mining controls.

Users can start and stop mining directly through the graphical interface without requiring a separate command-line mining application.

External Scrypt mining software may also be used where compatible.

### Network Tools

Parallax Core includes tools for inspecting network and node activity, including:

- Peer connections
- Network traffic
- Blockchain information
- Node information
- RPC console access
- Diagnostic information

These tools provide users with greater visibility into the operation of their own node.

---

## 7. Wallet Security

Parallax Core includes wallet security functionality intended to help users protect their PLX.

Available functionality includes:

- Wallet encryption
- Passphrase protection
- Passphrase management
- Wallet backups
- Local key storage
- Message signing
- Message verification
- Address management

Wallet security remains a shared responsibility between the software and the user.

Users should maintain secure backups and protect wallet passphrases.

Loss of required wallet credentials or wallet data may result in loss of access to funds.

Private keys, wallet passphrases, wallet backup files, RPC passwords, VPS credentials, and SSH credentials should never be shared publicly.

---

## 8. Native PLX Asset

PLX is the native currency of the Parallax blockchain.

It does not depend on another blockchain for settlement.

PLX therefore has:

- No ERC-20 contract
- No BEP-20 contract
- No third-party token contract
- No wrapped-token requirement for native network transfers

Transactions are recorded directly on the Parallax blockchain.

The standard unit supports eight decimal places.

---

## 9. Network Infrastructure

Parallax uses peer-to-peer networking between full nodes.

Current mainnet network ports are:

- **P2P:** 19339
- **RPC:** 19340

The P2P port is used for communication between blockchain nodes.

RPC is intended for local or trusted administrative applications and should not normally be exposed openly to the public internet.

Public blockchain information should instead be obtained through services such as the Parallax Explorer.

---

## 10. Public Block Explorer

The official public explorer is:

https://explorer.parallaxcoin.xyz/

The explorer provides an independently accessible view of the live Parallax blockchain.

It can be used to examine:

- Current block height
- Individual blocks
- Transactions
- Addresses
- Mined supply
- Network hashrate
- Recent blockchain activity

The explorer does not require users to provide private keys, passwords, or wallet credentials.

The blockchain itself remains the authoritative record of PLX transactions and supply.

---

## 11. Supply and Economic Model

New PLX is produced through Proof-of-Work mining.

The current block subsidy is 50 PLX.

The live mined supply should be determined from the blockchain and can be independently verified through the Parallax Explorer.

The project has published an intended long-term economic model based around a total economic allocation target of **1 billion PLX**.

The intended allocation model is:

| Category | Allocation | Long-Term Target |
|---|---:|---:|
| Mining | 40% | 400,000,000 PLX |
| Development | 30% | 300,000,000 PLX |
| Liquidity | 20% | 200,000,000 PLX |
| Community | 10% | 100,000,000 PLX |

These figures describe the intended long-term economic model.

They should not currently be interpreted as a protocol-enforced hard maximum supply while the project's long-term emission implementation is being reviewed and aligned with active consensus rules.

No claim should therefore be made that the current software enforces a one-billion-PLX hard cap unless and until such a consensus rule is implemented and publicly verifiable.

Current circulating and mined supply should always be determined from live blockchain data.

---

## 12. Development

Parallax is developed as an open-source project.

Source code is publicly available at:

https://github.com/ParallaxCoreDevelopers/parallax_wallet_miner

The repository contains project documentation and publicly available mainnet source code.

Open-source development allows independent developers, exchanges, infrastructure providers, miners, and users to inspect the implementation used by the network.

Changes affecting blockchain consensus require particular care because incompatible consensus changes can create separate blockchain histories.

---

## 13. Decentralized Participation

The Parallax network is designed so that multiple independent participants can operate infrastructure.

These participants may include:

- Full-node operators
- Solo miners
- Mining pools
- Exchanges
- Block explorers
- Wallet users
- Developers
- Infrastructure providers

The existence of an official wallet, explorer, or other project-operated infrastructure does not prevent independent parties from creating their own compatible services.

As participation develops, additional mining pools, nodes, exchanges, explorers, and services may operate independently of the Parallax Core Developers.

---

## 14. Exchange and Market Integration

PLX is designed as a native transferable cryptocurrency and may be integrated by cryptocurrency exchanges that support the Parallax blockchain.

Exchange integration requires operation of compatible Parallax node infrastructure and generation of native PLX deposit and withdrawal addresses.

A market price is not defined by the Parallax protocol.

Where PLX is traded on exchanges, its market price is determined by actual orders and transactions between market participants.

The blockchain itself records transfers of PLX but does not establish a fiat or stablecoin exchange value.

---

## 15. Transparency

Parallax provides several publicly accessible resources intended to allow independent verification of the project and network.

Official resources include:

**Website**  
https://parallaxcoin.xyz/

**Block Explorer**  
https://explorer.parallaxcoin.xyz/

**Source Code**  
https://github.com/ParallaxCoreDevelopers/parallax_wallet_miner

**Mainnet Genesis Block**  
`72b26135d67f262b8f9c33277c4be8499482d3cba475bc36291f6729dea08ae5`

Blockchain activity, supply, transactions, and mining activity should be verified using live network data rather than relying solely on project statements.

---

## 16. Project Identity

The current Parallax project launched in 2026.

Its official identity is:

**Parallax (PLX)**

Official website:

https://parallaxcoin.xyz/

The current Parallax blockchain is not affiliated with earlier cryptocurrency projects or historical assets that may previously have used the name **ParallaxCoin** or the ticker **PLX**.

The current project can be distinguished through its official website, public GitHub repository, independent Genesis Block 0, public block explorer, and active Parallax blockchain.

---

## 17. Security Considerations

Cryptocurrency software involves operational and financial risks.

Users should:

- Download software only from official project sources.
- Verify release checksums when available.
- Encrypt wallets containing funds.
- Maintain offline backups.
- Protect wallet passphrases.
- Never disclose private keys.
- Never expose RPC credentials publicly.
- Keep operating systems and security software maintained.
- Independently verify addresses before sending transactions.

Mining, cryptocurrency ownership, and exchange trading may involve financial risk.

Parallax does not guarantee the future market value of PLX.

---

## 18. Conclusion

Parallax is an independent Scrypt Proof-of-Work blockchain with PLX as its native currency.

The project combines a public blockchain, open-source full-node software, native wallet, integrated mining capability, wallet security features, network tools, and a public block explorer.

Its blockchain begins from its own Genesis Block 0 and operates independently of token platforms such as Ethereum or BNB Chain.

Parallax is intended to provide a transparent and independently verifiable cryptocurrency network in which users can operate nodes, hold their own wallet keys, participate in mining, inspect blockchain data, and develop compatible infrastructure.

---

## Official Resources

**Website:** https://parallaxcoin.xyz/  
**Explorer:** https://explorer.parallaxcoin.xyz/  
**GitHub:** https://github.com/ParallaxCoreDevelopers/parallax_wallet_miner  
**Ticker:** PLX  
**Consensus:** Scrypt Proof of Work  
**Current Block Subsidy:** 50 PLX  
