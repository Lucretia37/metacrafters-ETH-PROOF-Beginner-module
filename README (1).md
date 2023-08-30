# My Token

The orion (ORI) token smart contract is developed using Solidity .
## Description

This program is  for a token smart contract that implements the ability to burn (destroy) and mint (create) tokens on a blockchain network. The smart contract is designed to offer increased flexibility and control over the token supply by allowing users to remove tokens from circulation (burn) or create new tokens (mint) based on specific conditions.

## Getting Started

### Executing program

To run this program, you can use Remix.

```javascript
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;


contract MyToken {

 // public variables here
  string public tokenName = "ORION"; 
  string public tokenAbbry = "ORI"; 
  uint public totalSupply = 0


```

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile HelloWorld.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "HelloWorld" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the sayHello function. Click on the "HelloWorld" contract in the left-hand sidebar, and then click on the "sayHello" function. Finally, click on the "transact" button to execute the function and retrieve the "Hello World!" message.

## Authors

Metacrafter Chris  
[@metacraftersio](https://twitter.com/metacraftersio)


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
