Uranis on Secret MVP milestones

### Project Description 
Uranis is a decentralized adult content platform on Secret. The exponential rise of user-generated content in Web2 -- including, but not limited to OnlyFans, has continued to highlight loopholes in privacy for both audiences and the original creators. Web2 fundamentals exploit user data, where it is bought, sold, exchanged, or worse -- stolen. Secret Network, the first blockchain with customizable privacy, encrypts private metadata end to end. On Uranis, users get to choose what they share, who they share it with, and how long they share information for. Sensitive adult content should ensure this by default -- and this is now possible on Web3 on Secret. Truly peer-to-peer, not even the nodes operating on Secret can access the information being decrypted and processed on Uranis. 

### Problem / Solution
User-generated content websites like OnlyFans have a massive privacy bottleneck. Subscription spend and engagement with the OnlyFans Web2 platform is not private. Lack of trust and transparency discourages hundreds of thousands of potential users due to privacy concerns and lack of anonymity. This opens the opportunity to develop a decentralized solution serving creators and audiences alike looking for privacy, security, and anonymity. Without privacy, Web3 can turn into a dangerous diversion of Web2 architecture, where data and consumer behavior are public and available for big corporations to exploit them, or worse— ruin relationships between those closest to you. Uranis solves information privacy for the OnlyFans user case, protecting personal data when streaming user-generated content.

### Detailed product description
A sub-community that has evolved from the OG Sator Community has expressed interest in building a diversion from the traditional video streaming application to a subscription based platform on a private network, with an emphasis on user-generated content. 
 
Instantiating private SCRT smart contracts on Secret, Uranis will be Web3.0's encrypted, private OnlyFans derivative. To access user-generated content and subscriptions, users will pay using native tokens on Secret Network to access paid content and exclusive subscriptions for creators on the network. This way, transactions, subscriptions, and activity remain private and safeguarded by the SCRT network. Uranis is a decentralized Webapp with an IBC-enabled private tech stack on SCRT network. Uranis compiles custom Rust contracts for privacy where the creator has the option to safeguard exclusive content for VIPs only accessible if you own an NFT from or subscribe to that creator, with a password in the private metadata of the NFT authenticating a user to access. This protects the creator’s original content while also promoting fair revenue streams. This platform will be built with data protection and encryption at its core, with the privacy of all users a top priority.  

<img width="917" alt="Screen Shot 2022-12-06 at 1 53 08 PM" src="https://user-images.githubusercontent.com/54420219/205997838-cbe0571e-4880-4563-8d55-4db7e60b15b9.png">

### Go-to-market plan
* Go-to-market and commercialization plan (if applicable)
1. User Acquisition
2. Target 1,200,000 users Q4 2023, MAU 400k
3. Dual announcement to SCRT Network Community and Sator Community 
-SEO Agency for easy discovery of the product by popular keywords.
-Twitter spaces collaborations with top influencers and SpacesHosts.
4. Aggressive outreach on 4chan and Reddit. 
5. Brave campaign takeover: notifications and browser takeover. -Referral code deployment for New User Referrals Bonus
6. Incentivizing quality content creators from OnlyFans to join a new platform. 
7. Partnership Marketing —> Expand User Base. Consumer brands, sports teams, music festivals. Joint announcements.
8. Global Media Comms to increase Growth Efficiency —> Press coverage expanding brand awareness for new user downloads. Social campaigns that people care about. Agency specialization in press, highlighting the importance of privacy and security in Web3 on Secret Network.

### Team info

<img width="845" alt="TEAM" src="https://user-images.githubusercontent.com/54420219/205997907-9f785f86-b056-4387-a43c-7cb8def974c6.png">

### Overview

- **Total Costs:** Requested amount in USD for the whole project: $55,000 USD.

