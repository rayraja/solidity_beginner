# Simple Smart Contract

The purpose of this file is to highlight some of the core capabilities of a Solidity Smart Contract

## Description

The contract highlights the following functionality
1 Public variables that store the details about the coin (Token Name, Token Abbrv., Total Supply)
2 Contract will have a mapping of addresses to balances (address => uint)
3 A mint function that takes two parameters: an address and a value. The function then increases the 
  total supply by that number and increases the balance of the “sender” address by that amount
4 Contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It 
  will take an address and value just like the mint functions. It will then deduct the value from the total supply 
  and from the balance of the “sender”.
5 Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal to the #
  amount that is supposed to be burned.

## Getting Started

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., test.sol). Copy and paste the code from raytoken.sol (found in this repository) into your new file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile test.sol" button. (Rrep

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "Test" (or your chosen name) contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the the various functions:

burn - burn tokens  
mint - mint tokens  
balances - retrieve a balance  
tokenAbbrv - retrieve the token abbbreviation  
tokenName - retrieve the token name  
totalSuppy - retrieve the total supply  


## Authors

Contributors names and contact info

Rahil Raja
rayraja2014@gmail.com


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
