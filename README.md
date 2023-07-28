# ethereum avax module 3
# create my own Token in solidity and connect it with Local Hardhat
This repository is made for my ethereum avax module 3 project which is used to create my own token using contracts and connect by using local hardhat.

## Problem Statement
For this project we will write a contract to create our own token on a local hardhat network. once we have our contract we will be able to burnt , mint and tranfer the tokens. 


## Description:

1) For the first step we will create a contract with public variable that stores the details of the coins, it has 3 public access variable that contain (Token Name,Token Abbreviation and Total supply).
2) The Token Name,Token Abbreviation will be string type and the total supply witll be unsigned integer type.
3) Now for the second step we will create a mapping of address to balances and make it public type, the working of the mpping is - if we pss an address it will return a token amount that the address has i.e. their balance.
4) Next we wil create a mint fuction with parameters address and value, Now we will increase the total supply by the amount provided using += operator.
5) Lastly we will create aburn function whose working is the total opposite of the mint function i.e. it will detroy the tokens.
6) It will take address and value and deduct the value from the totalsuplly and the balance of the address.
      We should ensure that our burn function has a conditional statement ti ensure that the balnce of the account is greater than or equal to the amount that is supposed to be burned.




## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at (https://remix.ethereum.org/.)

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., error.sol). Copy and paste the following code written by me into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set heigher to "0.8.1" (or another compatible version), and then click on the "Compile error.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken1" contract from the dropdown menu, and then click on the "Deploy" button.

After compilation connect the contract to local hardhat network.

Once the contract is deployed, you can interact with it by passing the address. call any of the three function and set the value, and you can burn, mint or check the balance of your NFT.

## Author

SHRESHTHA PAL

## License

This project is licensed under the MIT License - see the LICENSE file for details