### Milestone 1 — Deploy a Secret Contract

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** of how the Secret Contract works. |
| 0c. | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile that can be used to test all the functionality delivered with this milestone. |
| 0e. | Article | We will publish an **article**/workshop that explains how Secret Contract works |
| 1. | Overview |  In this milestone we will compile & deploy the Secret Contract, producing the wasm contract file. |
| 2. | Deploy to Testnet | Upload optimized contract.wasm to explorer.secrettestnet.io with test SCRT from faucet. |
| 2a. | Query | Successfully query the smart contract code once deployed to testnet. |
| 3. | Instantiate the Secret Contract | Provide JSON input data to create an instance of the project. |
| 3a. | Custom Logic | Modify contract.rs for custom logic. Write to decentralized storage and provide an environment. |


### Milestone 2 — Webapp set-up.

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0. | Overview |  In this milestone we will complete initial setup of Webapp and configuration with SecretJS Javascript SDK.|
| 1. | Domain | Domain purchase / set up |
| 2. | SecretJS Install | Install Secret.js and begin WebApp dev using Next.js / Node framework |
| 3. | Bundlr Install | Bundlr combined with livepeer.js for ability to play a video on IPFS and Arweave with [livepeer.js] (https://livepeerjs.org/examples/react/dstorage-playback) this solution has CDN and transcoding built in.|
| 4. | API, HTTPS Connection | SecretJS interacts with a REST API exposed by nodes in the Secret Network. |
| 5. | SecretJS  | Front-end dApp connected to the Secret Network using SecretJS. SecretJS combined with a Secret contact provides built in computational and programmable data privacy.|



### Milestone 3 — Video Streaming using a Secret NFT

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0. | Overview |  In this milestone we will play encrypted video directly on site instead of downloading and decrypting offline. |
| 1. | HLS protocol | HTTP Live streaming protocol that is industry standard for video streaming with native support for playing encrypted videos. HLS format = m3u8 file describing list of video files + length. |
| 2. | [Encryption Keys] (https://scrt.network/blog/secret-deep-dive-unlocking-web3-movies-with-secret-nfts) | Allow player to get encryption key from the private metadata inside a Secret NFT by injecting dynamic key into the m3u8 file. |
| 3. | [Video.JS] (https://videojs.com/) | Video.js is an open source browser video player that allows key override in m3u8 files before the video segment is fetched and played. |
| 4. | Encryption key URI  | Replace the encryption key URI in manifest file with “key://0.key” to echo, verify and decode the proper key.|
| 5. | End-to-End testing  | Perform proper testing over HTTPS, ensure it is secure end-to-end, and that Secret NFTs can be decrypted to stream live video. |

### Milestone 4 — Content Creator Profile Features of Subscription-based Webapp

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0. | Author Profile | adding content, information about yourself, and reaching out to users. |
| 0a. | Subscription | Secret NFTs, add support for different tokens including USDC |
| 0b. | Share content | Publish content on demand as encrypted Secret NFTs |
| 0c. | Recieve payment | Receiving payment with fee retention |
| 0d. | Interaction |  Chats, private calls, messaging |

### Milestone 5 — User Profile Features of Subscription-based Webapp

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0. | User Profile | quick login, add user info, search. |
| 0a. | Payment | the ability to use different payment methods to subscribe |
| 0b. | Content purchase | Purchase personalized content with Secret NFTs, subscription content |
| 0c. | Suggestions | selection of recommendations |
| 0d. | Notifications |  Display updates and info to user |

### Milestone 6 — Administrator Features of Subscription-based Webapp

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0. | User Profile Management | Blocking, deleting, reports in case of rules violation. |
| 0a. | Creator Profile Management | Requests creators to register, create profile, post content |
| 0b. | Set commission percentage | Determine commission percentage based on personal factors |
| 0c. | View Payments | processing of all cryptocurrency txs |
| 0d. | Manage alerts | Send types of notifications |

### Milestone 7— End-to-End Tests

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0  |
| 0b. | Documentation | We will provide both **inline documentation** of the code and a basic **tutorial** that explains how a user can start using OnlyFud and show how the new functionality works. |
| 0c. | Testing and Testing Guide | Core functions will be fully covered by comprehensive unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Docker | We will provide a Dockerfile that can be used to test all the functionality delivered with this milestone. |
| 1. | End-to-end tests |  We provide end-to-end tests that test the interplay between the new components. |
