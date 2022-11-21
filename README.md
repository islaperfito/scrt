# Secret Network: OnlyFud MVP milestones

### Overview

- **Total Estimated Duration:** 6 months
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 4 FTE)
- **Total Costs:** Requested amount in USD for the whole project: $60,000 USD.

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
