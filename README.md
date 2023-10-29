# Token Creation

This project focuses on developing a smart contract that facilitates token creation, including minting and burning functions, along with the ability to check the balance for a given address.

## Description

The objective of this project is to create a Solidity smart contract for a token named “Alpha.” The provided code contains essential functions for minting and burning tokens, along with a mapping structure to maintain balances associated with specific Ethereum addresses.

## Getting Started

To run this program, you can use Remix, an online Solidity IDE. 

* Open Remix : Go to the Remix website (https://remix.ethereum.org/).

* Create a New File :
   - Click on the "+" button in the file explorer on the left.
   - Create a new file with the name "My_Token.sol" or any other name you prefer.

* Paste the Code :
   - Copy and paste the code present in CreateToken.sol file into the newly created file in Remix.

* Compile the Code :
   - Click on the "Solidity Compiler" tab on the left panel.
   - Under the "Compiler" section, choose the appropriate version. In this case, select "0.8.18" to match the pragma statement in your code.
   - Click the "Compile My_Token.sol" button to compile the code.

* Deploy the Contract :
   - Click on the "Deploy & Run Transactions" tab on the left panel.
   - Click on the "Deploy" button. This will deploy your contract to the selected network.

* Interact with the Contract :
   - Once the contract is deployed, you can interact with it using the provided functions (mint and burn).
   - Expand the contract section on the "Deploy & Run Transactions" tab to see your contract and its functions.
   - Use the "mint" and "burn" functions to create and destroy tokens. Provide the required parameters (address and value) and click the "transact" button to execute the functions.

* Check Contract State :
   - You can also check the state of the contract, including the `tokenName`, `tokenAbv`, `totalSupply`, and the `balance` of different addresses by calling the appropriate functions in the contract section.

## Authors
Reethu Thota <br>
reethu.thota@gmail.com

## License
This project is licensed under the MIT License.
