# Matrixport View_Technology #5
Matrixport Research

### Summary
- The path towards ETH 2.0 is at its final stages, with the final testnet, “Medalla”, set to be released on August 4. Along with the launch of the final testnet before ETH 2.0 mainnet, the developer team released the validator launchpad, a key part of the testnet launch stage.

- While progress has been made towards ETH 2.0, there remains some potential problems along the way. The latest “Berlin” hard fork has been delayed till at least August as developers seek to provide time for the network to reduce its reliance on Geth and reduce the chances of a fault. In addition, a Consensys research indicated that ETH 2.0 might have potential vulnerability, in order to overcome it, the researchers have proposed a series of suggestions. However, Vitalik Buterin has mentioned that the potential vulnerability has been overplayed.

- In other Ethereum news, a new layer 2 scaling solution Zkopru has been implemented. Using both optimistic rollup and zk-SNARK, Zkopru supports private transactions on the Ethereum blockchain at a low cost while delivering high transaction speed.

- A new scalability technology for Bitcoin, Utreexo was recently demonstrated. The new Utreexo software aims to make Bitcoin nodes smaller and faster while keeping the same security and privacy as before. It is currently at the proof-of-concept phase and has yet to be fully developed into a true wallet software.

- Other key updates include: 1) Zcash releasing its latest hard fork “Heartwood” and new version of Frost Signature Scheme, 2) Filecoin delaying the launch of its final testing phase by two weeks, 3) Polkadot launch continues to progress into phase 3 and 4, 4) Kyber network launched Katalyst (a DeFi protocol) and KyberDAO (a community platform for Katalyst).

- There continues to be security breaches across the cryptocurrency market.

### Public Blockchain: Mainstream Tokens
**ETH Core Developers Delay “Berlin” Hard Fork**

*Hard Fork Delay☆☆☆*

- Ethereum developers have decided to delay the “Berlin” hard fork until at least August to stem clients’ concern regarding centralization

- Berlin is the protocol’s 10th scheduled hard fork which will potentially include four Ethereum Improvement Proposals (EIPs), a major step in ETH 1.0 transition to ETH 2.0

- As many users are dependent on Ethereum client Geth (79% of the nodes run on it), a bug could temporarily freeze the network. Ethereum core developers propose to delay the hard fork to allow other clients the opportunity to increase their share of the network, and reduce the chances of the blockchain from shutting down should the upgrade at Geth go awry

**Consensys Research Indicates Potential Vulnerability in ETH 2.0**

*Review of ETH 2.0☆☆☆*

- After receiving funding from MolockDAO, Consensys’s Tanner Hoban and Tom Borgers have combined their effort to review the network economics of Ethereum 2.0 spec v0.12

- The pair reported that the proposed PoS system security is highly dependent on volatility of ETH prices (uncontrollable variable), if ETH prices dropped suddenly, the cost of an attack on the blockchain will be much easier and cheaper

- To mitigate the potential vulnerability, the team recommends that ETH 2.0 to increase the base reward factor from 64 to at least 128 and to target at least 13.8% of ETH being staked to match the same network security as ETH 1.0

- While praising the review, Vitalik Buterin believes that the analysis overestimates the cost of a PoW attack, and the expected cost of a PoW attack is much lower than a PoS attack at the same reward level

**Ethereum Introduces a New Layer 2 Privacy Solution**

*Layer 2 Implementation☆☆*

- Wansoeb Lim, the founder of Ethereum 9¾, announced the implementation of an Ethereum layer 2 scaling solution, Zkopru, for private transactions on the Ethereum blockchain

- Through utilizing both optimistic rollup and zk-SNARK, Zkopru supports (1) private transfer and private atomic swap within the layer-2 network between ETH, ERC20, ERC721 at a low cost, and (2) withdrawal of assets from the layer 2 before finalization with its pay-in-advance feature

- The performance is expected to be 8,800 gas per private transaction, with max TPS of 105 when gas limit is 11.95m, and block time of 13.2 seconds

**Ethereum Will Launch Final Testnet Before Officially Releasing ETH 2.0 Mainnet**

*Proposed Testnet Launch ☆☆☆*

- After the success of the previous testnets, the software developer team for ETH2.0 has announced that they will be launching “Medalla” testnet, the final testnet before the release of ETH 2.0 mainnet on 4th August (1pm UTC)

- Danny Ryan, Ethereum Foundation’s ETH 2.0 coordinator, mentioned that two necessary criteria must be met before “Medalla” testnet will be launched, (1) “minimum genesis time” where it is a manually imposed parameter that details when the earliest chain can start based on the minimum number of validators required, (2) minimum number of validators that signed up for testnet, the number of validators required is set at 16,385 blockchain users, translating to 524,288 ETH in total

- In the event both criteria are not met, the launch will be delayed till both conditions are met after which the genesis will start in 48 hours

- In addition, ETH 2.0 developers have also recently released guidelines for “attacknets” and added $5,000 bounties for developers to stress test the network and helped to finalize each client’s specification

**Developers Release Validator Launchpad for ETH 2.0 Final Testnet**

*Launchpad Release ☆☆☆*

- With the Ethereum 2.0 final testnet (“Medalla”) set to be released on August 4, developers announced the release of the validator Launchpad for the multi-client testnet

- The launchpad is part of the testnet launch stage, prior to Phase 0, in which the network will move towards Proof-of-Stake (PoS)

- The validator Launchpad will allow users to participate in the testnet’s PoS and help to fine-tune the interface for a successful mainnet release

