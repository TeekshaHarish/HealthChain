# HealthChain

HealthChain is a decentralized application (DApp) that uses blockchain and decentralized storage technologies to securely manage and share medical records. The project consists of three main components: a React client integrated with MetaMask, a Solidity smart contract deployed on the Ethereum blockchain, and the Interplanetary File System (IPFS).

![HealthChain](https://d112y698adiu2z.cloudfront.net/photos/production/software_photos/002/187/785/datas/original.png)


## How It Works

HealthChain operates through the following key components:

1. **React Client with MetaMask Integration**  
   The React client interacts with MetaMask, a cryptocurrency wallet and gateway to blockchain apps. The client communicates with the smart contract to create patient or doctor blocks. If a user's wallet public address is not registered, the smart contract facilitates the creation of the corresponding block.

2. **Solidity Smart Contract on Ethereum Blockchain**  
   The Ethereum smart contract is pivotal in managing the registration of patients and doctors. It facilitates the creation of patient or doctor blocks associated with wallet addresses. These blocks contain references to medical records stored on IPFS.

3. **Interplanetary File System (IPFS)**  
   IPFS is a decentralized file storage system that HealthChain uses for securely storing medical records. Users can upload record files to IPFS, and the resulting IPFS addresses are linked to patient blocks on the Ethereum chain. The smart contract enables the retrieval of these records, which can then be fetched from IPFS.


## How To Use

Install Truffle globally if you haven't.

```sh
$ npm install -g truffle
```

Install Truffle dependencies and deploy smart contracts to local Ethereum network like [Ganache](https://trufflesuite.com/ganache/). 

```sh
$ cd truffle
$ npm install
$ truffle compile
$ truffle deploy
```

Install React dependencies and start React app. 

```sh
$ cd ../client
$ npm install
$ npm start
```

You should be able to see the application running at http://localhost:3000.


## Support

If you like this project, please leave a star ⭐️. This helps more people to know this project.

---

