# ethereum avax module 3
# create my own Token in solidity and connect it with Local Hardhat
This repository is made for my ethereum avax module 3 project which is used to create MY TOKEN using contracts and connect by using local hardhat.

## Problem Statement
For this project we will write a contract to create our own token on a local hardhat network. once we have our contract we will be able to burnt , mint and tranfer the tokens. 


## Description
This program  written in Solidity by using a simple contract, solidity is  a programming language used for developing smart contracts on the Ethereum blockchain.
This contract with name MyToken has 3 public access variable that contain (Token Name,Token Abbreviation and Total supply).
Then in the next step  we mapped address into balances.
Then we use a Function with name Mint that increase the total supply and  increases the balance of the (sender) address by that amount.
Then we use  burn function to burn the balance and subtract the burn amount from total_supply and balances of the address provided.
Here,  we  have to provided a if statement to check balance is greater than the value to be burnt, if balance is less than value than the further code will not execute.
Then we will compile this contract and then deploy this contract then connet it to local hardhat network.




## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at (https://remix.ethereum.org/.)

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., error.sol). Copy and paste the following code written by me into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set heigher to "0.8.1" (or another compatible version), and then click on the "Compile error.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken1" contract from the dropdown menu, and then click on the "Deploy" button.

After compilation connect the contract to local hardhat network.

Once the contract is deployed, you can interact with it by passing the address. call any of the three function and set the value, and you can burn, mint or check the balance of your NFT.

## Author

Sulochana

## License

This project is licensed under the MIT License - see the LICENSE file for details
