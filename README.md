


## How It Works

There are three major components of HealthChain:

1. React client (connected with MetaMask)
2. Solidity smart contract on Ethereum blockchain
3. Interplanetary file system (IPFS)

<p align="center">
<img src="https://d112y698adiu2z.cloudfront.net/photos/production/software_photos/002/187/785/datas/original.png" width="700"/>
</p>

The client first connects with crypto wallet, and use smart contract to mint a patient or doctor block if the public address of the user’s wallet is not registered.

The client can upload a record file to IPFS, which address is linked to a patient block in ETH chain. The client can get all record addressed stored in a patient block from smart contract, and get a record file by its address from IPFS.

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

> [jeffreyyu.dev](https://jeffreyyu.dev/) &nbsp;&middot;&nbsp;
> GitHub [@jeffreythecoder](https://github.com/JeffreytheCoder/JeffreytheCoder) &nbsp;&middot;&nbsp;
> Twitter [@jeffreyzepengyu](https://twitter.com/jeffreyzepengyu)

