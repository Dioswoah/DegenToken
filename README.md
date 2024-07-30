# DegenToken

This smart contract deploys a coin on the Snowtrace testnet and includes several functions for interaction. The DegenToken.sol code follows the ERC20 standard and is designed for Degen Gaming. It works with Metamask to connect the Remix IDE to Snowtrace, allowing users to see real-time updates of transactions. The contract owner can mint Degen Tokens, while users can transfer, burn, check balances, and redeem tokens for in-game items or merchandise.

## Description

The Solidity code provided uses the ERC20 standard to issue Degen Tokens specifically for Degen Gaming. By integrating with Metamask, users can link Remix IDE to Snowtrace for live transaction updates. Only the contract owner has the right to mint new tokens, whereas all users can transfer, burn, check their token balance, and use tokens to claim items or merchandise from the store.

![image](https://github.com/user-attachments/assets/fb7fa193-3a7a-49e8-966a-5820021a21cd)


## Getting Started

### Installing
1. Go to the contracts folder and open the DegenToken.sol file.
2. Open Remix IDE (https://remix.ethereum.org/) and create a new file, pasting the content of DegenToken.sol into it.

### Executing Program
![image](https://github.com/user-attachments/assets/e010bd39-3b01-439c-9d22-409812b69d00)
1. In Remix IDE, under the Solidity Compiler tab on the left, select the EVM version (Istanbul or Berlin) for compatibility.
2. Compile the DegenToken.sol file by clicking the blue compile button.

![image](https://github.com/user-attachments/assets/8968ff07-8f39-49da-9adb-6a26df4b6a29)
3. Under the Deploy and Run Transactions section on the left, select Injected Provider - Metamask as the environment and connect your Metamask account.
4. Ensure that your Metamask account contains AVAX.
5. Deploy the contract by clicking the orange deploy button.
6. After deployment, copy the contract address.
7. Visit Snowtrace Testnet (https://testnet.snowtrace.io/) and paste the contract address to view the transaction history.

Example:
Snowtrace link: https://testnet.snowtrace.io/address/0x22E2F1F52C14728411B392AAFE8F65D749466778
![image](https://github.com/user-attachments/assets/f1752f4b-218b-436f-8614-4fc518f7ee94)

## Functions
- **mint**: Lets the contract owner mint new tokens to a specified address.
- **burn**: Allows any token holder to burn a specified number of their own tokens.
- **redeem**: Enables users to redeem tokens (by burning them) for items, requiring a sufficient balance.
- **transfer**: Permits users to transfer tokens to a specified address.

## Authors
Marc Joshua Ramos

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
