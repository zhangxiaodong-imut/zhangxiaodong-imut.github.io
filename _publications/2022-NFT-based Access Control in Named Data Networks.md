---
title: "NFT-based Access Control in Named Data Networks"
collection: publications
category: conferences
permalink: /publication/2022-NFT-based Access Control in Named Data Networks
excerpt: 'EI检索，CCF推荐英文C类学术会议'
date: 2022-12-17
venue: '2022 IEEE Intl Conf on Parallel & Distributed Processing with Applications, Big Data & Cloud Computing, Sustainable Computing & Communications, Social Computing & Networking (ISPA/BDCloud/SocialCom/SustainCom)'
paperurl: 'https://doi.org/10.1109/ISPA-BDCloud-SocialCom-SustainCom57177.2022.00025'
citation: 'Hui Zhao, <b>Xiaodong Zhang</b>, Ru Li, "NFT-based Access Control in Named Data Networks", 2022 IEEE Intl Conf on Parallel & Distributed Processing with Applications, Big Data & Cloud Computing, Sustainable Computing & Communications, Social Computing & Networking (ISPA/BDCloud/SocialCom/SustainCom), Melbourne, Australia, 2022, pp. 139-146.'
---

The information cache technology in the Named Data Network (NDN) decouples the location of the Content Provider (CP) from the data, which leads to the data in the storage nodes facing security threats due to the lack of security control. Therefore, access control becomes extremely important. Because Ciphertext-Policy Attribute-Based Encryption (CP-ABE) supports sending data to a group of unknown recipients and realizes flexible and fine-grained access control, CP-ABE is often used in the access control of NDN. However, there are two problems when CP-ABE is directly applied to NDN: first, CP is required to be online all the time to verify the legitimacy of users and distribute decryption keys; Second, illegal users can obtain ciphertext. In view of the above problems, we propose an access control scheme based on Non-Fungible Token(NFT). Smart contracts distribute AttributeNFT and AccessNFT for users, and provide credentials for users to obtain keys and ciphertext. NDN routers only forward ciphertext data packets to valid users by implementing the filtering mechanism based on AccessNFT, and finally achieve the purpose of protecting data and achieving the safe distribution of data. Finally, we implement the system prototype on the Hyperledger Fabric and analyze the performance of the smart contract with the caliper. The experimental results show that the access delay of the smart contract is low and can meet the requirements of access control.
