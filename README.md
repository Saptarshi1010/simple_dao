Simple DAO solidity smart contract


A smart contract that functions as a simple decentralized autonomous organization. This is in development (i.e. not extensively tested for deploying on the Ethereum mainnet). It has been tested using Remix.

Basic instructions to run:
1.Open Remix and deploy the vending machine solidity contract first and then the simpleDAO contract. You can import this repo into the Remix IDE directly or simply copy and paste the code.

2.Solidity is a statically typed programming language and you must compile the code before deploying the smart contract.

3.Copy and paste the address of the vending machine into the simpleDAO constructor.

4.Specify how long members will be allowed to vote (seconds)

5.Add in name of proposals: ["buy_cupcakes", "no_cupcakes"]

6.Only the chairperson can give the right to vote in the DAO to other addresses.

7.If the majority of the DAO members who voted selected "buy_cupcakes", then the DAO will send 1 ether to the digital vending machine and in return the DAO will recieve one cupcake.


# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
