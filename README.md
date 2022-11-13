# KaseiCoin_Crowdsale

This Solidity app simulates an Initial Coin Offering through a crowdsale of Kasei Coin tokens. The smart contract is developed around the ERC-20 fungible token standards.

<br/>

----

## Technologies

This application uses the following technologies:

Remix is used for developing, compiling and deploying the Solidity smart contracts
* [Remix](https://remix.ethereum.org)

Ganache is used as the 'local' Ethereum blockchain network for testing purpose.
* [Ganache](https://trufflesuite.com/ganache/)

MetaMask is used as the interface between Ganache and Remix
* [MetaMask](https://metamask.io)


<br/>

---

## Usage

Go to the Remix website, create two new smart contracts and copy/paste the code from the KaseiCoin.sol and KaseiCoinCrowdsale.sol files. Compile both files and deploy the KaseiCoinCrowdsaleDeployer smart contract. KaseiCoinCrowdsaleDeployer is in KaseiCoinCrowdsale.sol. The KaseiCoinCrowdsaleDeployer will automatically deploy the KaseiCoinCrowdsale and KaseiCoin contracts.


The following images videos showed the tests done on the deployed smart contracts.

<br/>


1. Deploying the contracts
![Deploy Contracts](media/01_Deploy_Contracts_01.png)
![Deploy Contracts](media/01_Deploy_Contracts_02.png)

<br/>

2. Account used to deploy the contracts showed a reduction in ETH due to the payment of gas fees
![Gas fees consumed in deploying contracts](media/02_Gas_Fee_Used_02.png)
![Gas fees consumed in deploying contracts](media/02_Gas_Fee_Used_01.png)

<br/>


3. Deployed contracts
![Deployed Contracts](media/03_Deployed_Contracts.png)

https://user-images.githubusercontent.com/80833988/129816362-144cfbb1-163a-4999-a9de-173854a7c643.mov

<br/>

4. The following video shows the purchase of tokens from the crowdsale by an investor
https://user-images.githubusercontent.com/80833988/129816362-144cfbb1-163a-4999-a9de-173854a7c643.mov

<br/>


---

## Contributors

This application is written by James Tan, with code snippets provided UBC Extension.

<br/>

---

## License

MIT.