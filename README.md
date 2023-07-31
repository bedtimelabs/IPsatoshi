
# IPsatoshi: A Bitcoin Scaling Project

IPsatoshi is a proposed Bitcoin scaling project aiming to integrate Bitcoin payments into the broader IPLD decentralized internet. It seeks to leverage the security and immutability of the Bitcoin blockchain and the Rootstock merge-mined Bitcoin sidechain to provide a platform for decentralized applications and services. The project is designed with the ambition to accommodate a larger number of users and transactions, while also providing a platform for decentralized applications and services.

## Core Components

1. **Bitcoin and Rootstock (RSK) Nodes:** These nodes would form the base on which the IPsatoshi layer rests. Rootstock is a merge mined Bitcoin sidechain that is incetive aligned with the game theory behind Bitcoin network security. The Rootstock sidechain will serve as a rootnet for IPsatoshi subnet nodes in the Interplanetary Consensus hierarchical consensus scaling architecture.
	https://dev.rootstock.io/

2. **InterPlanetary Consensus (IPC) with Mir and Trantor:** IPC is a scaling solution created by Consensus Labs of Protocol Labs and Filecoin. It allows for the creation of subnets, which are smaller networks within the larger network. These subnets can operate using their own consensus rules. They are highly configurable and allow for modular scaling. Mir and Trantor are tools used within IPC to facilitate these processes.
	https://docs.filecoin.io/basics/interplanetary-consensus/hierarchical-consensus/ 
 	https://github.com/consensus-shipyard 
 	https://github.com/filecoin-project/mir
 	https://github.com/filecoin-project/mir/tree/main/pkg/trantor

4. **WebNative File System (WNFS):** WNFS is a decentralized file system that could allow users to control their data and share it across applications and devices. It uses IPFS for data storage and IPLD for data structuring. It natively supports UCAN delegation and access control for filesharing etc.
	https://github.com/wnfs-wg/

5. **InterPlanetary Virtual Machine (IPVM) and Bacalhau:** IPVM and Bacalhau are decentralized computation protocols that could allow for the execution of WebAssembly (Wasm) code in a distributed manner. They use IPLD for data structuring and IPFS for data storage.
	https://github.com/ipvm-wg
	https://github.com/bacalhau-project

6. **UCAN + Channel Payments:** UCAN (User-Controlled Authorization Networks) is a protocol for decentralized identity and access control. It could allow users to control who can access their data and what they can do with it. In the IPsatoshi layer, UCAN/IPLD channel payments could be used to facilitate microtransactions and to incentivize the provision of services as well as allow for Bitcoin scale and remain accessible into the future. 
	https://github.com/ucan-wg 

7. **Decentralized Identifiers (DIDs):** DIDs are a new type of identifier that enables verifiable, decentralized digital identity. They could be used in the IPsatoshi layer to provide a secure and privacy-preserving mechanism for users to create and manage their digital identities. DIDs could be used to route channel payments and manage isolated user services.

## Potential AI Integrated GUI

The AI Integrated GUI could be a user-friendly interface for interacting with the IPsatoshi layer. It would provide a visual representation of the system and allow users to easily navigate and interact with the various modules. The AI assistant could use machine learning algorithms and language models to provide personalized assistance and to facilitate the creation and management of sophisticated user products. The GUI would be an IPLD native browser/OS allowing for intuitive usage of the various decentralized protocols and services available throughout the IPLD. The GUI should integrate Name Name System (NNS) for resolving names and decentralized website address/location making the user experience more intuitive. Ideally the GUI could interact with the host device and allow for the contribution or the marketing, negotiation, and sale of available device resources to the network or it's users.

## Starting Points and Potential Integrations

1. **Petals Project:** A research effort aimed at creating a distributed network for running and fine-tuning text-generating AI models.
	https://github.com/bigscience-workshop/petals

2. **Lilypad:** A proof-of-concept project that demonstrates the feasibility of a decentralized network for running and fine-tuning text-generating AI models.
	https://docs.lilypadnetwork.org/research-and-vision/whitepaper

