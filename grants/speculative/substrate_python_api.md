# Project name
substrate python api

## Project Description
* Team will develop a Python library as substrate python api.
* The project will help a lot of Python developer to interact with substrate, then expand Substrate / Polkadot ecosystem.
* Web3 will be the future of IT infrastructure, we hope to be part of it.


## Team members
* Junius Zhou: full time researcher and developer https://github.com/juniuszhou
* Ruichao Xin: part time senior Python developer  https://github.com/adamxrc
* Junjun Wang: part time senior Python developer  https://github.com/tanghanerla

## Team Website	
No

## Legal Structure 
No

## Team's experience
* Junius Zhou: blockchain scientist in star mine Ltm. two years research experience in Ethereum,
               Polkadot and IPFS. Over 15 years software architect and development experience.
               Implemented the PoS blockchain, via Casper FFG based on Parity code.
               Implemented the community incentive coin economic model based on Solidity.

* Ruichao Xin: data scientist, experience in data analysis and distributed computing.
               familiar with Numpy, Pandas, Tensorflow and whole Python ecosystem.
               for blockchain, developed decentralized exchange based on Graphene.

* Junjun Wang: software architecture, experience in Python, flask, tornado.
               big data expert in Hadoop Spark and machine learning.
               for blockchain, developed wallet in Android platform.


## Development Roadmap
We will start the project from August, understand the specification of api provided by substrate rpc, 
also read the cpp version api as reference.
 The implementation will be started from September. Details as following:

* Septerber 2019
The wrapper of sr25519, generating key pair, signature and verification.
The blake2 hasher, xxhasher and parity encode decode implemented in python.
The decode of metadata for different versions, V6, V7
The subscriber of new block, new balance change, new events and so on.
* October 2019
The basic transfer, get the value of storage.
To call any method in any module via extrinsic.
The format of intrinsics and the builder of intrinsics
Shared subscriber client can publish new events according to session ID.
* November 2019
Documentation: explain each api provided by library and give several examples.
Test cases: write test case to verify library and help python developer to utilize library to develop Dapp in Python.
Publish and get feedback from Python developer, make the sdk easier to understand and usage.
* Future
Support Polkadot API
Test against Kusama
Fix bugs and improve efficiency

## Licensing
GNU GPL v3 license.

## Budget
We need about 30K dollar to complete the first three months project scope.
10K$ each month.