**Release of Utreexo to Help Bitcoin Achieve Scalability**

*Node Update Release ☆☆*

- The first demonstration of Utreexo, a new scalability technology for Bitcoin was released, allowing Bitcoin nodes to be smaller and faster while keeping the same security and privacy as full nodes

- Utreexo replaces the “UTXO set” of Bitcoin with a novel cryptographic accumulator allowing Utreexo to function as a full validating node while getting some benefits of a low-footprint SPV node

- The current Utreexo code is able to connect to a server, download the blockchain, and verify all the transactions and signatures, and do so without using much disk space, however it is currently at a proof-of-concept stage for a digital wallet, therefore, the current software is not a true wallet and unable to complete transactions or send/receive money

### Public Blockchain: Others

**Zcash Latest Hard Fork ”Heartwood” Makes Mining Private**

*Code Update ☆☆*

- Zcash latest hard fork “Heartwood” was successfully implemented on 16 July, with two new Zcash Improvement Proposals (ZIPs) being updated

- The first ZIP is “Shielded Coinbase” (ZIP 213) where Zcash consensus rules are modified to enable coinbase funds to be mined to shielded Sapling addresses, the second ZIP is “Flyclient” (ZIP 221) where Zcash adds support for lightweight clients that verify transactions

- Heartwood is the fourth hard fork in Zcash, the updates are backward incompatible, all nodes must by sync to the new software in order to use the Zcash blockchain

**Zcash Releases New Version of Frost Signature Scheme**

*Feature Update ☆*

- Partnering with University of Waterloo, Zcash Foundation announced an updated version of its flexible-optimized Schnorr threshold signature scheme, FROST

- The update aims to reduce interactions between participants by utilizing FROST signatures to sign transactions from the owners of a signing key, allowing a single party to sign the transactions

**Filecoin Delays its Final Testing Phase**

*Testnet Delay ☆☆*

- Filecoin has delayed the launch of its incentivized testnet (the final phase of testing for its blockchain-enabled storage network) by two weeks to 3 August

- The firm announced a calibration period from 20 July to 3 August to allow miners to test their mining set-ups and to get an idea of how the competition’s conditions affect their rewards

- The delay in the final testnet will result in its main launch window to be delayed, with the new timeline for the launch estimated to be between 31 August and 21 September

**Polkadot Launch Moves into Phase 3 & 4**

*Version Update ☆☆*

- As part of its multi-stage launch process, Polkadot has progressed into its phase 3 and 4 within a short span of time

- In phase 3, Polkadot elected a full council and Polkadot Chain Candidate 1 was upgraded to include full governance features

- In phase 4, Polkadot ran without the Sudo module (a super user account with access to governance function) and included all three elements of governance features, allowing Polkadot to transit from a permissioned network to a permissionless network governed by its stakeholders

### dApp and Layer 2 Updates
**dApp**

- Kyber Network launched Katalyst, a DeFi protocol and KyberDAO, a community platform to facilitate the decentralized governance of Katalyst. Kyber Network token holders can stake their KNC tokens on KyberDAO and govern the protocol by voting on proposals and parameters, while earning ETH rewards for their effort. (DeFi; Platform update ☆☆)

### Blockchain Adoption in Traditional Industries

**Financial Industry**

- Cambodia’s central bank has released its whitepaper detailing the technical details of its upcoming blockchain-based payment systems dubbed “Project Bakong”. Project Bakong will be a centralized system where the central bank aims to enable P2P transactions and real-time fund transfer in Cambodia. (CBDC; Whitepaper launch ☆)

- SEBA Bank (a leading integrated bank for digital and traditional asset services headquartered in Switzerland) and Corda-based Digital Asset Shared Ledger (DASL), entered into a strategic partnership for allow the bank to offer asset securitization services on Corda’s public network. (STO; Partnership achieved ☆)

- Dubai government announced the launch of its KYC blockchain platform with six banks joining the consortium. By utilizing the blockchain to facilitate the exchange of verified KYC data amongst the banks, the platform will allow companies to open bank accounts with participating banks instantly. (Government Blockchain Platform; Platform launch ☆☆)

### Security Incidents

**DeFi**

- 919,299 $VETH tokens, worth $900k USD, was hacked from a VETH smart contract and drained from the entire Vether Uniswap pool for just 0.9ETH ($200). VETH has promised to compensate affected victims. ☆

**Token**

- Ravencoin lead developer, Tron Black, announced that unidentified attackers exploited a Ravencoin vulnerability to mint extra RVN, increasing the total supply of 21 billion RVN by 1.5%. ☆

*Importance level：low-☆; medium-☆☆; high-☆☆☆*

*Sources: Coindesk, Coinness, Cointelegraph, Cryptoglobe, TechwireAsia, Medium, Kyber Network, Zcash, Filecoin， ETHResearch, analyzed by Matrixport*

***Disclaimer***

*Matrixport provides this analysis as general information only. Matrixport accepts no responsibility for the accuracy or completeness of any information herein contained and Matrixport shall not be responsible for any loss arising from any investment based on any forecast or other information herein contained. The contents of this materials should not be construed as an express or implied promise, guarantee or implication by Matrixport that the forecast information will eventuate. The cryptocurrency market is highly volatile. Buying, selling, holding, or investing in cryptocurrencies or related product carries various risks and is not suitable for all investors. Please seek expert advice, and always ensure that you fully understand these risks before participating in the cryptocurrency market.
Matrixport is not acting as a financial adviser, consultant or fiduciary to you with respect to any information provided. Any information available here is “general” in nature and for informational purposes only.*

