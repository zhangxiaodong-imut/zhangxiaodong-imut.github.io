---
title: "DART: a Low-cost and Secure Cross-chain scheme for Popular Digital Assets"
collection: publications
category: conferences
permalink: /publication/2024-DART a Low-cost and Secure Cross-chain scheme for Popular Digital Assets
excerpt: 'EI检索，CCF推荐英文C类学术会议'
date: 2024-04-21
venue: '2024 IEEE Wireless Communications and Networking Conference (WCNC)'
paperurl: 'https://doi.org/10.1109/WCNC57260.2024.10571060'
citation: 'Hui Zhao, <b>Xiaodong Zhang</b>, Jinshan Shi and Ru Li, "DART: a Low-cost and Secure Cross-chain scheme for Popular Digital Assets", 2024 IEEE Wireless Communications and Networking Conference (WCNC), IEEE, 2024: 1-7.'
---

In blockchain-based data marketplaces, the cross-chain solution based on relay chains has become an effective way to support digital asset transfer between heterogeneous blockchains. If a digital asset is popular, it will be frequently transferred between multiple data marketplaces. Digital assets are typically represented as (Non-fungible Tokens) NFTs. However, when utilizing a cross-chain transfer scheme based on a relay chain that involves locking, unlocking and burning of the NFT, it can lead to significant transaction costs. Due to the frequent minting and burning of popular NFTs, they tend to consume a significant amount of gas, resulting in high transaction costs. To address this issue, we propose the DART scheme, a secure and low-cost cross-chain transaction scheme for popular digital assets based on (dynamic NFT) DNFT and relay chain. The scheme mainly includes three aspects: Firstly, the initial owner of (Data NFT) DataNFT locks it onto the gateway contract on SChain, mints a (Cross-chain NFT) CNFT on the relay chain that references the DataNFT for resale, and minted DataNFT on the destination blockchain until the CNFT is no longer being resold. Secondly, the DNFT standard is utilized to implement CNFTs. The DNFT standard records the transaction hash of each CNFT resale, ensuring the secure reselling of DataNFTs. Thirdly, the metadata of DataNFT is encrypted to ensure its security during cross-chain transmission. Finally, we selected Axelar Network as the relay network and successfully implemented a prototype of the system. The experimental results demonstrate the feasibility of our proposed scheme.