3. **Fairgate with FairRISCV:** A protocol for multi-party computation (MPC) and secure data storage. The FairRISCV processor, part of the Fairgate suite, could run other virtual machines by executing the VMs compiled code, providing a secure local environment for the execution of the AI assistant and other applications.
	https://fairgate.io/assets/fairgate-whitepaper.pdf

4. **Quark ID:** A decentralized identity protocol that allows users to create and manage their digital identities in a secure and privacy-preserving manner.
	https://github.com/Quark-id/WhitePaper

5. **Taubyte:** A cloud-native layer for Web 3 and Edge Computing that offers features such as horizontal scalability, autonomy, resilience, and decentralization.
	https://github.com/taubyte

6. **CRDTs (Conflict-free Replicated Data Types):** CRDTs are data structures that allow multiple replicas to be updated independently and concurrently without coordination between them, and then merged, with a guaranteed eventual consistency. They could be used in the IPsatoshi layer to manage state in a distributed system.

7. **NNS (Name Name System):** A decentralized naming system that could be integrated into the GUI for resolving names and making the user experience more intuitive.
	https://talk.fission.codes/t/nns-the-name-name-system/3684

This project is in its early stages and is open to contributions and collaborations. Please feel free to reach out if you have any ideas or suggestions.

## Inspiration:

https://research.protocol.ai/publications/on-the-future-of-decentralized-computing/vukolic2021.pdf
https://rootstock.io/static/77b8332baf312e6f354e938e1ddbe252/rsk-white-paper-updated.pdf
https://bitcoin.org/bitcoin.pdf


## Media:

https://www.cod.cloud 

https://www.youtube.com/watch?v=e3N9x67B9jc Merge Mining and Why it Matters | Rootstock Summit 2022

https://www.youtube.com/watch?v=UJwPyo2c_7k
ConsensusDays 21 / Opening Talk: Vision for ConsensusLab and Decentralized Computing - Marko Vukolić

https://www.youtube.com/watch?v=J9Y4_bzGue4 IPC Quick Start: Zero-to-Subnet - Live Video Walk Through

https://www.youtube.com/watch?v=D_S46ljwXn8
ConsensusLab: Running an IPC Subnet (PL EngRes Demo Day March 2023)

https://www.youtube.com/watch?v=mh9b8PgVlU4
Realising Web3: 15 Months of ConsensusLab - Marko Vukolić

https://www.youtube.com/watch?v=R0FjrqdIxso
Applications of IPC - Juan Benet

https://www.youtube.com/watch?v=8lDwBnQ9Wuc
Protocol Labs – Vision

 https://www.youtube.com/watch?v=qPLhqPGDZyk 
InterPlanetary Consensus (IPC): Adding a consensus layer wherever is needed - Alfonso De la Rocha

https://www.youtube.com/watch?v=-S95I-O1MXo
UCAN + WNFS for Filecoin

https://www.youtube.com/watch?v=jhtEYr3ORfk
IPVM: Content Addressed Compute for an Open World - Brooklyn Zelenka

https://www.youtube.com/watch?v=MuHfrqw9gQA
Decentralizing Auth, and UCAN Too - Brooklyn Zelenka

https://www.youtube.com/watch?v=BFAMy5-VHak
Foundations for Open-World Compute: Homestar, an IPVM Tale - Zeeshan Lakhani

https://www.youtube.com/watch?v=CHiCEd36KtI
The Name Name Service - Blaine Cook

https://www.youtube.com/watch?v=3_nunGOY1j0
Shared Private Files Design in Webnative's WNFS, by Brooklyn Zelenka

https://www.youtube.com/watch?v=B0l0gFYxADY
Build With Bacalhau: Calling Bacalhau from FEVM smart contracts with Project Lilypad (Ally Haire)

https://www.youtube.com/watch?v=rIvLY7j-vfI
Compute Over Data Working Group Session #11 (Aligned.co and Petals.ml)

 https://www.youtube.com/watch?v=tFTExuukQPk
How to Build a Decentralized Cloud Computing - Samy Fodil (TauByte)
