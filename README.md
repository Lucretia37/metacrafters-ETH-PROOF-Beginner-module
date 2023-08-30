# My Token 

This smart contract, named "MyToken," integrates essential functionalities such as the ability to burn and mint tokens.
## Description

This repository contains the source code for a token smart contract that implements the ability to burn (destroy) and mint (create) tokens on a blockchain network. The smart contract is designed to offer increased flexibility and control over the token supply by allowing users to remove tokens from circulation (burn) or create new tokens (mint) based on specific conditions.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. 

```javascript
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;


contract MyToken {

 // public variables here
  string public tokenName = "ORION"; 
  string public tokenAbbry = "ORI"; 
  uint public totalSupply = 0;

```

To compile the code, go to any solidity compiler .  

Once the code undergoes the compilation process, you can initiate the deployment of the contract by navigating to the "Deploy & Run Transactions" tab present in the left-hand sidebar. From the dropdown menu, choose the "MyToken" contract, and then activate the "Deploy" button.

Upon the successful deployment of the contract, you gain the ability to engage with its functionalities by invoking the "burn" and "mint" functions. Locate the "MyToken" contract within the left-hand sidebar, and proceed to select the desired function—either "burn" or "mint." Finally, execute the function by activating the "transact" button, resulting in the execution of the function and the retrieval of pertinent outcomes associated with the "MyToken" contract's burn and mint features.

## Authors

Lucretia37


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
