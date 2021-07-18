Truffle v5.3.12 (core: 5.3.12)
Solidity v0.5.16 (solc-js)
Node v10.16.0
Web3.js v1.3.6


# Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

The DApp User Interface when running should look like...

![truffle test](images/ftc_product_overview.png)

![truffle test](images/ftc_farm_details.png)

![truffle test](images/ftc_product_details.png)

![truffle test](images/ftc_transaction_history.png)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

```
Give examples (to be clarified)
```

### Installing

A step by step series of examples that tell you have to get a development env running

Clone this repository:

```
git clone https://github.com/udacity/nd1309/tree/master/course-5/project-6
```

Change directory to ```project-6``` folder and install all requisite npm packages (as listed in ```package.json```):

```
cd project-6
npm install
```

Launch Ganache:

```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```

Your terminal should look something like this:

![truffle test](images/ganache-cli.png)

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

Your terminal should look something like this:

![truffle test](images/truffle_compile.png)

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```
Migrate to Rinkeby test network

```
truffle migrate --network rinkeby
```

** Get some test ether from https://faucet.rinkeby.io/ into your main address as deployment needs gas. Instructions on how to get test ether from the faucet are available in the site above.

Your terminal should look something like this:

![truffle test](images/truffle_migrate.png)

Test smart contracts:

```
truffle test
```

All 10 tests should pass.

![truffle test](images/truffle_test.png)

In a separate terminal window, launch the DApp:

```
npm run dev
```

## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open.
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.


## Authors

See also the list of [contributors](https://github.com/your/project/contributors.md) who participated in this project.

## Acknowledgments

* Solidity
* Ganache-cli
* Truffle
* IPFS

## IPFS is not used in the project

## Below UML diagrams are included in the project

* Activity Diagram - Activity Diagram.drawio

```
Activity diagram shows the actors in the whole process and the activities that each of the actor is associated with. It also shows the interaction between the actors
```

* Sequence Diagram - Sequence Diagram.drawio

```
Sequence diagram shows the actors and the sequence in which the activities can be perform by the respective actors
```

* State Diagram - State Diagram.drawio

```
State diagram shows the various states of the object in the whole process and which actor is responsible/associated with that particular state
```

* Class Diagram - Data Model Diagram - Class Diagram.drawio

```
Class diagram shows the data structure in the process
```

## Transaction hash
0x93648a31f396d95ef3f017a3100ee032178bd5279423e612f25d54c70636beb4

## Contract Address
0x16E104f9459C4A82a3feC54728b3d73086e36c8D


